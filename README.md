# SQL Data Analytics Project

This project demonstrates an end-to-end SQL data analytics workflow using a retail sales dataset. It covers database setup, data cleaning, dimensional modeling, and analytical queries designed to extract business insights from raw transactional data. The main aim is to generate two final reports, customers report and products report, for further visualization in reporting tools.

## Project Overview

The project simulates a real analytics environment by:

* Creating a SQL Server database using Docker.
* Importing raw CSV files into fact and dimension tables.
* Building a star schema for structured analysis.
* Writing analytical SQL queries to explore trends, segmentation, product performance, and customer behavior.

## Skills Demonstrated

* Data modeling (fact and dimension tables)
* Data cleaning and transformation
* Window functions (running totals, lag)
* Aggregation and segmentation (CASE WHEN, grouping, categorization)
* Trend and proportional analysis
* Docker container setup for SQL Server
* Azure Data Studio for querying and data visualization

## Key Insights Generated

* Monthly and yearly sales trends
* Customer purchase patterns
* Product performance comparisons
* Part-to-whole and segmentation analysis
* Running totals and cumulative growth metrics

## Technologies Used

* SQL Server 2022 (Docker)
* Azure Data Studio
* GitHub
* CSV datasets (raw retail sales data)

## How to Run

1. Start SQL Server in Docker with a mounted data folder.
2. Connect using Azure Data Studio.
3. Create the database and load CSV files using BULK INSERT or copy-paste the init-database script.
4. Run the analytical SQL scripts in the project folder.

## Repository Structure

```
/datasets        Raw CSV data files  
/sql-scripts     Database creation, modeling, and analysis scripts  
```

## Purpose

This project demonstrates practical, SQL analytics skills—including ETL, modeling, and business-focused analysis.

