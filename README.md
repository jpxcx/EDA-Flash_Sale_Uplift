# EDA Project 
## Project Overview

This project analyzes the performance of a flash sale campaign by performing exploratory data analysis (EDA) and measuring uplift in buyer activity.
The goal was to understand buyer behavior during flash sales, identify key drivers of uplift, and generate insights for optimizing future campaigns.

This analysis was conducted as part of my Summer 2025 Data Science Internship at Shopee and has been refactored for demonstration purposes.

## Methods
1. Data Cleaning & Preprocessing
- Removed missing values and outliers
- Normalized transaction timestamps and categorical variables
- Joined multiple tables from PostgreSQL queries

2. Exploratory Data Analysis (EDA)
- Generated summary statistics and frequency distributions
- Visualized buyer purchase patterns using histograms and scatterplots
- Segmented users by activity levels (light, medium, heavy buyers)

3. Campaign Uplift Measurement
- Compared pre-sale vs. post-sale buyer activity
- Calculated uplift in KPIs (transactions, revenue, conversion rate)
- Applied statistical testing to assess significance

4. Visualization
- Created visual summaries (Gini curves, trend plots) for campaign performance
- Highlighted shifts in buyer activity distribution before and after the flash sale

## Key Results
- Identified significant uplift in conversion rate and average spend per buyer during the flash sale.
- Detected heterogeneous treatment effects across buyer segments—heavy buyers showed limited uplift compared to light buyers.
- Visualizations revealed time-based spikes in purchasing behavior (sale entry + closing hours).
