# Big Data Management & Analytics: Assignment 2 - Insurance Cost Prediction

This  contains the solution for Assignment 2, which focuses on analyzing an insurance dataset to understand the factors that influence medical costs. The project involves exploratory data analysis and the implementation of three different predictive models: Linear Regression, Logistic Regression, and a Decision Tree.
Project Context
The project utilizes the insurance.csv dataset, which contains anonymized information about individuals, including their demographic data, lifestyle factors (like smoking), and the resulting medical charges billed by a health insurer.

# Key Variables:

- Predictors: age, gender, bmi, children, smoker, region
- Target: charges (yearly medical costs)

# Key Objectives & Tasks

The assignment is divided into three main parts:

1. Exploratory Data Analysis (EDA)

- Analyze how medical charges differ between smokers and non-smokers across various age groups.
- Generate a correlation matrix and heatmap to identify which numerical variables have the strongest relationship with charges.

2. Linear Regression
- Build a multiple linear regression model to predict the exact value of charges.
- Interpret model coefficients to understand the impact of each predictor.
- Assess core model assumptions (normality of residuals, homoscedasticity).
- Refine the model by applying a log transformation to the target variable (log_charges) to improve its performance and adherence to assumptions.
- Evaluate the model's fit using R-squared and use it to predict charges for new data.

3. Classification Models

Two classification models were developed to predict charge categories rather than exact values.

- Logistic Regression:
Engineered a binary target variable (binary_charges) to classify charges as either above or below the mean.
Built a logistic regression model to predict the probability of an individual having high medical costs.

- Decision Tree:
Created a multiclass target variable (multiclass_charges) by segmenting charges into 'low', 'medium', and 'high' based on quartiles.
Constructed and visualized a decision tree classifier (with a constrained depth to prevent overfitting) to predict these charge categories.
