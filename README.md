**LAYOFFS DATA SET PROJECT OVERVIEW**

This project focuses on data cleaning, preparation, and exploratory data analysis (EDA) using MySQL on a company layoffs dataset.

The project starts by inspecting the original layoffs table and creating staging tables to safely perform the cleaning process without modifying the original dataset.

**Data Cleaning & Preparation**

The main data-cleaning tasks include:

Creating staging tables using CREATE TABLE ... LIKE
Copying the original data into a staging table
Identifying duplicate records using ROW_NUMBER()
Using PARTITION BY to detect records with matching values
Creating a second staging table containing a row_num column
Identifying duplicate records where row_num > 1
Removing duplicate records from the cleaned staging table
Inspecting individual company records
Standardising company names using TRIM()
Checking distinct company values before and after cleaning
Converting the date column into a usable date format
Preparing the cleaned dataset for exploratory analysis

**Exploratory Data Analysis**

After cleaning the dataset, SQL queries are used to explore layoff patterns, trends, and company-level performance.

The exploratory analysis includes:

Calculating maximum and minimum layoffs
Identifying companies with 100% of their workforce laid off
Comparing companies based on total employees laid off
Analysing total layoffs by company
Analysing total layoffs by industry
Comparing layoffs across different locations
Filtering and investigating specific locations
Analysing layoffs by year
Examining layoffs by company stage
Calculating average and total layoff percentages
Analysing monthly layoffs
Creating a rolling total of layoffs over time
Analysing total layoffs by company and year
Ranking companies by total layoffs for each year
Identifying the top five companies with the highest layoffs in each year using CTE, DENSE_RANK(), and window functions

The project demonstrates practical MySQL skills in data cleaning, duplicate detection, data transformation, exploratory analysis, aggregation, CTEs, date analysis, rolling totals, ranking, and window functions.

Overall, the analysis transforms a raw company layoffs dataset into a cleaner and more structured dataset that can be used to understand layoff trends across companies, industries, locations, stages, months, and years.

**ENTERPRISE DATA SET PROJECT OVERVIEW**

This project focuses on building and querying an Enterprise database using MySQL.

The database was designed to represent a simple business environment containing departments, employees, and projects. It demonstrates how relational databases can be structured using primary keys and foreign keys to establish relationships between tables.

The project includes:

Creating an Enterprise database
Creating and populating Departments, Employees, and Projects tables
Using primary keys to uniquely identify records
Using foreign keys to establish relationships between employees/projects and departments
Inserting sample business data
Retrieving and filtering records using SELECT and WHERE
Using comparison operators such as =, !=, <, >, >=, and BETWEEN
Using logical operators such as AND and OR
Filtering records with IN and NOT LIKE
Using wildcard searches with LIKE
Performing aggregate calculations using SUM(), AVG(), and COUNT()
Applying conditions to analyse employee salaries, department membership, and project budgets

The project demonstrates practical SQL database design, data manipulation, filtering, and basic business data analysis using MySQL.

**SCHOOL DATA SET PROJECT OVERVIEW**

This project focuses on SQL and MySQL database fundamentals, covering the creation, modification, and management of databases and tables.

The project includes practical exercises using different datasets such as school information, employee records, and customer information. It demonstrates the fundamental SQL commands required to create databases, define table structures, insert data, modify tables, and retrieve records.

Key SQL concepts covered include:

Creating and selecting databases using CREATE DATABASE and USE
Viewing available databases and tables using SHOW DATABASES and SHOW TABLES
Creating tables with different data types
Defining primary keys
Inserting single and multiple records
Retrieving data using SELECT
Adding new columns to an existing table using ALTER TABLE
Working with data types such as INT, VARCHAR, CHAR, and DATE
Managing structured information related to employees, students, and customers

This project provides practical experience with relational database creation, table design, data insertion, and basic data retrieval using MySQL.



