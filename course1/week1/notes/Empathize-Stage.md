---
title: Empathize Stage
date: 2020-04-21 23:47:10
tags:
keywords:
categories: [AI Workflow, Process Model]
description:
---

## Empathize Process
1. Get as close to the source of data as possible usually by interviewing the people involved
2. Identify the business problem
3. Obtain all of the relevant the data
4. Translate the business problem into a testable hypothesis or hypotheses



## Identifying the business opportunity: Through the eyes

### Our story
**The first stage of any project in a large enterprise is to identify the business opportunity. In the world of design thinking, this begins with the Empathize stage**. During this time, you and your team are gathering as much information as possible to understand the challenges faced by your AAVAIL.

You are suprised by the fact that you, a data scientist, are being asked to help out with interviews, observations, process mapping, and various design thinking sessions. These techniques as well as many others are used during the empathize stage to gather **as much information as possible** so that a problem may be defined.

As a data scientist, this process should be used to guide your investigative process. Ultimately, your top priority is to analyze the data coming out of Singapore, understand the problem and fix the situation. **The involved parties are subscribers, data engineers, data scientists, marketing and management**. You are going to need to talk everyone involved in the data generation process. This is why you're spending time on interviews and observations.

**Asking questions is a critical part of getting the process started**. You will want to be naturally curious gathering details about the product, the subscriber, and the interaction between the two. This information gathering stage provides both a perspective on the situation and it will help you formulate the business question.

In the short sections below, we provide guidelines for asking questions and beginning with an investigative mindset.

### Articulate the business question

There are generally many business questions that can be derived from a given situation. It is an important thought exercise to enumerate the possible questions, that way it makes the discussion easier when you work with the involved stakeholders in order to focus and prioritize. In this situation here are some ways of articulating the business case.

- Can we use marketing to reduce the rate of churn?
- Can we salvage the Singapore market with new products?
- Are there factors outside of our influence that caused the situation in Singapore and is it temporary?
- Can we identify the underlying variables in Singapore that are related to churn and can we use the knowledge to remedy the situations?
- The business problem in all of these examples is written shown in terms of the data we have.

NOTE: This case study can be approached in many different ways and there may not be a clear right or wrong. During the various modules of this course, we will provide guidance when there are multiple paths to choose from.


### Prioritize

It is logical, but there is a need to prioritize If there are several distinct business objectives. In this case maybe one is related to reducing chrun directly and another is about profitability.

There are three major contributing factors when it comes to priority.

#### Stakeholder or domain expert opinion
In situations where considerable domain expertise is required to effectively prioritize (e.g. Physics, Medicine and Finance) prioritization will likely be driven by the people closest to the domain.

#### Feasibility
- Do we have the necessary data to address the business questions?
- Do we have clean enough data to address the business questions?
- Do we have the technology infrastructure to deploy a solution once the data are modeled?

#### Impact

When looking at Impact we’re purely looking at expected dollar contribution and added value from a monetary perspective. When possible, calculating the back-of-the-envelope ROI is a crucial step that you can do. This is an expectation and not real ROI calculation, but it is a guiding principle nonetheless.

The ROI calculation should be an expected dollar value that you can generate based on all available information you currently have in your organization combined with any domain insight you can collect.

Measuring the back-of-the-envelope ROI calculation could make use of any of the following:

- Estimates for fully-loaded salaries of employees involved
- Cost per unit item and/or time required to produce
- Number of customers, clients, or users
- Revenue and more


## Scientific Thinking for Business

### Our Story

Data science involves lots of investigation via trial and error. The investigations are based on evidence and this is one of the strongest reasons why data science is considered a "real" science.

You will be using a scientific process with your work at AAVAIL. This will help you to organize your work as well as be able to clearly explain everything you are doing to the AAVAIL leadership.

Let's take a look now at some guidance and best practices for engaging with a **scientific mindset**.


### Science is a process and the route to solving problems is not always direct

A common argument made by statisticians and mathematicians is that data science is not really a science. This is untrue, mainly because data science involves a lot of **investigations** through sometimes chaotic data sets, in search of meaningful patterns that might help in solving particular problems.

Since data science implies a scientific approach, it is important that all data scientists learn to adopt and use a scientific thought process. **A scientific thought process of observation, developing hypotheses, testing hypotheses, and modifying hypotheses is critical to your success as a data scientist**.

Pulling in data and jumping right into exploratory data analysis can make your work prone to exactly the types of negative issues that plague data science today. There are a number of well-discussed issues revolving around data science and data science teams not living up to promised potential.

At the heart of this problem is the process of communicating results to leadership. It should begin with a meaningful and well-articulated business opportunity. If that opportunity is stated too simply, as say, increasing overall revenue then the central talking point for communication is too vague to be meaningful from the data side.


> The business scenario needs to be communicated in a couple of ways:
1. Stated in a testable way in terms of data
2. Stated in a clear way that minimizes the influence of confounding factors

### Testable hypotheses

There is no one single best way to articulate a business opportunity as a testable hypothesis. In some cases the statement will be intuitive, but in other cases there will be some back and forth with stakeholders and domain experts.

### Guidelines for creating testable hypotheses

1. Become a scientist of the business

Spend a little bit less time learning new algorithms and Python packages and more time learning the levers that make your specific business go up or down and the variables that impact those levers.

2. Make an effort to understand how the data are produced

If it comes down to it, sources of variation can be explicitly accounted for in many types of models. If the data come from a database you should ask about the process by which the data are stored. If the data are compiled by another person then dig into the details and find out about the compiling process as well as the details of what happened before the data arrived on their desk.

3. Make yourself part of the business

Do not under any circumstances become siloed. Proactively get involved with the business unit as a partner, not a support function.

4. Think about how to measure success

When thinking about what course of action might be most appropriate, keep at the forefront of your mind how you will measure business value when said action is complete.

**IMPORTANT**: Data Science is NOT Business Intelligence. BI analysts serve to derive business insights out of data. There is without a doubt some overlap, but the job of a data scientist is to investigate the business opportunity and solve it.

There is a balancing act to maintain between directly addressing the business need and ensuring that you have thoughtfully studied the problem enough to ensure that you can account for most of the likely contingencies. The scientific method can be of some guidance here.


### Thinking scientifically about the business scenario

A major goal of this process is to make the business objectives clear to leadership. Some of these individuals are technical and some are not, so as a good rule-of-thumb get in the habit of articulating the business problem at a level that everyone can understand. Stakeholders and leadership need to know what you are trying to accomplish before you begin work. They also need to be aware from the start what success would look like. Science is an iterative process and many experiments produce results that some might consider a failure. However, experiments that are properly setup will not fail no matter the result–the result may not useful but you have gained valuable information along the way.

Experiments in this context could refer to an actual scientific experiment (e.g. A/B testing) or it could be more subtle. Let’s say you work for a company that collects tolls in an automated way, and you want to identify the make and model of each car in order to modify pricing models based on predicted vehicle weight. After talking with the stakeholders and the folks who implemented the image storage solution you are ready to begin. The experiment here has to do with how you begin. You may think that there is enough training data to implement a huge multi-class model and just solve most of the problem. If you approach it that way then you are hypothesizing that the solution will work.

For those of you who have done much image analysis work, you could guess that approach would likely result in a significant loss of time. If we take a step back and think scientifically, we could approach the solution from an evidence driven perspective. Before investing a significant amount of time you may try to see if you can distinguish one make and model from the rest before adding more classes. You may want to first pipe the images through an image segmentation algorithm to identify the make of the car. There are many possible ways to build towards a comprehensive solution, but it is important to determine if either of these piecemeal approaches would have any immediate business value.

This might be a good time for a reminder about the steps in the scientific method.

### The Scientific Method

It is the process by which science is carried out. The general idea is to build on previous knowledge to in order to improve an understanding of a given topic.

1. Formulate the question
2. Generate a hypothesis to address the question
3. Make a prediction
4. Conduct an experiment
5. Analyze the data and draw a conclusion

We will continue with an interactive example, but first it is important to note that **Scientific experiments must be repeatable in order to become reliable evidence.**


#### Question

The question can be open-ended and generally it summarizes your business opportunity. Let’s say you work for a small business that manufactures sleds and other winter gear and you are not sure which cities to build your next retail locations. You have heard that Utah, Colorado and Vermont are all states that have high rates of snowfall, but it is unclear which one has the highest rate of snowfall.

#### Hypothesis

Because the Rocky mountains are higher in elevation and they are well-known for fresh powder on the ski slopes you hypothesize that both Utah and Colorado have more snow than Vermont.

#### Prediction

If you were to run a hypothesis test Vermont would have significantly less snow fall than Colorado or Utah

#### Experiment

You hit the NOAA weather API to get average annual snowfall by city. We have compiled these data for you in snowfall.csv. You could use a 1-way ANOVA to test the validity of your prediction, but let’s start by looking at the data.

```python
# First we read in the data

import pandas as pd
df = pd.read_csv("../data/snowfall.csv")

# Next, subset the data to focus only on the states of interest

mask = [True if s in ['CO','UT','VT'] else False for s in df['state'].values]
df1 = df[mask]


# Finally, create a pivot of the data that focuses only on the relevant summary data

pivot = df1.groupby(['state'])['snowfall'].describe()
df1_pivot = pd.DataFrame({'count': pivot['count'],
                          'avg_snowfall': pivot['mean'],
                          'max_snowfall': pivot['max']})
print(df1_pivot)

#        count  avg_snowfall  max_snowfall
# state
# CO       5.0         37.76          59.6
# UT       2.0         51.65          58.2
# VT       1.0         80.90          80.9
```


#### Analyze

There is not enough data to do a 1-way ANOVA. The experiment is not a failure; it has a few pieces of information.

There is not enough data
There is a small possibility that VT gets more snow on average than either CO or UT
Our degree of belief in the conclusion drawn from (2) is very small because of (1)
The notion of degree of belief is central to scientific thinking. It is somehow a part of our human nature to believe statements that have little to no supporting evidence. **In science the word belief, with respect to a hypothesis is proportional to the evidence**. With more evidence available, ideally, from repeated experiments, one’s degree of belief should change. Evidence is derived from the process described above and if we have none then we are stuck at the question stage and a proper scientific hypothesiscannot be made.

The other important side to degree of belief is that it never caps out at 100 percent certainty. Some hypotheses have become laws like Newton’s Law of Gravitation, but most natural phenomena in the world outside of physics cannot be explained as a law.

A hypothesis is the simplest explanation of a phenomenon. A scientific theory is an in-depth explanation of the observed phenomenon. Do not be mistaken with the word theory, there can be sufficient evidence that your degree of belief all but touches 100%, and is plenty for decision making purposes. A built-in safeguard for scientific thought is that our degree of belief does not reach 100%, which leaves some room to find new evidence that could move the dial in the other direction.

There are additional factors like external peer review that help ensure the integrity of the scientific method and in the case of implementing a model for a specific business task this could mean assigning reviewers for a pull request or simply asking other qualified individuals to check over your work.


## Gathering Data

### Our Story

Your first step at AAVAIL, just like everywhere else, it to look at the data sources. You soon discover that AAVAIL has data everywhere! There is no shortage of data. It looks like they have managed to store every type of transaction with their subscribers.

You will need a smart way of managing all of this data. Let's take a look now at some best practices for managing data in a large enterprise.

### Documenting your data

Too often data scientists will find themselves deep in the process of developing a solution, based on the data that was provided to them, before they realize that the data itself is flawed, inaccurate or in some other way non-ideal. Developing the habit of creating a simple document with at least a description of the ideal data needed to test the hypotheses around the business problem may seem like an unnecessary step, but it has potential to both:

- Streamline the modeling process
- Help ensure that all future data come in an improved form



### ETL

The process of gathering data is often referred to as Extract, Transform, Load (ETL). Data is generally gathered (or extracted) from heterogeneous sources, cleaned (transformed) and loaded into a single place that facilitates analysis. Before the advent of the modern data scientist’s toolkit data was often staged in a database,data lake or a data warehouse. Still today data is frequently staged to facilitate collaboration, but there are tools now that enable more possibilities today than ever before. Jupyter Lab has an extension called data grid that allows it to read delimited files with millions or even billions of rows. Then tools like Dask help you scale your analyses. To ensure that projects are completed in a reasonable amount of time the initial pass at ETL should use a simple format like CSV, then a more complex system can be built out once you have accomplished the Minimum Viable Product (MVP).


### Common methods of gathering data

#### Plain text files

Plain text file can come in many forms and generally the open function is used to bring the data into a Python environment. This is a flexible format, but because no structure is imposed, custom scripts are generally needed to parse these files and these scripts do not always generalize to new files.

The large majority of data science projects involve a modeling step that requires input data in a tabular numeric format. In order to extract data from a plain text file you may need to identify patterns in the text and use regular expressions (regex) to pull out the relevant information. Python’s built-in regex library is known as re.

On the other hand if the data you are working with consists of natural language, then there are a number of libraries that can work directly with the text files. The two main libraries are:

- spaCy
- NLTK

Also, scikit-learn has become a standard tool in the overall workflow when processing these files.

- scikit-learn’s text tutorial

These tools can be applied to unstructured text to generate things like word counts, and word frequencies. We saw an example of this in the Data science workflow combined with design thinking example.

#### Delimited files

One of the most commonly encountered ways of storing structured data is in delimited files, where rows of tabular data are stored in lines of a text file and the columns within each row are separated by a special “delimiter” character such as a comma or a tab character.

This simple structure helps account for the popularity of these formats, with probably the most widely used being Comma-Separated Values (CSV). CSV files are both human and machine readable, and have minimal overhead in terms of the proportion of the file devoted to defining the structure of the data when compared to most other file formats. As such Pandas comes with methods for both reading and writingCSV files. (Note that these functions can also handle other delimiters like tab or the pipe character “|”, but commas are the default.)

Spreadsheet programs like Microsoft Excel that are used for analyzing tabular data also read from and write to files in CSV format. The native Excel file format (often with file extensions .xls or .xlsx) can also be considered a delimited file type. Though these files also contain a significant amount of extra information related to things like styling that are separate from the actual data. Nonetheless, since these files are commonly used to save datasets, Pandas also has a method for reading them: pandas.read_excel.

HINT: A best practice when loading data from plain text or delimited files is to separate the code for parsing into its own script. Because the files are read line by line in a separate Python call, it is more memory efficient and this separation of tasks helps with automation and maintenance.

It is a common mistake to try to read large files into pandas then use the date frame environment to parse. If your parsing (cleaning) task is simple then use a parser. Here is a simple example:

```python
#!/usr/bin/evn/python

"""
simple example of a parser
"""

import os
import csv

## specify the files
file_in = os.path.join("..","data","snowfall.csv")
file_out = os.path.join("..","data","snowfall_parsed.csv")

## create an outfile handle (needs to be closed)
fidout = open(file_out,"w")

## use the csv module to read/write
writer = csv.writer(fidout)

## generic parsing function
def parse_line(line):
    
    if line[3] not in ["HI","NC","OR"]:
        return None
    else:
        return line + ['new_data']
    
## for each line in the file read in the first file that you need to reference
with open(file_in) as csvfile:
    reader = csv.reader(csvfile, delimiter=',')
    header_in = reader.__next__()
    writer.writerow(header_in + ["new_column"])
    for line in reader:
        line = parse_line(line)
        if line:
            writer.writerow(line)
   
fidout.close()
print("done parsing")
```
The highlighted lines show where this parser changes the original data by filtering and adding an additional column.

#### JSON files

While delimited files are well suited for housing data in flat tables, datasets with more complex structures require different formats. The JavaScript Object Notation (JSON) file format can accommodate quite complex data hierarchies. Python’s built-in library handles reading/writing JSON files.

```python
import json
data = json.load(open('some_file.json'))
```


In addition, pandas.read_json is also available for loading JSON files.

At its base a JSON object can be thought of as analogous to a Python dictionary or list of dictionaries. For example a table of data from a JSON file could be read into Python as a list of dictionaries where each dictionary represented a row of the table, and the keys of each dictionary were the column names. This formatting is somewhat inefficient for simple tabular data, with column information explicitly repeated with each row, but is useful when representing more intricate relationships in the data. JSON objects often have a highly nested structure that you can think of as dictionaries within dictionaries within dictionaries.

For example, modern websites track a great deal of information about users’ interactions with the site and the varied nature of these interactions make a table structure too rigid for recording them. In practice, most sites send JSON objects back and forth between the user’s computer and the website’s server. Many data scientists’ primary source of data are ultimately these JSON objects.


#### Relational databases

Relational databases, i.e. those that impose a schema on datasets are a major source of data for data science projects. Database tables can naturally be converted into Python objects like Pandas DataFrames. Reading data into a Python environment requires opening a connection to a database and there are various libraries for managing this connection, depending on the type of database to be accessed. Some Relational DataBase Management System (RDBMS) and their corresponding interface utilities for Python:


|RDBMS |  Python Connector|
|:--|:--|
|MySQL |  MySQL Connector|
|PostgreSQL | Psycopg|
|SQLite | sqlite3|
|Microsoft SQL | pyodbc|


Each of these tools are designed with maintaining the integrity of the database in mind, including methods for rolling back updates, and ways to safeguard against SQL Injection vulnerabilities. As such, the process of querying the database and ingesting the results can seem fairly involved. For example, here is a basic flow for getting the contents of a table from a PostgreSQL database using psycopg2.


```python
import psycopg2 as pg2
conn = pg2.connect(database='my_db', user='my_username')

# create a cursor to traverse the database
cur = conn.cursor()

# cursor object executes a query, but does not automatically return results
cur.execute("SELECT * FROM my_table")

# Return all query results
results = cur.fetchall()
# WARNING: If the result set is large, it may overwhelm the memory
# resources on your machine.

cur.close()
conn.close()
```


While the steps required to connect, query, and disconnect from a relational database are more involved than when loading in data from a file on your local machine, the table structure from the database schema basically guarantees that the data will fit cleanly into a Pandas DataFrame or NumPy Array.


#### NoSQL databases

“NoSQL” is a catch-all term referring to “non SQL” or “non relational”, or more recently “not only SQL”. Usually meaning that the method for housing data does not impose a schema on it (or at least not as tightly constrained as in relational databases). This tradeoff gives greater flexibility in what and how data are stored at the cost of increased traversal times when searching the database. This tradeoff is similar to the one we encountered when working with delimited files like CSVs and with JSON files. When loading or dumping data between a file and a database, CSVs are a good match for tables in a relational database, whereas JSONs are more aligned with NoSQL databases.

The are many examples of NoSQL databases, each with different use cases, and most of which can be accessed with Python.

One flexible and popular example is MongoDB. MongoDB is a document-oriented database, where a “document” encapsulates and encodes data in a standard format. In the case of MongoDB, that format is JSON-like. Like the relational databases mentioned above, MongoDB has a client for querying it directly, as well as a connector for querying from within Python. These queries are constructed usingMongoDB’s query syntax.

The Python connector to MongoDB is PyMongo.

```python
from pymongo import MongoClient
# By default a Mongo db running locally is accessible via port 27017
client = MongoClient('localhost', 27017)
db = client['database_name']

# Within a db, documents are grouped into "collections" -- roughly equivalent
# to tables in a relational db.
coll = db['collection_name']

# Return all the documents within the collection
docs = coll.find()
```



#### Web scraping and APIs

Automating the process of downloading content from websites is known as web scraping.

** IMPORTANT **
> Web scraping can be done in legitimate ways, but just as easily web scraping tools do not stop you from violating a websites terms of service. If a website encourages the sharing of their data then they will create a specific API endpoint that you will use. More often than not the API will require to have an identifying key.

Various tools in Python are available for accessing and parsing webpage data.Requests is a user-friendly library for downloading web pages. It can also be used to retrieve files that are exposed through a URL. For a webpage the data returned from a call using Requests is the HyperText Markup Language (HTML) code that instructs a client such as a web browser how to display a page. This HTML code will often (but not always) contain the data you want to collect from the particular webpage.

Modern webpages tend to have a great deal of information in their HTML beyond what is shown to the user, so parsing through it all to collect the relevant data can be a daunting task. Fortunately, if a page is readable in your browser, then its HTML must have a coherent structure. Beautiful Soup is a Python library that provides tools for walking through that structure in a systematic and repeatable way. Thus, in the context of web scraping Beautiful Soup can be used to extract the relevant data from the soup of all the other information contained in an HTML file.

Many websites’ contents are dynamically rendered in such a way that the information displayed on a page never makes it directly into the page’s HTML. In such cases it may not be possible to download the data of interest with a tool like Requests. One option in this scenario is to move to a tool for browser automation, such as Selenium. Selenium’s Python interface is described here.

Another tool, specifically designed for web scraping in Python, is Scrapy.

Depending on your website of interest you may have to try several of these tools to successfully collect the relevant data in a scalable way. But a general rule of thumb is that if you can see what you want to collect in your browser, the the website sent it to you, so it should be retrievable.



#### Streaming data

In the modern landscape of business data streams are becoming more common. A data stream is a sequence of digitally encoded signals. Data can be streamed for many purposes including storage and further processing (like modeling). Data streams become important when the data of a project or company becomes mature and the AI pipeline is connected to it. As we move into the portions of the AI enterprise workflow that focus on models in production we will be using Apache Spark’s streaming to connect deployed models with streaming data. Data collected from sensors or devices connected via the internet of things are oftent setup to produce streaming data. We will work specifically with these types of data in module 5.


#### Apache Hadoop File Share (HDFS)

Apache Hadoop File Share (HDFS) is the core of Apache Hadoop , an open source system that is designed to use arrays of commodity hardware to store and manage very large datasets.

HDFS is the storage component of the system. Large datasets are divided into blocks, and those blocks are distributed and stored across the nodes in an HDFS cluster. Any code that is created to analyze the datasets stored in a Hadoop cluster is executed locally for each block of data, and in parallel. This parallel analysis of data blocks means that Hadoop can process very large data sets rapidly.

The Hadoop framework itself is written mostly in Java. However, any language, including Python, may be used to analyze the data stored in a Hadoop cluster. The Apache Foundation provides a number of other packages that may be installed alongside Hadoop to add additional relational database functionality and improve scalability.

IMPORTANT: Apache Hadoop is a de facto standard in many large enterprises today. It is often used with Apache Spark and a NoSQL database engine to provide data storage and management of data pipelines used by machine learning models.

#### Other sources of data formats

|Format | Description |
|:--|:--|
|HDF5 |   There is a is a hierarchical format HDF5 used to store complex scientific data. The format is useful for storing and sharing large amounts of data.
|NumPy’s \*.npy and \*.nzp formats | NumPy has its own binary format (NPY) and the NPZ format is an extension of it that allows multiple arrays and compression.



## Summary

In this module you should have learned:

- Stakeholder or domain expert opinion, feasibility and impact are three of the most important factors when prioritizing business opportunities
- The practice of articulating a business opportunity, with the data in mind, as a testable hypothesis helps keep the overall project linked to the business needs
- The notion of degree of belief is important when making statements both in science and in business. No statement has 100% degree of belief, it is some percentage of 100% that is a reflection of accumulated evidence
- The scientific method helps formalize a process for rationalizing business decisions through experimentation and evidence