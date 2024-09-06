# Bank Customer Term Deposit Subscription Prediction

## Project Overview
This project aims to predict whether a bank customer would subscribe to a term deposit based on various customer, marketing, and bank-related features. The analysis was conducted using a dataset from the UCI Machine Learning Repository, focusing on reducing marketing costs by targeting potential customers effectively.

## Table of Contents
1. [Introduction & Objective](#introduction--objective)
2. [Data Overview](#data-overview)
3. [Exploratory Data Analysis (E.D.A)](#exploratory-data-analysis-eda)
4. [Model Presentation](#model-presentation)
5. [Conclusion](#conclusion)
6. [Business Proposal](#business-proposal)

## 1. Introduction & Objective
The goal of this project is to predict the likelihood of a bank customer subscribing to a term deposit after a marketing campaign. By identifying customers who are likely to accept the offer, the bank can optimize its marketing efforts and reduce costs.

## 2. Data Overview
- **Source**: UCI Machine Learning Repository
- **Raw Data**: 
  - 20 input features and 1 target feature (Subscription Status)
  - ~41,000 records
- **Cleaned Data**:
  - 18 features and ~39,000 samples after cleaning

## 3. Exploratory Data Analysis (E.D.A)
The E.D.A section provides insights into customer behavior based on features such as age and education level. Some of the key findings include:
- **Age**: Customers' likelihood of subscribing to the offer varies with age.
- **Education**: Educational background influences offer acceptance.

## 4. Data Processing
Several data processing steps were undertaken:
- **Feature Handling**: Removing irrelevant features and samples, replacing unknown values with the mode, and handling class imbalance using SMOTE.
- **Feature Importance**: Age and education emerged as key predictors of term deposit subscription.

## 5. Model Presentation
Three models were compared:
- **Decision Tree Classifier**
- **Logistic Regression**
- **K-Nearest Neighbors Classifier**

A Random Forest model with hyperparameter tuning was selected for its strong performance, achieving:
- **Accuracy**: 89%
- **Recall**: 88% on the test set

## 6. Conclusion
The project successfully identified key features influencing customer subscription behavior. With an accuracy of 89% and a recall of 88%, the model demonstrates strong predictive power. However, improvements could be made with a more balanced dataset and further customer segmentation.

## 7. Business Proposal
The findings suggest targeted marketing based on age and education, allowing the bank to optimize its marketing efforts and reduce costs.

 
