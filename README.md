# Customer-Segmentation-for-E-commerce

## Overview

This project focuses on customer segmentation using K-means clustering and PCA (Principal Component Analysis). The goal is to identify distinct groups of customers based on their purchasing behavior in an e-commerce dataset. Customer segmentation enables personalized marketing strategies and recommendations.

## Dataset

- **Source:** [Online Retail Dataset](https://archive.ics.uci.edu/ml/datasets/online+retail)
- **Description:**
  - Transnational dataset with transactions occurring between 01/12/2010 and 09/12/2011 for a UK-based non-store online retail company.
  - Mainly sells unique all-occasion gifts, with many customers being wholesalers.

## Data Understanding

- Importing necessary libraries and loading the dataset.
- Initial exploration of the dataset, including checking for missing values and understanding data types.
- Investigating negative values in Quantity and UnitPrice, addressing outliers, and checking for data integrity.

## Data Cleaning

### 1) Missing Values

- Addressing missing values in the 'Description' column.
- Handling missing 'CustomerID' values by creating a customer ID through the invoice number.

### 2) Correct Data Types

- Ensuring correct data types for each column.

### 3) Check for Duplication

- Removing duplicate rows from the dataset.

### 4) Outliers

- Analyzing and addressing outliers in the 'Quantity' and 'UnitPrice' columns.

## Feature Engineering

- Creating new features:
  - Date-related features: Year, Month, Day, Hour, DayOfWeek.
  - Customer-related features: Total spending per customer, Recency of each transaction.
  - Order-related features: Average basket size.

## EDA & Visualization

### 1) Univariate Analysis

- Exploring top products, customers, and countries.
- Analyzing time-related patterns, including total sales per day, month, and day of the week.

### 2) Bivariate & Multivariate Analysis

- Investigating correlations between features.
- Analyzing the influence of quantity, unit price, and customer spending on total sales.
- Identifying significant contributors to total sales and exploring relationships.

### 3) Correlation Analysis

- Examining relationships between different features using correlation coefficients.
- Visualizing correlations using heatmaps.

### 4) Time Series Analysis

- Analyzing total sales trends over time, including monthly and daily patterns.
- Identifying peak sales days and understanding customer behavior.

### 5) Dashboard

- Creating a simple dashboard for non-technical users to visualize key insights.

## Hypothesis Testing

- Concluding that hypothesis testing is not necessary for this project.

## Data Preprocessing

### 1) Feature Engineering

- Removing outliers identified during EDA.

### 2) Encoding

- Encoding categorical variables.

### 3) Scaling

- Standardizing numerical features.

### 4) Dimensionality Reduction

- Applying PCA to reduce dimensionality while retaining important information.

## Modeling

### 1) Choose Model

- Selecting K-means clustering for customer segmentation.

### 2) Train the Model

- Training K-means clustering model with an initial number of clusters.

### 3) Evaluate the Model

- Evaluating the model using inertia and scatter plots.

### 4) Hyperparameter Tuning

- Fine-tuning the number of clusters based on evaluation results.

## Interpretation of Model Parameters

- Analyzing cluster assignments and interpreting model results.

## Cluster Profiling

- Profiling each cluster based on key features and characteristics.

## Conclusion

- Summarizing key findings and insights from the customer segmentation analysis.
 
