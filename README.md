# Data Modeling with Apache Cassandra

## **Project Overview:**

In this project, I'll apply what I've learned on data modeling with Apache Cassandra and complete an ETL pipeline using Python. I have modeled my data by creating tables in Apache Cassandra to run queries. I was provided with part of the ETL pipeline that transfers data from a set of CSV files within a directory to create a streamlined CSV file to model and insert data into Apache Cassandra tables.

### **Purpose: What songs users are listening to?**

      Example: A startup called Sparkify wants to analyze the data they've been collecting on songs and user activity on their new music streaming app. The analytics team is particularly interested in understanding what songs users are listening to.

### **Issue: Data to be queried resides in CSV files**

       Currently, there is no easy way to query the data to generate the results, since the data reside in a directory of CSV files on user activity on the app.

#### Datasets:

      For this project, i'll be working with one dataset: event_data. The directory of CSV files are partitioned by date. Here are examples of filepaths to two files in the dataset:
      event_data/2018-11-08-events.csv
      event_data/2018-11-09-events.csv
