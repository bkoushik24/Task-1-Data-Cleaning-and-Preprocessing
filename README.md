# Task-1-Data-Cleaning-and-Preprocessing
📌 Overview
This project is part of my Data Analyst Internship Task 1, focusing on data cleaning and preprocessing of the Customer Personality Analysis dataset.
The aim is to transform raw, messy data into a clean, structured dataset ready for analysis or modeling.

🎯 Objectives
Identify and handle missing values
Remove duplicate records
Standardize text and categorical formats
Convert date columns to a consistent format
Rename columns for uniform naming conventions
Correct data types
Create derived features for richer analysis

🔧 Tools & Libraries
Python
Pandas for data manipulation
NumPy for numeric operations
Datetime for date conversions

🛠 Steps Performed
Load & inspect the raw tab-separated dataset
Rename columns to lowercase with underscores
Convert Dt_Customer to datetime
Compute Age from Year_Birth and Dt_Customer
Standardize Education and Marital Status values
Combine Kidhome and Teenhome → Children column
Calculate Total Spending across product categories
Derive Family Size from marital status & children
Convert Income to numeric and impute missing values with median
Remove duplicates
Ensure correct data types for all columns

📊 Key Results
Original Shape: 2240 rows × 29 columns
Final Shape: 2240 rows × 34 columns (added new features)
Missing Income values (24) → filled with median: 51,381.5
No duplicates after cleaning
All text standardized and numeric columns fixed
