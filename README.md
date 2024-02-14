# Machine-Learning-with-Python

# Supervised Learning Capstone Project - Tree Methods Focus

## Goal:
The goal of this project is to create a model that predicts whether a customer will churn or not.

## Project Overview:
This project focuses on using supervised learning techniques, specifically tree-based methods, to create a predictive model for customer churn prediction. The dataset used for this project is "Telco-Customer-Churn.csv."

## Contents:
1. **Part 0: Imports and Data Reading**
   - Importing necessary libraries and reading in the dataset.

2. **Part 1: Quick Data Check**
   - Confirming data types and non-null values.
   - Obtaining a quick statistical summary of numeric columns.

3. **Part 2: Exploratory Data Analysis**
   - Checking for the presence of NaN values.
   - Exploring the distribution of TotalCharges between Churn categories.
   - Creating visualizations to analyze the data.

4. **Part 3: Churn Analysis**
   - Segmenting customers based on tenure.
   - Analyzing customer cohorts based on tenure length.

5. **Part 4: Predictive Modeling**
   - Training and evaluating different tree-based models:
     - Single Decision Tree
     - Random Forest
     - AdaBoost
     - Gradient Boosting

## Conclusion:
After evaluating the performance of different tree-based models, Gradient Boosting emerged as the preferred model due to its consistent performance across different evaluation metrics. It is recommended to use the Gradient Boosting model for predicting customer churn based on the analysis conducted in this project.

