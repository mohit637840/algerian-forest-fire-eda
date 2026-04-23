# Algerian Forest Fire Data Analysis

## Overview
This project performs data cleaning and exploratory data analysis (EDA) on the Algerian Forest Fires dataset. The dataset contains weather observations and fire indices from two regions: Bejaia and Sidi Bel-Abbes.

## Dataset Description
The dataset includes:
- Weather data: Temperature, Humidity, Wind Speed, Rain
- Fire Weather Index (FWI) components
- Target variable indicating fire occurrence

## Data Preprocessing
- Handled missing values and removed invalid rows
- Created a new feature "Region" to distinguish between two locations
- Cleaned column names and fixed formatting issues
- Converted string-based numerical columns into numeric format
- Processed target variable into binary form:
  - 0 → Not Fire
  - 1 → Fire

## Exploratory Data Analysis
- Distribution of fire vs non-fire cases
- Relationship between temperature and fire occurrence
- Analysis of Fire Weather Index (FWI)
- Correlation analysis between features

## Key Insights
- Higher temperature and FWI values are associated with fire occurrences
- Weather conditions play a significant role in fire prediction
- Data cleaning was essential due to inconsistencies in the raw dataset

## Tools Used
- Python
- pandas
- NumPy
- Matplotlib
- Seaborn

## Future Work
- Apply machine learning models for fire prediction
- Perform feature selection and model evaluation
