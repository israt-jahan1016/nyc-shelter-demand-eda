# NYC Shelter Demand Analysis (EDA)

## Overview
This project explores trends in New York City shelter populations and their relationship with
minimum temperature and unemployment rates. The analysis focuses on exploratory data analysis (EDA)
rather than predictive modeling.

## Data Sources
- NYC Department of Homeless Services (Daily Shelter Census)
- NOAA Daily Minimum Temperature (Central Park)
- NYC Unemployment Rate (Monthly)

## Key Questions
- How has total shelter population changed over time?
- Is shelter demand strongly related to daily temperature?
- How does unemployment relate to shelter usage before and after COVID-19?

## Key Findings
- NYC shelter population experienced a permanent structural increase after COVID-19.
- Daily temperature shows little linear correlation with total shelter demand.
- Shelter demand increased even as unemployment declined, reflecting policy timing,
  eviction protections, and lag effects rather than direct causality.
- High shelter demand appears to be the new normal rather than a temporary spike.

## Methods Used
- Data cleaning & date standardization
- Merging daily and monthly datasets using time-based keys
- Statistical summaries and distribution analysis
- Correlation analysis
- Time-series visualization
- Bivariate analysis

## Tools
Python, Pandas, Matplotlib, Seaborn
