# Data Cleaning Project – Club Member Dataset (PostgreSQL)
(Note - This project uses a publicly available dataset originally published by [iweld](https://github.com/iweld/data_cleaning). All SQL cleaning logic and documentation were developed independently.)


## Objective
Design and implement a structured SQL-based data cleaning pipeline using PostgreSQL to transform raw club member data into a validated, analysis-ready format.

## 🛠️ Tools & Technologies
- PostgreSQL (pgAdmin 4)
- SQL string, regex, and conditional functions
- Optional: Excel (for raw vs cleaned data comparison)

## Problem Statement
Raw member data often contains inconsistencies such as extra spaces, invalid characters, null values, and formatting issues. These errors can distort analysis and reporting. This project focuses on cleaning and standardizing such data using SQL transformations.

## Cleaning Logic
- ✅ Dropped existing tables if present to avoid duplication
- ✅ Created structured tables with defined columns and primary keys
- ✅ Trimmed whitespace and converted text to lowercase
- ✅ Removed special characters using regex
- ✅ Handled null and blank values with conditional logic
- ✅ Normalized categorical fields like marital status
- ✅ Standardized formats for age, email, and phone numbers
- ✅ Split address fields and corrected date anomalies

## Outcome
- Produced a clean, validated dataset ready for downstream processing
- Ensured high data quality for reliable reporting and visualization
- Demonstrated proficiency in SQL-based ETL and transformation logic

## Repository Highlights
- `data_cleaning.sql`: SQL script containing all transformation steps
- `README.md`: Project documentation and summary

## Skills Demonstrated
- SQL data profiling and transformation
- Regex and conditional logic in PostgreSQL
- ETL pipeline design for relational databases
