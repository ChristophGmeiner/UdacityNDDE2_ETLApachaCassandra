# ETL process for Creating Sparkify Data Model in Apache Cassandra
 
This is my second project for the Udacity Nanodegree of Data Engineering. It is about an etl process (Apache Cassandra based) for Sparkify.

Sparkify is a simulated (not-real) online music streaming service.

This Git repository shows how to script an etl process for loading data from csv raw data to a Apacha Cassandra Database and for creating tables to fulfill the query requirements of the project template (see in the Jupyter Notebook below).

This is done using Python, mainly with the modules pandas and cassandra.

## Purpose of the Database sparkifydb

The sparkifydb database is Apache Cassandra based and is about storing information about songs and listening behaviour of the users

The analytical goal of this database to get all kinds of individual insights into the user beahviour. Please consider here, that I work here only with a few data samples. Apacha Cassandra is made for big data, therefore to get individual insights into user behaviour Apacha Cassandra is much more suitable than a relational database.

## Files and Scripts

### Project_1B_ Project_Template
This is the main notebook, which contains the whole etl pipeline

First the data is transfered from csv to a pandas dataframe for analysis reasons, before further importing the data into the database.

Then 3 tables are created and filled (based on needed queries, these arer defined in the notebook).

Afterwards test queries are ran, to check whether the queries run succesfull.

