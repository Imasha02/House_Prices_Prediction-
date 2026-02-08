# 🏠 House Price Prediction using Machine Learning

This project focuses on predicting residential house prices using machine learning techniques on the Ames Housing Dataset. It demonstrates a complete end-to-end ML workflow, including data preprocessing, feature engineering, model training, hyperparameter tuning, and ensemble learning.

📌 Project Overview

Goal: Predict house sale prices based on property features

Dataset: Ames Housing Dataset (Kaggle)

Problem Type: Regression

Evaluation Metric: Root Mean Squared Error (RMSE)

📌 Key Concepts Used

* Exploratory Data Analysis (EDA)

* Missing Value Handling (context-aware imputation)

* Feature Engineering

* Regularized Linear Models

* Tree-based Models

* Hyperparameter Tuning

* Ensemble Learning

📌 Outlier Treatment

Explicit outlier removal was not performed in this project. Since the primary models used were tree-based algorithms (Random Forest and Gradient Boosting), which are inherently robust to extreme values, outliers were retained to preserve potentially informative high-value observations.

Additionally, a log transformation of the target variable (SalePrice) was applied, which reduced skewness and mitigated the impact of extreme values without discarding valid data points.




