# Data-Assignment

**Overview**
This repository contains solutions for several data-related problems, including data modeling, SQL queries, machine learning, and time series analysis. The problems address different aspects of data manipulation, analysis, and prediction using various tools and techniques.

***Contents
Data Modeling
SQL Queries
Machine Learning
Time Series Analysis*

# **Problem 1: Data Modeling**
Overview: 

Design a database for an e-commerce platform with the following requirements:

Multiple types of products
Product variants
Dynamic pricing
Customer details

Files:

*Data_Modelling.ipynb*: Jupyter notebook containing the data model design and random data generation code.

*ERD.drawio.png*: Entity-Relationship Diagram for the database.

# **Problem 2: SQL Queries**
Overview:

Write SQL queries for the following:

Retrieve top 5 customers by average order amount in the last 6 months.
List customers with lower order values this year compared to the previous year.
Create a table showing cumulative purchases by customer and product category.
Retrieve top 5 selling products, including variant sales.

Files: 
*Problem 2 SQL.txt* : Text file containing SQL queries for the tasks.


# **Problem 3: ETL**

Overview:

Transform nested JSON data related to orchestras, their concerts, works, and artists into a normalized format for easier analysis.

Files:

**Problem 3 ETL.ipynb**: Jupyter notebook performing data transformations and normalization.

*program.csv, work.csv, soloists.csv, concerts.csv*: Output CSV files containing the transformed data.

*ERD.png*: Entity-Relationship Diagram showing relationships between the normalized data tables.
Problem 3 ETL SQL.txt: SQL file for the ETL process.

Instructions:

Load and transform the nested JSON data into normalized tables.
Generate an ERD to show relationships between the entities.
Implement the transformation using Python and SQL.

# **Problem 4: Machine Learning**
Overview:

Analyze anonymized loan application data to predict credit risk using machine learning models.

Files:

*Machine_Learning_Problem_Task_1(EDA).ipynb*: Exploratory Data Analysis (EDA) and insights.

*Machine_Learning_Problem_Task_2(Model).ipynb*: Machine learning models for predicting credit risk.

Instructions
Perform EDA and segment customers based on risk.
Develop at least two ML models to predict credit risk.
Explain feature selection, handle missing values, and evaluate models using confusion matrices.

# **Problem 5: Time Series Analysi**
Overview:

Analyze work done by AGI bots, which can multi-task. Determine continuous work periods and aggregate activities.

Files:

*Time_Series_problem.ipynb*: Jupyter notebook performing data transformations and aggregating activities.

*Problem 5 Time Series SQL Queries.txt*: SQL queries for time series analysis.

Instructions
Transform data to identify continuous work periods.
Aggregate activities during these periods using Python and SQL.
