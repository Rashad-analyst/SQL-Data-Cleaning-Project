# SQL Data Cleaning Project – Layoffs Dataset

This project focuses on cleaning a raw layoffs dataset using SQL.

## Steps Performed:
- Removed duplicates using ROW_NUMBER() and CTE.
- Standardized text fields (company, industry, country).
- Fixed inconsistent date formats using STR_TO_DATE.
- Handled NULL and blank values.
- Identified missing industries and filled them using self-join.
- Removed invalid rows.
- Exported the clean dataset to CSV.

## Tools:
MySQL Workbench

## Files included:
- 01_data_cleaning.sql  → full SQL cleaning script
- cleaned_layoffs.csv   → final cleaned dataset
