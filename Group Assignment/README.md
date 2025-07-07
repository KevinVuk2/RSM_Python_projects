# Big Data Management and Analytics: Group Project - EuroBank Customer Churn Analysis
This repository contains the solution for the final group project of the Big Data Management and Analytics (BM04BIM) course. The project is divided into two parts:

1. Business Context
EuroBank International (EBI) is experiencing a significant customer churn problem. Our group was tasked with conducting a comprehensive data analytics study to understand the root causes of churn, identify customers at high risk of leaving, and provide actionable recommendations to improve customer retention.

2. The Analytical Process
The project followed a structured data analysis workflow:

a. Data Pre-processing

The initial dataset (ebi_base_customers.csv) was cleaned and prepared for modeling. Key steps included:

- Handling Missing Values: Imputing missing data to ensure dataset completeness.
- Encoding Categorical Variables: Converting features like gender and country into numerical formats.
- Removing Irrelevant Features: Dropping the customer_id column as it provides no predictive value.
- Outlier Detection: Identifying and removing outliers using the Interquartile Range (IQR) method to enhance model robustness.

b. Exploratory Data Analysis (EDA)

We analyzed the cleaned data to uncover initial patterns and trends related to churn, focusing on:

- The overall churn rate.
- How churn varies by demographics like age, gender, and country.
- The relationship between customer tenure and their likelihood to churn.

c. Predictive Modeling

To identify at-risk customers, we built and evaluated at least three machine learning models (e.g., Logistic Regression, Decision Tree, Random Forest). The key objectives were:

- Feature Importance: Identifying the strongest predictors of churn (e.g., age, balance, products_number).
- Model Comparison: Evaluating models using metrics like accuracy, precision, recall, and AUC to select the most effective and reliable model for the task.

d. Recommendations and Profitability Analysis

Based on the model's insights, we formulated strategic recommendations for EBI. A key part of this was a profitability analysis to guide a proactive retention campaign. This involved:

- Using our best model to predict the churn probability for a new set of customers (ebi_exp_customers.csv).
- Calculating the total expected profit of the retention campaign at different probability thresholds, considering:

Cost to retain a customer: €1

Value of a retained customer: €5 and €10 scenarios.

Recommending the optimal number of customers to target to maximize the campaign's return on investment.
