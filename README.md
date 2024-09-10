# Predicting Term Deposit Subscription

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
- **Age**: Customers' likelihood of subscribing to the offer varies with age, with lowest acceptance rate observed in the range 40-50 and increasing subscription rate with increasing age . 
- **Education**: Educational background influences offer acceptance. A positive correlation between the education level and offer acceptance is observed. 

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
- **Recall**: 89% on the test set

## 6. Conclusion
The project successfully identified key features influencing customer subscription behavior. With an accuracy of 89% and a recall of 89%, the model demonstrates strong predictive power. However, improvements could be made with a more balanced dataset and further customer segmentation.

## 7. Business Proposal
The findings suggest that targeted marketing based on customer age and education can significantly improve marketing conversion rates. Additionally, two bank-related factors (the number of employees and the 3-month Euribor rate) emerge as key determinants in offer acceptance. Larger bank branches, with higher employee counts, may offer better customer service and more sophisticated marketing efforts, leading to higher acceptance rates. Therefore, investing in increased employee capacity could further boost offer acceptance. Moreover, lower 3-month Euribor rates are correlated with higher subscription rates, indicating that banks should focus their marketing campaigns during periods of lower Euribor rates, as these times are often associated with financial stability and customer confidence.

Furthermore, the machine learning model used in this project demonstrates a high level of predictive accuracy, achieving 89% accuracy in forecasting customer responses. This indicates that leveraging machine learning can significantly enhance the precision of targeting strategies and improve overall marketing effectiveness.

 
