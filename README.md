# Ford GoBike 2018 - Exploratory Data Analysis

## Project Summary
This project performs Exploratory Data Analysis (EDA) on Ford GoBike's 2018 trip data, 
covering all 12 months (~1.86 million trips) across the San Francisco Bay Area. It analyzes 
rider behavior, usage timing, demographics, and station popularity to uncover actionable 
business insights.

## Problem Statement
Ford GoBike generates large volumes of trip data monthly but lacks a consolidated view of 
how, when, and by whom its bikes are used. This project identifies usage patterns across 
time, demographics, and location to support data-driven business decisions.

## Dataset
- Source: Ford GoBike (now Bay Wheels) system trip data, 2018 (Jan-Dec)
- ~1.86 million trip records
- Columns: trip duration, start/end station, timestamps, bike ID, user type, birth year, 
  gender

## Business Objective
- Understand rider behavior across user types, demographics, and time
- Identify peak demand periods and high-traffic stations
- Differentiate Subscriber (commuter) vs Customer (casual) usage patterns
- Provide recommendations to grow ridership and revenue

## Approach
1. Loaded and combined 12 monthly CSV files
2. Cleaned data (missing values, duplicates, incorrect types, invalid ages)
3. Engineered features: month, day, hour, trip duration (minutes), age, age group, weekend flag
4. Performed EDA using 21 visualizations following the Univariate-Bivariate-Multivariate (UBM) framework
5. Derived insights and business recommendations

## Key Insights
- Usage is commuter-driven: Subscribers dominate weekday trips with peaks at 8-9 AM and 5-6 PM
- Customers ride longer, more on weekends, with strong summer seasonality
- Riders are concentrated in the 25-40 age range and skew male
- A small number of transit-hub stations drive most trips
- User type (Subscriber vs Customer) is the strongest behavioral differentiator - stronger 
  than age, hour, or location

## Recommendations
- Prioritize bike availability during commute peaks at high-traffic stations
- Run targeted weekend/summer campaigns to convert Customers into Subscribers
- Treat tourist-heavy vs commuter-heavy stations differently in operations strategy
- Improve signup data collection to close demographic data gaps

## Tools Used
Python, Pandas, NumPy, Matplotlib, Seaborn, Google Colab

## Files
- `FordGoBike_2018_EDA.ipynb` - Full analysis notebook
- `README.md` - Project overview


