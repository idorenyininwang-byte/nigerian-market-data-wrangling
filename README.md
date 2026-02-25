
# Nigerian Market Data Wrangling Assignment

**Name** Idorenyin Inwang  
**Assignment:** "Data Wrangling Assignment"  
**Date:** February 25, 2026  

## Project Overview
This repository contains the data cleaning and wrangling work on two datasets:
- nigerian_market_transactions_assignment.csv  
- nigerian_market_prices_assignment.csv  

Goal: Prepare the data for building a forecasting tool for the Nigerian market.

## Files Included
- **Idorenyin_Nigerian_Market_Data_Wrangling.ipynb**  
  Full Jupyter notebook with all steps:
  - Loading datasets
  - Data inspection (shape, info, missing values)
  - Cleaning: date conversion, handling missing values, removing currency symbols/commas from prices
  - Merging transactions with prices on product + approximate week
  - Final checks and saving

- **nigerian_market_merged_cleaned.csv**  
  Final cleaned and merged dataset ready for analysis/forecasting

## Key Steps Performed
- Converted date columns to datetime
- Removed ₦ symbol and commas from price → converted to numeric
- Filled missing quantity/unit_price/price with medians (overall or per product)
- Removed duplicates
- Merged using left join on product + week-start date
- Filled remaining missing prices with product median

## Repository Link
https://github.com/idorenyininwang-byte/nigerian-market-data-wrangling-assignment

Submitted for review.
