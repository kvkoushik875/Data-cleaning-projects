# Project 1: Customer Dataset – Data Cleaning & Preprocessing

## Project Description
This project focuses on cleaning and preprocessing a simulated e-commerce customer dataset containing real-world data quality issues such as missing customer IDs, duplicate records, inconsistent text formatting, and invalid demographic values. The goal is to transform raw customer data into a structured, analysis-ready format suitable for business analytics and machine learning applications.

## Sample Dataset
- <a href="https://github.com/kvkoushik875/Data-cleaning-projects/blob/main/customers-100.csv">Customer Dataset</a>

## Data Issues Addressed
- Duplicate customer records across multiple attributes
- Missing customer IDs and contact details
- Inconsistent name capitalization and whitespace
- Mixed date formats in registration dates
- Invalid or out-of-range age values
- Region/category inconsistencies

## Cleaning & Processing Steps
- Loaded raw data using Pandas with initial sanity checks
- Removed exact and partial duplicate records
- Dropped irrelevant columns (temporary IDs, notes)
- Handled missing values using deletion and statistical imputation
- Converted data types (dates, numeric fields)
- Standardized text fields (lowercase, trimmed)
- Validated final dataset using assertions

## Outcome
- A clean, deduplicated, and standardized customer dataset ready for downstream analysis such as customer segmentation, churn prediction, and reporting.
- <a  href="https://github.com/kvkoushik875/Data-cleaning-projects/blob/main/cleaned_customers_data.csv">Cleaned_customers_data</a>




# Project 2: People Dataset – Data Cleaning & Preprocessing

## Project Description
- This project involves cleaning a demographic people dataset containing inconsistent job titles, malformed phone numbers, mixed date formats, and missing personal attributes. The objective is to ensure data consistency and reliability for analytics, HR reporting, and data science workflows.

## Sample Dataset
- <a href="https://github.com/kvkoushik875/Data-cleaning-projects/blob/main/people-100.csv">People Dataset</a>

## Data Issues Addressed
-Mixed date formats (DD-MM-YYYY, MM/DD/YYYY, text dates)
-Inconsistent job titles (e.g., “SWE”, “Software Eng”, “software engineer”)
-Malformed or incomplete phone numbers
-Missing demographic fields (age, gender, occupation)
-Duplicate individual records

## Cleaning & Processing Steps
- Parsed and standardized date columns
- Normalized job titles using mapping dictionaries
- Cleaned phone numbers using regex operations
- Handled missing values using mode/median imputation
- Removed duplicate person records
- Ensured correct data types for numerical and categorical fields

## Outcome
- A well-structured and validated people dataset suitable for demographic analysis, workforce analytics, and machine learning models.
- <a href="https://github.com/kvkoushik875/Data-cleaning-projects/blob/main/cleaned_people_data.csv">Cleaned People Dataset</a>




# Project 3: Organization Dataset – Data Cleaning & Preprocessing

## Project Description
- This project focuses on cleaning organizational data containing inconsistent industry labels, missing employee counts, website formatting issues, and duplicate company records. The dataset simulates real corporate registries used for market research and business intelligence.

## Sample Dataset
- <a href="https://github.com/kvkoushik875/Data-cleaning-projects/blob/main/organizations-100.csv">Organization Dataset</a>

## Data Issues Addressed
- Inconsistent industry categories and naming conventions
- Missing or invalid employee count values
- Incorrect website URL formats
- Duplicate organization records
- Text inconsistencies in company names

## Cleaning & Processing Steps
- Removed duplicate organizations using multi-column checks
- Standardized industry categories using mapping rules
- Imputed missing employee counts using median values
- Cleaned and validated website URLs
- Normalized text formatting for company names
- Reordered and renamed columns for clarity

## Outcome
- A clean and standardized organization dataset ready for business analytics, market segmentation, and company profiling.
- <a href="https://github.com/kvkoushik875/Data-cleaning-projects/blob/main/cleaned_organizations_data.csv">Cleaned Organization Dataset</a>

# Project 4: Retail Sales Data Cleaning Project
## Project Description
- This project involves cleaning a retail sales transactions dataset containing date parsing issues, extreme outliers in sales and quantity, missing values, and inconsistent store and item identifiers. The goal is to produce a reliable dataset suitable for time-series analysis, demand forecasting, and business reporting.

## Sample Dataset
- <a href="https://github.com/kvkoushik875/Data-cleaning-projects/blob/main/train.csv">Retail Sales</a>

## Data Challenges Addressed
- Mixed and invalid date formats in transaction timestamps
- Extreme outliers in sales amount and item quantity
- Missing values in sales and quantity fields
- Inconsistent store IDs and item IDs
- Duplicate sales transactions

## Key Cleaning Techniques Applied
- Parsed and standardized date columns using pd.to_datetime()
- Detected and filtered outliers using logical thresholds and statistical rules
- Handled missing values using median and mode imputation
- Standardized categorical identifiers (store/item IDs)
- Removed duplicate transaction records
- Performed data validation using assertions


## Outcome
- A clean, consistent retail sales dataset ready for trend analysis, sales forecasting, and performance analytics.
- <a href="https://github.com/kvkoushik875/Data-cleaning-projects/blob/main/cleaned_retail_sales_data.csv">Cleaned Retail Sales</a>

# Project 5: Spotify Streaming History Data Cleaning Project

## Project Description
- This project focuses on cleaning Spotify streaming history data containing timestamp errors, missing track identifiers, inconsistent artist names, and duplicate listening records. The objective is to prepare user listening data for behavioral analysis and recommendation-based insights.

## Sample Dataset
- <a href="https://github.com/kvkoushik875/Data-cleaning-projects/blob/main/spotify_data_dictionary.csv">Spotify_data_dictionary</a>
- <a href="https://github.com/kvkoushik875/Data-cleaning-projects/blob/main/spotify_history.csv">Spotify_data_history</a>
## Data Challenges Addressed
- Invalid or missing timestamp values
- Missing track IDs
- Inconsistent artist and track name formatting
- Duplicate streaming events
- Mixed text casing and whitespace issues

## Key Cleaning Techniques Applied
- Converted timestamp columns into standardized datetime formats
- Removed records missing critical fields such as artist name and track name
- Normalized artist and track names (lowercase, trimming whitespace)
- Handled missing track IDs using conditional logic
- Removed duplicate listening events
- Applied quality checks to ensure data consistency

## Outcome
- A cleaned and validated Spotify streaming dataset suitable for listening behavior analysis, trend detection, and recommendation system development.
- <a href="https://github.com/kvkoushik875/Data-cleaning-projects/blob/main/cleaned_spotify_streaming_history.csv">Cleaned_Spotify_Streaming</a>


# Project 6:  Data Science Job Postings – Advanced Data Cleaning Project
## Description
- This project cleans Glassdoor job postings data containing salary outliers, unstructured job descriptions, inconsistent job titles, and mixed location formats. The dataset simulates real-world labor market data used for salary analysis and workforce analytics.

## Sample Data
<a href="https://github.com/kvkoushik875/Data-cleaning-projects/blob/main/Cleaned_DS_Jobs.csv">Cleaned DS Job</a>
<a href="https://github.com/kvkoushik875/Data-cleaning-projects/blob/main/Uncleaned_DS_jobs.csv">Uncleaned DS Job</a>

## Data Challenges Addressed
-Extreme salary outliers
- Missing or inconsistent salary ranges
- Unstructured textual job descriptions
- Inconsistent job titles and location formats
- Duplicate job postings

## Advanced Techniques Applied
- Salary outlier detection using threshold-based logic
- Job title and location standardization
- Cleaning and preprocessing unstructured text fields
- Handling missing salary values
- Data consistency checks and validation

## Outcome
- A structured and cleaned job postings dataset ready for job market analysis, salary prediction models, and NLP-based insights.
- <a href="https://github.com/kvkoushik875/Data-cleaning-projects/blob/main/cleaned_ds_job_postings.csv">Cleaned DS Job Posting</a>

# Project 7: NYC Taxi Trips – Large-Scale Data Cleaning Project
##  Description
- This project involves cleaning and preprocessing large-scale NYC taxi trip data containing millions of records with GPS coordinate errors, fare discrepancies, invalid passenger counts, and missing timestamps. Due to the dataset’s size, chunk-based processing is used to ensure memory efficiency and scalability.

## Sample Dataset
<a href="https://github.com/kvkoushik875/Data-cleaning-projects/blob/main/taxi_zone_lookup.csv">Taxi Dataset</a>

## Data Challenges Addressed
- Invalid GPS coordinates outside NYC boundaries
- Incorrect passenger counts (zero or unrealistic values)
- Fare and trip distance anomalies
- Missing or malformed datetime values
- Extremely large dataset size requiring optimized processing

## Advanced Techniques Applied
- Chunk-wise data processing using pd.read_csv(chunksize=…)
- Geographic boundary validation for latitude and longitude
- Logical filtering of passenger count, fare amount, and trip distance
- Datetime parsing with error coercion
- Memory-efficient writing of cleaned data to disk
- Data quality validation using assertions

## Outcome
- A scalable, high-quality taxi trip dataset suitable for urban mobility analytics, demand forecasting, and transportation modeling.
- <a href="https://github.com/kvkoushik875/Data-cleaning-projects/blob/main/cleaned_sample_nyc_taxi_trips.csv">Cleaned Taxi Dataset</a>

