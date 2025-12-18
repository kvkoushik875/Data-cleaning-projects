# Project 1: Customer Dataset – Data Cleaning & Preprocessing

# Project Description
This project focuses on cleaning and preprocessing a simulated e-commerce customer dataset containing real-world data quality issues such as missing customer IDs, duplicate records, inconsistent text formatting, and invalid demographic values. The goal is to transform raw customer data into a structured, analysis-ready format suitable for business analytics and machine learning applications.

# Sample Dataset
- <a href="https://github.com/kvkoushik875/Data-cleaning-projects/blob/main/customers-100.csv">Customer Dataset</a>

# Data Issues Addressed
- Duplicate customer records across multiple attributes
- Missing customer IDs and contact details
- Inconsistent name capitalization and whitespace
- Mixed date formats in registration dates
- Invalid or out-of-range age values
- Region/category inconsistencies

# Cleaning & Processing Steps
- Loaded raw data using Pandas with initial sanity checks
- Removed exact and partial duplicate records
- Dropped irrelevant columns (temporary IDs, notes)
- Handled missing values using deletion and statistical imputation
- Converted data types (dates, numeric fields)
- Standardized text fields (lowercase, trimmed)
- Validated final dataset using assertions

# Outcome
- A clean, deduplicated, and standardized customer dataset ready for downstream analysis such as customer segmentation, churn prediction, and reporting.
- <a  href="https://github.com/kvkoushik875/Data-cleaning-projects/blob/main/cleaned_customers_data.csv">Cleaned_customers_data</a>



# Project 2: People Dataset – Data Cleaning & Preprocessing

# Project Description
- This project involves cleaning a demographic people dataset containing inconsistent job titles, malformed phone numbers, mixed date formats, and missing personal attributes. The objective is to ensure data consistency and reliability for analytics, HR reporting, and data science workflows.

# Sample Dataset
- <a href="https://github.com/kvkoushik875/Data-cleaning-projects/blob/main/people-100.csv">People Dataset</a>

# Data Issues Addressed
-Mixed date formats (DD-MM-YYYY, MM/DD/YYYY, text dates)
-Inconsistent job titles (e.g., “SWE”, “Software Eng”, “software engineer”)
-Malformed or incomplete phone numbers
-Missing demographic fields (age, gender, occupation)
-Duplicate individual records

# Cleaning & Processing Steps
- Parsed and standardized date columns
- Normalized job titles using mapping dictionaries
- Cleaned phone numbers using regex operations
- Handled missing values using mode/median imputation
- Removed duplicate person records
- Ensured correct data types for numerical and categorical fields

# Outcome
- A well-structured and validated people dataset suitable for demographic analysis, workforce analytics, and machine learning models.
- <a href="https://github.com/kvkoushik875/Data-cleaning-projects/blob/main/cleaned_people_data.csv">Cleaned People Dataset</a>

