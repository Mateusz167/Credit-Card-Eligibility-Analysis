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

## Visualization
The Power BI dashboard provides insights into:
- Demographic breakdowns.
- Eligibility analysis by various factors.
- Account and employment details.
- Ownership and contact information.
