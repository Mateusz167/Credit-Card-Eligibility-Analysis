# Credit Card Eligibility Analysis

This repository contains code and visualizations for analyzing credit card eligibility based on past data. The analysis includes data cleaning and preparation using Python and visualization creation using Power BI.

## Data Cleaning (Python)

The Python script in this repository performs the following data cleaning tasks:

- Handling missing values
- Removing duplicates
- Converting data types
- Renaming columns
- Replacing values

### Code

The Python script for data cleaning and preliminary analysis can be found in the `data_cleaning.py` file.

## Visualization (Power BI)

The Power BI visualization provides insights into credit card eligibility based on past data. It includes various charts and graphs to help the marketing department identify customer groups to focus on in the coming months.

## Project Structure
- README.md: The readme file
- data_main.py : python code
- dataset : raw data downloaded from: https://www.kaggle.com/datasets/rohit265/credit-card-eligibility-data-determining-factors/data
- Data_csv : csv file after processing in Python
- PowerBI report

## Data Cleaning and Preprocessing
- Loaded the dataset and checked for missing values and duplicates.
- Renamed columns to be more descriptive.
- Replaced numerical values with categorical labels for better interpretation.

## Exploratory Data Analysis (EDA)
- Investigated the distribution of age and income using histograms.
- Visualized the distribution of credit card eligibility using a count plot.

## Correlation Analysis
- Calculated correlations between each feature and the target variable (Credit Card Eligibility).
- Used Point Biserial Correlation for binary features and Pearson Correlation for numeric features.
- Identified potential predictors of credit card eligibility.

## Analysis
The analysis involves:
- Calculating correlations between variables and the target.
- Visualizing distributions and interactions using Power BI.

### Important Note
The correlation between individual variables and the target variable (Credit Card Eligibility) is generally poor, with correlation coefficients less than 0.2 for all variables. This indicates that no single variable strongly predicts credit card eligibility. Therefore, the analysis focuses on exploring potential interactions and distributions rather than relying solely on correlation.

### Correlation Results
Here are the correlation coefficients between each variable and the target variable:

| Variable               | Correlation with Target |
|------------------------|-------------------------|
| ID                     | 0.0004                  |
| Gender                 | 0.0150                  |
| Has_car                | -0.0068                 |
| Has_property           | -0.0282                 |
| Has_work_phone         | -0.0029                 |
| Has_phone              | -0.0095                 |
| Has_email              | 0.0072                  |
| Is_unemployed          | -0.0249                 |
| Number_of_children     | 0.0117                  |
| Family_size            | 0.0071                  |
| Account_duration       | 0.0775                  |
| Income                 | 0.0188                  |
| Age_years              | -0.0437                 |
| Years_of_employment    | -0.0093                 |
| Type_of_income         | 0.0104                  |
| Education_level        | 0.0222                  |
| Marital_status         | 0.0249                  |
| Type_of_housing        | 0.0175                  |
| Occupation             | 0.0165                  |


## Visualization
The Power BI dashboard provides insights into:
- Demographic breakdowns.
- Eligibility analysis by various factors.
- Account and employment details.
- Ownership and contact information.

# Summary and Recommendations
## Overview
The analysis of the credit card eligibility data reveals several key insights about our customer base. Although the correlation between individual attributes and credit card eligibility is generally low, the visualizations provide a clear picture of the distribution and characteristics of eligible customers. This information is vital for targeting the right customer groups in our upcoming marketing campaigns.

# Contextual Factors
## Impact of Recent Economic Conditions:
Over the past few years, we have struggled with high inflation, which caused increased interest rates due to the COVID-19 pandemic and the war in Ukraine. Now, inflation has fallen, which should cause interest rates to decrease in the foreseeable future. This economic context might explain the current low level of eligibility for credit cards as consumers' financial stability and borrowing capacities have been impacted by these high interest rates. As the economic situation improves, we may see an increase in eligibility rates.

# Recommendations for Targeting Customer Groups
## 1. Target Specific Age Groups:

Analyze the clustered column chart to identify age groups with higher eligibility rates. Focus on marketing campaigns towards these age groups. For example, if customers aged 25-35 show higher eligibility, tailor messages and offers specifically for this demographic.

## 2. Income Type Segmentation:

Identify the income types that are more prevalent among eligible customers. If salaried employees or business owners show higher eligibility, design credit card products and marketing messages that cater specifically to their financial behaviors and needs.

## 3. High-Income Individuals:

Although the correlation is low, higher-income individuals generally have a slightly better chance of eligibility. Marketing efforts can include premium credit card offerings to higher-income customers.

# Data Limitations
## Lack of Information on Other Sources of Credit:
It is important to note that the dataset does not include information about other sources of credit such as mortgages, consumer credit, or payday loans. These additional financial obligations could significantly impact a customer's eligibility for a new credit card. Future analyses should consider incorporating such data to provide a more comprehensive assessment of credit card eligibility.

# Final Thoughts
While individual correlations with eligibility are low, the combination of these attributes in our visualizations provides a comprehensive understanding of our customer base. By focusing on education levels, specific age groups, prevalent income types, and gender-specific trends, we can enhance our marketing strategies to target the most promising customer segments effectively.

Additionally, the anticipated decrease in interest rates as inflation falls may positively impact credit card eligibility in the future, making this an opportune moment to refine and target our marketing efforts.
