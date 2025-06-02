# Task-1-Data-Cleaning-and-Preprocessing
Cleaning and preparing a raw dataset (with nulls, duplicates, inconsistent formats).
# Summary of Data Cleaning

- Loaded `sales_data_sample.csv` with Pandas
- Removed missing values using dropna()
- Eliminated duplicate rows
- Standardized text in 'status' and 'country' columns
- Parsed date columns to datetime format
- Renamed columns to lowercase with underscores
- Converted 'quantityordered' to integer
- Final cleaned data saved as `cleaned_sales_data.csv`

Summary of Changes:
- Removed 127 duplicate rows
- Filled 95 missing values using forward fill
- Standardized gender values to lowercase
- Reformatted date columns to dd-mm-yyyy format
- Renamed all column headers to snake_case
- Converted 'age' to integer data type
