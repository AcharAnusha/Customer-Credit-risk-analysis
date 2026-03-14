# Customer-Credit-risk-analysis

A comprehensive **Exploratory Data Analysis (EDA)** project investigating customer credit risk patterns, characteristics, and relationships within financial data.

## Project Overview

This project performs exploratory analysis of customer credit data to uncover patterns, distributions, correlations, and key characteristics that define credit risk. Rather than building predictive models, the focus is on understanding the data itself and extracting meaningful insights through visualizations, using libraries like seaborn, matplotlib, pandas.

## What's Included

- **Data Loading & Overview**: Understanding dataset dimensions, structure, and basic information
- **Data wrangling**:
  - Filtering to remove extreme income values that could skew results.
  - Dropped irrelevant identifiers and processed missing values in Annual_Income.
  - Feature Engineering: Created Debt_to_Income_Ratio to assess relative financial burden.
    * Categorized Annual_Income into "Low," "Medium," and "High" brackets for segmented analysis.Identifying missing values, duplicates, and data inconsistencies
- **Univariate Analysis**: Distribution analysis of individual features
  - Analyzed distributions of age and income to understand the active customer base
  - Visualized Credit_Score distribution to identify the "Standard" category as the largest segment.
- **Bivariate Analysis**: Relationships between pairs of variables
  - Evaluated the impact of Num_of_Delayed_Payment and Num_Credit_Inquiries on credit scores.
  - Investigated how the number of bank accounts serves as a signal for potential financial instability.
- **Multivariate Analysis**: Patterns across multiple dimensions
  - Correlation heatmap
- **Data Visualization**: Comprehensive charts and plots revealing patterns
- **Key Findings & Insights**: Summary of important discoveries and observations

## Findings

* The majority of the customer base falls into the "Standard" credit score category. This is the primary growth segment for potential upsell and credit-improvement products.

* Customer engagement significantly peaks between the ages of 30 and 40, identifying this as the core demographic for marketing and product development.

* A higher number of active bank accounts (5–8) is a strong indicator of "Poor" credit scores. Financially stable customers ("Good" score) tend to maintain a leaner portfolio of 2–5 accounts.

* Frequent credit inquiries act as a "distress signal." As inquiry counts rise, the population of "Good" credit score holders drops

* There is a inverse relationship between Credit History Age and Outstanding Debt. Customers with longer, established credit histories demonstrate lower debt levels and better financial resilience.

* Strong positive correlations exist between Annual_Income, Amount_Invested_Monthly, and Monthly_Balance. High earners distinguish themselves not just by higher income, but by consistent wealth-building behaviors.


