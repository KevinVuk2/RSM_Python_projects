# Big Data Management & Analytics: Assignment 1 - Orange Inc. Customer Analysis

This repository contains the solution for Assignment 1 of the Big Data Management and Analytics (BM04BIM) course. The project focuses on cleaning, analyzing, and visualizing an integrated customer dataset for a fictional technology company, Orange Inc.

# Business Context

Orange Inc. is a technology firm specializing in electronic products like the oPhone, oWatch, oPods, and oTV. Historically, customer data was managed in separate databases by three different departments:

- Marketing & Customer Relations: Handled customer demographics (age, gender) and loyalty tiers.

- Product Management: Tracked product ownership for each customer.

- Finance: Recorded transaction details, including payment method and date.

These databases have been merged into a single orange_inc.csv file. The goal of this assignment is to act as a data analyst for Orange Inc., tasked with cleaning this integrated dataset and extracting valuable business insights.

# Dataset

The primary dataset for this analysis is orange_inc.csv.
- Missing Values: Represented by a dash (-).

- Assumption: All products purchased by a single customer were bought on the same date.

# Data Dictionary

![image](https://github.com/user-attachments/assets/0a6971b5-4868-4b04-a0d8-c2b7ba121b6b)

# Key Objectives & Tasks

The analysis is structured around answering a series of questions to derive insights from the data.

1. Data Cleaning and Preparation

Import the dataset and report the number of missing values for each column.
Remove all rows containing at least one missing value.

2. Feature Engineering

Create a new column owns_multiple_products to identify customers who own two or more products.
Create a sales_revenue column by calculating the total purchase value for each customer based on the following product prices:
- oPhone: €1200
- oWatch: €300
- oPods: €150
- oTV: €2500

Create a month_of_purchase column by extracting the month from the transaction date.

3. Data Analysis and Insights

Perform conditional filtering to answer specific business questions, such as:
- How many female customers (18-25) used a Visa or Mastercard credit card?
- What percentage of customers older than 25 with a debit card own multiple products?
- How many customers own all four products?
- Calculate the average number of products owned per loyalty tier.
- Determine the total sales revenue from all customers and for each individual product.
- Identify the month with the highest sales revenue.

4. Visualization

- Create a bar chart to visualize sales revenue by month.
- Create a pie chart to show each product's share of the total revenue.

5. Targeted Segment Analysis

Isolate a specific customer segment: young_oPhone_owners (customers aged 18-25 who own an oPhone).
Analyze this segment to find their most preferred payment card type and the average number of products they own.


#Technology Stack

Language: Python (Pandas for data manipulation, Matplotlib/Seaborn for visualization)
