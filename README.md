# Machine-Learning
This repository contains two machine learning projects.

1. Bengaluru House Price Prediction
This project uses a dataset of house prices in Bengaluru to build a model that predicts a home's price. The key steps include:
Data Cleaning: Removing irrelevant columns like area_type and society and handling missing values.
Feature Engineering: Creating a BHK (number of bedrooms) column from the size column and calculating a price_per_sqft metric to identify and remove outliers.
Model Training: Training a linear regression model and using GridSearchCV to find the best model parameters. The final model can predict a house price based on its location, size in square feet, and number of bathrooms and bedrooms.

2. Credit Card Fraud Detection
This project focuses on building a model to identify fraudulent credit card transactions. The dataset has a significant imbalance, with very few fraudulent transactions compared to legitimate ones. To address this, the project takes the following steps:
Data Preprocessing: Dropping irrelevant columns and preparing the remaining data by scaling numerical features and using one-hot encoding for categorical features.
Model Training: The model uses several classification algorithms, such as Logistic Regression, Random Forest, and Support Vector Machine (SVM). The class_weight parameter is set to 'balanced' to ensure the model doesn't ignore the rare fraudulent transactions.
Evaluation: The performance of the best model is evaluated using a confusion matrix and a classification report to assess its ability to correctly identify fraud cases.
