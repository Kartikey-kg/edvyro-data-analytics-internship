# Data Quality and Exploratory Analysis

## Overview

This project focuses on auditing and cleaning a synthetic customer churn dataset and performing initial exploratory analysis.

## Objectives

- Profile columns and data types
- Identify missing values and duplicates
- Check for impossible and extreme values
- Document data-cleaning decisions
- Validate the cleaned dataset
- Calculate summary statistics
- Explore meaningful customer churn patterns

## Tools Used

- Python
- Pandas
- NumPy
- Matplotlib
- Jupyter Notebook

## Key Findings

The dataset contains 15 customer records.

The quality audit found no missing values, duplicate customer IDs, invalid categories, impossible numeric values, or IQR-based outliers.

The overall observed churn rate was 46.7%.

The analysis identified month-to-month customers with 3 or more support tickets as the first audience to consider for retention outreach.

Because the dataset is small and synthetic, these findings are descriptive and should not be interpreted as proof of causation.

## Files

- `Customer_Churn_Analysis.ipynb` — analysis notebook
- `customer_churn_sample.csv` — original dataset
- `customer_churn_cleaned.csv` — analysis-ready dataset
- `customer_churn_data_dictionary.csv` — data dictionary
- `data_quality_summary.md` — data-quality report
