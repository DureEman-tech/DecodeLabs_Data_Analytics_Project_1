# DecodeLabs Data Analytics Project 1

## Data Cleaning & Preparation

This project was completed as part of my Data Analytics Internship at DecodeLabs.

The main objective of this project was to clean and prepare an e-commerce order dataset for further data analysis.

## Dataset Overview

- Total Rows: 1,200
- Total Columns: 14
- Data Type: E-commerce order data
- Tools: Python, Pandas, Google Colab

## Data Cleaning Performed

The following data-cleaning tasks were performed:

- Checked the dataset structure and data types
- Checked for missing values
- Handled missing values in the `CouponCode` column
- Checked for duplicate rows
- Checked for duplicate `OrderID` values
- Validated date values
- Checked numeric columns for invalid values
- Verified `TotalPrice` using Quantity × UnitPrice
- Reviewed categorical/text values
- Performed final data validation

## Missing Values

Initially, the `CouponCode` column contained 309 missing values.

These were replaced with:

`No Coupon`

After cleaning:

- Missing values: **0**

## Final Validation

| Check | Result |
|---|---:|
| Total Rows | 1,200 |
| Total Columns | 14 |
| Missing Values | 0 |
| Duplicate Rows | 0 |
| Duplicate OrderIDs | 0 |
| Invalid Dates | 0 |

## Files Included

- `DecodeLabs_Data_Analytics_Project_1.ipynb` — Python/Colab notebook
- `cleaned_dataset.xlsx` — Cleaned dataset
- `DecodeLabs_Data_Analytics_Project_1_Report.docx` — Project report

## Key Learning

This project helped me understand the importance of data cleaning and validation before performing data analysis. Clean and reliable data is essential for producing accurate insights.

## Tools Used

- Python
- Pandas
- Google Colab
- Microsoft Excel
- GitHub
