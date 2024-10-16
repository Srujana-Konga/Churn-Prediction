# Online Retail Customer Churn Prediction Analysis

## Overview
This project aims to analyze and predict customer churn in the online retail sector. By identifying the factors that contribute to customer loss, businesses can implement targeted strategies to improve customer retention and enhance overall profitability. The analysis utilizes various customer features, including demographics and purchasing behavior, to build a predictive model for churn.

## Dataset Columns
The dataset contains the following columns:

- **Customer_ID**: Unique identifier for each customer.
- **Age**: Age of the customer.
- **Gender**: Gender of the customer (Male/Female).
- **Annual_Income**: Annual income of the customer in currency units.
- **Total_Spend**: Total amount spent by the customer over their lifetime.
- **Years_as_Customer**: Duration (in years) that the customer has been with the company.
- **Num_of_Purchases**: Total number of purchases made by the customer.
- **Average_Transaction_Amount**: Average amount spent per transaction.
- **Num_of_Returns**: Total number of returns made by the customer.
- **Num_of_Support_Contacts**: Number of times the customer has contacted customer support.
- **Satisfaction_Score**: Customer satisfaction score derived from surveys.
- **Last_Purchase_Days_Ago**: Number of days since the last purchase was made.
- **Email_Opt_In**: Indicates if the customer has opted in for marketing emails (Yes/No).
- **Promotion_Response**: Indicates if the customer responded to promotions (Yes/No).
- **Target_Churn**: Indicates if the customer has churned (1) or not (0).

## Libraries Used
The following Python libraries were utilized in this analysis:

- `pandas`: For data manipulation and analysis.
- `numpy`: For numerical operations.
- `matplotlib`: For data visualization.
- `seaborn`: For enhanced data visualization and statistical analysis.

## Methodology
1. **Data Loading**: Load the dataset and examine its structure.
2. **Data Cleaning**: Handle missing values and remove duplicates.
3. **Exploratory Data Analysis (EDA)**: Conduct univariate and bivariate analyses to understand the data.

## Data Cleaning
- **Missing Values**: Identified and handled missing values through imputation or removal.
- **Duplicates**: Checked for and removed any duplicate records in the dataset.
- **Data Types**: Ensured all columns had the correct data types for analysis.

## Kurtosis
Kurtosis is a statistical measure that describes the shape of a distribution's tails in relation to its overall shape. Here’s how to compute the kurtosis for numerical features:

## Univariate Analysis
Univariate analysis focuses on examining individual variables in the dataset to understand their distributions and characteristics. This analysis helps summarize the key aspects of each feature:


## Bivariate Analysis
Bivariate analysis investigates the relationships between pairs of variables to identify correlations and patterns. 
