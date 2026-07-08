# Gold Trade Analysis: Zimbabwe vs Uganda (2017–2023)
## Overview

This project analyzes gold export trends between Zimbabwe and Uganda from 2017 to 2023 using international trade data obtained from the UN Comtrade Database.

The objective was to understand how economic conditions, geopolitical events, and the COVID-19 pandemic influenced gold exports, trade value, pricing, and international trade relationships. The project combines data cleaning, exploratory data analysis, descriptive statistics, and business analysis to identify patterns in the gold trade and generate actionable insights.

## Business Problem

Gold is one of the most valuable export commodities for many African economies.
Understanding historical trade patterns helps governments, investors, and policymakers answer questions such as:

Which countries import the most gold?
How did COVID-19 affect exports?
Which markets generate the highest trade value?
Which trading partners dominate the gold market?
How do political and economic events influence exports?

This project compares Zimbabwe and Uganda to identify similarities, differences, and long-term trade trends.

## Dataset

The dataset was collected from the UN Comtrade Database and contains gold export records between 2017 and 2023.

Key variables include:
-Reporting Country
-Partner Country
-Export Quantity
-Trade Value (USD)
-Year
-Price per Quantity (derived feature)

The original dataset contained missing values and inconsistencies, requiring extensive preprocessing before analysis.

## Project Workflow
Data Collection
        │
        ▼
Data Discovery
        │
        ▼
Data Cleaning & Validation
        │
        ▼
Feature Engineering
        │
        ▼
Descriptive Statistics
        │
        ▼
Exploratory Data Analysis
        │
        ▼
Business Insights
        │
        ▼
Recommendations

## Technologies Used
Python
Pandas
NumPy
Matplotlib
Excel
Jupyter Notebook

## Data Preparation

Several preprocessing steps were performed to improve data quality:
-Removed missing values
-Checked for duplicate records
-Replaced incomplete yearly data using monthly records
-Removed aggregate "World" records to avoid double counting
-Created a new Price per Quantity feature
-Validated the transformed dataset before analysis

These steps reduced the dataset to a clean and analysis-ready format.

## Exploratory Data Analysis

The analysis focused on:
-Export quantity trends
-Export value trends
-Average gold price
-Country-wise trade distribution
-Year-over-year comparisons
-Pre-COVID, COVID, and post-COVID performance
-BRICS trade relationships
-Major export destinations

Visualizations were created to identify trade patterns and anomalies across different years and partner countries.

## Key Insights

Some of the major findings include:

-The United Arab Emirates (UAE) was the largest trading partner for both Zimbabwe and Uganda during the study period.
-Uganda experienced significant growth in gold exports before and during the COVID-19 pandemic, supported by strong trade with the UAE.
-Zimbabwe maintained consistently higher export volumes and trade values than Uganda.
-COVID-19 disrupted Zimbabwe's mining operations and exports due to logistical challenges and labor shortages.
-Uganda experienced missing post-2021 trade data, largely associated with tax disputes and changes in export regulations.
-Zimbabwe's gold exports recovered after the pandemic but declined again in 2023 because of economic uncertainty and new government regulations.

## Business Insights

The analysis highlights several important business observations:

-Heavy dependence on a single export market increases trade risk.
-Government regulations and taxation policies have a measurable impact on export performance.
-Data quality issues can significantly influence analytical outcomes and require careful preprocessing.
-External events such as pandemics and geopolitical developments can reshape international trade networks.

These findings can support policymakers, trade analysts, and investors in making informed decisions regarding international commodity markets.

## Future Improvements
-Develop an interactive Power BI dashboard for trade exploration.
-Incorporate predictive models to forecast future export trends.
-Expand the analysis to include additional African gold-producing countries.
-Integrate real-time trade data through APIs for automated reporting.


## Link to report https://github.com/aravinddev13/Gold-Trade-Analysis/blob/main/Aravind_Devakumar%20Gold%20Trade%20Analysis%20Final%20Report.pdf
