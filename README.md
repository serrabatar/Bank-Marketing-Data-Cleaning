# Bank Marketing Data Cleaning

## Project Overview
This project focuses on cleaning, transforming, and organizing bank marketing campaign data using Python and Pandas.

The dataset contains **41,188 records** with customer information, marketing campaign outcomes, and economic indicators.

This project was completed as part of the DataCamp practical project **Cleaning Bank Marketing Campaign Data**.

## Tools and Technologies
- Python
- Pandas
- NumPy
- Jupyter Notebook
- CSV Data Processing

## Data Cleaning Process

The original dataset was divided into three structured datasets:

**1. Client Data (`client.csv`)**
- Standardized job and education categories.
- Handled unknown education values.
- Converted credit default and mortgage indicators into Boolean values.

**2. Campaign Data (`campaign.csv`)**
- Organized customer contact and campaign information.
- Converted previous and current campaign outcomes into Boolean values.
- Created a standardized contact date column.

**3. Economic Data (`economics.csv`)**
- Extracted consumer price index information.
- Organized three-month Euribor interest rate data.

## Project Output

| Dataset | Records | Columns |
|---|---:|---:|
| client.csv | 41,188 | 7 |
| campaign.csv | 41,188 | 7 |
| economics.csv | 41,188 | 3 |

All three datasets were exported as CSV files without DataFrame indexes.

## Skills Demonstrated
- Data Cleaning and Preprocessing
- Data Transformation
- Data Type Conversion
- DataFrame Manipulation
- Data Quality Checks
- Data Export

## Project Source
DataCamp — Cleaning Bank Marketing Campaign Data

https://www.datacamp.com/projects/1613
