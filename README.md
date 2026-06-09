# Netflix Data Cleaning & Analysis

## Project Overview

This project focuses on building an end-to-end ELT (Extract, Load, Transform) workflow using SQL Server and Python to clean, transform, and analyze Netflix's Movies & TV Shows dataset. The goal was to improve data quality, create a structured analytical model, and generate business insights through advanced SQL analysis.

## Objectives

* Clean and transform raw Netflix content data.
* Standardize and improve data quality for analysis.
* Create a normalized database structure for efficient querying.
* Perform exploratory and business-focused analysis using SQL.
* Extract actionable insights from Movies and TV Shows data.

## Tools & Technologies

* SQL Server
* Python (Pandas)
* SQL
* Git & GitHub
* Excel (Data Validation)

## Dataset

The dataset contains information about Netflix Movies and TV Shows, including:

* Title
* Content Type
* Director
* Cast
* Country
* Date Added
* Release Year
* Rating
* Duration
* Genre (Listed In)
* Description

## ELT Workflow

### 1. Extract

* Imported raw Netflix dataset into SQL Server.
* Validated schema and data types.

### 2. Load

* Loaded source data into staging tables for processing.

### 3. Transform

Performed extensive data cleaning and transformation:

* Removed duplicate records.
* Handled foreign and special characters.
* Standardized date formats.
* Populated missing values where applicable.
* Cleaned inconsistent text fields.
* Split multi-value columns into normalized tables.

Created normalized dimension tables for:

* Genre
* Director
* Country

This improved data integrity and enabled more efficient analysis.

## Data Modeling

Implemented a normalized relational structure to reduce redundancy and support scalable analytical queries.

### Dimension Tables

* dim_genre
* dim_director
* dim_country

### Fact Table

* netflix_titles

## SQL Analysis

Performed advanced SQL analysis using:

* Common Table Expressions (CTEs)
* Window Functions
* String Functions
* Aggregate Functions
* Joins and Subqueries

## Key Business Questions Answered

### Content Distribution

* What is the ratio of Movies vs TV Shows on Netflix?

### Country Analysis

* Which countries produce the most Netflix content?
* Which countries contribute the most Comedy titles?

### Genre Analysis

* What are the most popular genres?
* Which genres are growing over time?

### Director Analysis

* Which directors have produced content across multiple genres?
* Who are the most prolific directors on Netflix?

### Time-Based Analysis

* How has content addition changed over the years?
* Which years saw the highest content growth?

## Key Insights

* Identified the top countries contributing Comedy content.
* Discovered directors working across multiple genres.
* Revealed content distribution trends across Movies and TV Shows.
* Uncovered patterns in Netflix's content expansion over time.
* Improved analytical performance through normalization and optimized SQL queries.

## Project Structure

```text
Netflix-Data-Cleaning-Analysis/
│
├── Dataset/
│   └── netflix_titles.csv
│
├── SQL/
│   ├── data_cleaning.sql
│   ├── data_transformation.sql
│   ├── data_modeling.sql
│   └── business_analysis.sql
│
├── Python/
│   └── preprocessing.ipynb
│
├── Documentation/
│   └── project_report.pdf
│
└── README.md
```

## Skills Demonstrated

* SQL Querying
* Data Cleaning
* Data Transformation
* Data Modeling
* Database Normalization
* Exploratory Data Analysis (EDA)
* ELT Workflow Development
* Business Insight Generation
* Query Optimization

## Outcomes

This project demonstrates the complete lifecycle of a data analytics workflow, from raw data preparation to business insight generation. It highlights practical experience in SQL Server, Python, data modeling, and analytical problem-solving using a real-world entertainment dataset.
