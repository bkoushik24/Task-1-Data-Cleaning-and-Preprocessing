# Task-1-Data-Cleaning-and-Preprocessing
Data cleaning and preprocessing of the Customer Personality Analysis dataset using Python (Pandas). Includes handling missing values, removing duplicates, standardizing formats, correcting data types, and creating derived features for analysis.
📌 Overview
This project is part of my Data Analyst Internship Task 1, focusing on data cleaning and preprocessing of the Customer Personality Analysis dataset.
The aim is to transform raw, messy data into a clean, structured dataset ready for analysis or modeling.

🎯 Objectives
1.Identify and handle missing values
2.Remove duplicate records
3.Standardize text and categorical formats
4.Convert date columns to a consistent format
5.Rename columns for uniform naming conventions
6.Correct data types
7.Create derived features for richer analysis

🔧 Tools & Libraries
1.Python
2.Pandas for data manipulation
3.NumPy for numeric operations
4.Datetime for date conversions

🛠 Steps Performed
1.Load & inspect the raw tab-separated dataset
2.Rename columns to lowercase with underscores
3.Convert Dt_Customer to datetime
4.Compute Age from Year_Birth and Dt_Customer
5.Standardize Education and Marital Status values
6.Combine Kidhome and Teenhome → Children column
7.Calculate Total Spending across product categories
8.Derive Family Size from marital status & children
9.Convert Income to numeric and impute missing values with median
10.Remove duplicates
11.Ensure correct data types for all columns

📊 Key Results
1.Original Shape: 2240 rows × 29 columns
2.Final Shape: 2240 rows × 34 columns (added new features)
3.Missing Income values (24) → filled with median: 51,381.5
4.No duplicates after cleaning
5.All text standardized and numeric columns fixed
