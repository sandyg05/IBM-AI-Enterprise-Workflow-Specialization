## ETL

Extract, Transform, Load (ETL) is a process to move data from its original source to another target destination. The target destination is often a database or a data warehouse, but it could be a simple flat file. The commonly referred to acronym, ETL, consists of three distinct stages:

Extract

Read data from a source (e.g. database) and extract the desired subset of data. The purpose of this step is to retrieve all the required data from the source system with minimum resources. This step needs to be designed in a way that it does not affect the source system negatively in terms of performance or response time. Often this means that the regularly scheduled pull is performed at night, when the system is not under load.

Transform

The transform stage cleanses and prepares the extracted data using lookup tables or rules. Data from heterogeneous sources can be combined at this stage. The transform step also includes validation of records, rejection of data (if they are not acceptable). The commonly used processes for transformation are conversion, sorting, filtering, clearing the duplicates, standardizing, translating and looking up or verifying the consistency of data sources.

Load

Loading is the last stage of an ETL process. The load function writes the extracted and transformed data (all of the subset or just the changes) to a target data location. Often the target data are inserted as a record in a target database using SQL insert statement.

ETL has been around for a long time and it often implies the use of SQL databases. When ETL is described we often come up short covering all of common tasks associated with this part of the AI workflow. Some examples of technologies that have forced the industry to re-think the boundaries of ETL are:

source and target locations are not always SQL databases
maintaining quality data can become more expensive than just storing everything
streaming data as an alternative
NoSQL technologies and enterprise solutions IBM’s enterprise data warehousing solution are common alternatives.
Another important limitation to the traditional ETL philosophy is that up front in the process decisions have to be made about which data are going to be important. Sometimes the specific data or form that the data must take is not evident. Sometimes, the best data for a model can change if a different model is selected. Flexibility in the early stages of the AI workflow is critical to avoid complications or errors later on.


## Data ingestion in the modern enterprise

ETL is still used today for simple use cases, usually as part of a larger process. However, the complexity of today’s data-intensive use cases precludes the use of ETL in most large enterprises.

For these reasons we refer collectively to the content of this part of the AI enterprise workflow as data ingestion rather than ETL.

The archaic process of ETL has given way to data ingestion approaches that emphasize the use of massive amounts of data in place, where analysis tools are used against data sources that have not been moved or transformed. This approach allows for much more flexibility since the transformation of data is isolated to each individual pipeline that is accessing a large data source. Different pipelines can be used to flexibly transform data from a large data store.




## Enterprise data stores for data ingestion

Large data stores are the norm in large enterprises. The concept of a data lake reflects this reality. Data lakes are very large collections of data stored in their natural formats, usually as object blobs or files. Today’s data scientist must be proficient in building data pipelines that tap directly into such large collections of raw data, then process the data to gain insights.

Along with data lakes, technologies such as Apache Hadoop enable large enterprises to store very large amounts of data, and to access the data quickly for analysis. Hadoop has two advantages that make it useful in large enterprises. First, it is designed from the ground up to be fault tolerant. A Hadoop cluster runs on an array of individual commodity servers designed to cleanly fail over without loss of data or processing power. Second, Hadoop clusters allow for parallel execution of data analysis code against the blocks of data stored in the cluster. This enables the rapid execution of complex analyses against huge amounts of data.

While many data ingestion pipelines draw data directly from sources such as data lakes and Hadoop clusters, data scientists in large enterprises will sometimes work with data engineers to build a data warehouse. A data warehouse keeps data gathered and integrated from different sources (e.g., a data lake) and stores the large number of records needed for long-term usage by machine learning systems. A data warehouse is typically built using data extractions, data transformations and data loads. After selecting data from the sources of origin, data ingestion procedures resolve problems in the data and ready it for research and modeling.

Modern large enterprises have adopted sophisticated data management processes and systems to handle very large amounts of data. With large datasets and complex use cases, data ingestion involves the ability to use data from a wide variety of sources, mixing and matching those sources to create data pipelines that feed machine learning models.


## Why we need a data ingestion process

Cleaning, parsing, assembling and gut-checking data is among the most time-consuming tasks that a data scientist has to perform. In fact, the problem is not new as statisticians have been dealing with the same dilemma for many decades. The time spent on data cleaning can start at 60% and increase depending on data quality and the project requirements. One could debate the proportion and surely it depends on the team, the data and a number of other factors, but one statement that is difficult to argue against is

> Very significant portions of time are often devoted to data ingestion pipelines.

For many enterprises data is the most important asset and when this is true maintaining the quality of those data is paramount. Poor data quality can result in project delays, budget projection shortfalls, or other avoidable challenges. The quality of data refers to both the observations themselves and the maturity of the data itself. Companies may consider improving their data ingestion infrastructure and methods for the benefits it could return.



## Data ingestion and automation

Data engineers exist in many organizations to ease the burden of the data ingestion process. If the target data source is a database, then there are some useful tools and procedures under the umbrella term database testing. Data warehouse automation is the general term used to improve the overall process of data ingestion. Testing is an essential piece of data warehouse automation, because the quality of downstream models are tied to the quality of the available data.

**IMPORTANT**: The testing process is data-centric and it helps validate that data has been transformed and loaded into the target destination as expected. It is a critical part of data ingestion automation.

Testing can involve comparing large volumes of data which may contain millions of records. The size of the data can pose challenges, but in some cases a more significant challenge can be heterogeneous nature of data. You may find that you are using data of various types and sources: flat files, relational databases, open API feeds like twitter to XML web services and many others. Connecting all these heterogeneous sources in a standardized way can be a non-trivial task. With more sources of data comes an increased need for testing.

In reality, any form of data movement from source to target can be considered as data ingestion. In large enterprises like hospitals it is not uncommon to have dozens of independent systems saving data—oftentimes in a redundant way. A common database as a target is next to impossible due to logistical and privacy concerns, but a well-constructed gateway in the form of an Application Programming Interface (API) and API keys could be a viable solution towards automation.

Outside of more comprehensive solutions automation can be achieved with scripting. If the data ingestion code exists as a script (e.g. Bash or Python), then cron jobs are an incredibly powerful way to automate the process. The testing process can be automated with cron as well.





## Sparse matrices are used early in data ingestion devel

Once a well-trained machine learning model has been deployed, the data ingestion pipeline for that model will also be deployed. That pipeline will consist of a collection of tools and systems used to fetch, transform, and feed data to the machine learning system in production.

However, that pipeline cannot be finalized during the development of the machine learning model it feeds. Finalizing the process of data ingestion before models have been run and your hypotheses about the business use case have been tested often leads to lots of re-work. Early experiments almost always fail and you should be careful about investing large amounts of time in building a data ingestion pipeline until there is enough accumulated evidence that a deployed model will help the business.

Instead of building a complete data ingestion pipeline, data scientists will often use sparse matrices during the development and testing of a machine learning model. Sparse matrices are used to represent complex sets of data (e.g., word counts) in a way that reduces the use of computer memory and processing time.

There are Python libraries available in the SciPy package to work with sparse matrices. The code block below imports this library as well as NumPy for calculations.