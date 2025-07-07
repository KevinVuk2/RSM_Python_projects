# Big Data Management & Analytics: Assignment 3 - Model Evaluation & Unsupervised Learning
This repository contains the solution for Assignment 3, which is divided into two parts. The first part focuses on an in-depth evaluation of the logistic regression model developed in Assignment 2. The second part shifts to unsupervised learning techniques to uncover patterns in a new dataset of customer book purchases.

# Part 1: Logistic Regression Model Evaluation

This section revisits the insurance.csv dataset to perform a rigorous assessment of the logistic regression model that predicts whether medical charges are above or below the mean.

# Key Objectives & Tasks:

1. Threshold Analysis: Evaluate model performance by generating confusion matrices at different classification thresholds (0.2, 0.5, and 0.8) to understand the trade-off between precision and recall.
2. Performance Metrics: Calculate and interpret a comprehensive set of evaluation metrics, including:
- Accuracy
- Precision
- Sensitivity (Recall / True Positive Rate)
- Specificity
- False Positive Rate
- ROC/AUC Analysis: Create an ROC (Receiver Operating Characteristic) curve and calculate the AUC (Area Under the Curve) to provide an aggregate measure of the model's ability to distinguish between classes.

# Part 2: Unsupervised Learning on Book Purchases
This section introduces a new dataset, books.csv, containing 500 customer transactions across five book genres. The goal is to apply unsupervised learning methods to discover hidden patterns in purchasing behavior.

# Key Objectives & Tasks:


1. Customer Similarity:

Calculate Euclidean and Manhattan distances to measure the similarity between the purchasing habits of different customers.
Compute the centroid to find the average customer profile for a specific segment.
2. Co-occurrence Analysis:
- Identify which book genres are most and least frequently purchased together.
- Market Basket Analysis (Association Rules):
- Calculate key metrics to uncover purchasing relationships:
- Support: To identify frequently purchased itemsets (e.g., {fiction, self_help}).
- Confidence: To measure the likelihood of one item being purchased given another (e.g., {fiction} → {mystery}).
- Lift: To determine if two items are purchased together more often than expected by chance, indicating a strong association.
