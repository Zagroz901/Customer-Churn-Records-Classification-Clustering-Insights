# Customer Churn Records: Classification & Clustering Insights

## Overview

This project aims to study and predict the phenomenon of customer churn in commercial banks using machine learning models. The dataset used includes various customer attributes, such as demographic information, account details, and transaction history.

## Key Features

- **Machine Learning Models**: The project leverages multiple machine learning algorithms to predict customer churn, including:
  - Logistic Regression
  - Decision Trees
  - Random Forest
  - K-Neighbors
  - XGBoost
  - Support Vector Machines (SVM)
  - CatBoost
  - Gradient Boosting
  - LightGBM
  
- **Data Preprocessing**: Extensive preprocessing techniques were employed, including handling missing values, categorical variable encoding (One Hot Encoding), and feature scaling (Standard Scaler).

- **Feature Engineering**: Derived important features such as:
  - **Salary to Balance Rate**: Assesses financial stability by comparing account balance to salary.
  - **Product Usage Rate by Year**: Tracks the frequency of product usage across years.
  - **Loyalty Rate by Age**: Measures customer loyalty based on their age and tenure with the bank.
  - **Credit Score Rate by Age**: Evaluates creditworthiness by comparing credit scores with age.

## Results

- **Model Performance**: 
  - Random Forest, XGBoost, and CatBoost models achieved the highest accuracy, with up to 89% accuracy in predicting customer churn.
  - Feature importance analysis revealed that age, the number of products, and balance were the most significant predictors of churn.
  
- **Clustering Analysis**:
  - Applied K-Means, DBSCAN, and Hierarchical Clustering to identify patterns and group similar customers.
  - K-Means clustering indicated four main clusters, aligning well with the classes identified by the churn prediction models.
  
- **Final Model**:
  - The CatBoostClassifier, combined with a weighted soft voting ensemble, provided the best results with an accuracy of 89% and an F1 score of 88%.

## Conclusion

This project highlights the effectiveness of machine learning models in predicting customer churn and provides valuable insights for retaining valuable customers. The use of ensemble methods and thorough feature engineering contributed significantly to the model's performance.

## References

- [Ramírez Martínez, Erick David. "Churn detection on bank customers."]
- [Charandabi, Sina E. "Prediction of Customer Churn in Banking Industry."]
- [Hend Sayed, Manal A. Abdel-Fattah, Sherif Kholief "Predicting Potential Banking Customer Churn using Apache Spark ML and MLlib Packages: A Comparative Study."]
