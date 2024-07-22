# DATA CLEANING 

### Project Overview

This project focuses on cleaning the data using SQL. We remove duplicates, standardize the data, look for null or missing values and remove any data that we don't need.

### Data Source 

Layoffs Data : The primary dataset used for this analysis is the "layoffs.csv" containing information about layoffs in various companies. 

### Data Cleaning 

Our Data Cleaning Process Had 4 steps which are as follows : 

- Remove Duplicates
- Standardize the Data
- Null values or blank values
- Remove Any Columns

### Process

- Removed the duplicates from the table by identifying them by giving them a ROW_NUMBER() partitioning by all the other columns and deleted them from the table.
- Standardized names of some columns and industries
- Also changed the date column using the STR_TO_DATE() function.
- Changed blank values to nulls and removed rows that had no data. 
- Finally removed the ROW_NUMBER() that we had added to the table.
