# credit-risk-classification

Overview

This project involves building and evaluating a logistic regression model to assess credit risk using historical lending data. The goal is to predict the likelihood of a loan defaulting (high-risk) or being healthy using various features from the dataset.

Steps
1. Split the Data into Training and Testing Sets
Read the Data:

The dataset lending_data.csv is loaded into a Pandas DataFrame from the Resources folder.
Create Labels and Features:

Labels (y): Created from the loan_status column, where 0 indicates a healthy loan and 1 indicates a high-risk loan.
Features (X): Created from the remaining columns in the dataset.

Split the Data:

The data is divided into training and testing sets using train_test_split with 70% for training and 30% for testing.

2. Create a Logistic Regression Model
Instantiate and Fit the Model:

A logistic regression model is created using LogisticRegression with a random_state of 1 for reproducibility.
The model is trained using the training data (X_train and y_train).
Make Predictions:

Predictions are generated for the testing data using the fitted model.
Evaluate the Model’s Performance:

Confusion Matrix: Displays the counts of true positives, true negatives, false positives, and false negatives.
Classification Report: Provides precision, recall, and F1-score for both the 0 (healthy loan) and 1 (high-risk loan) labels.

3. Credit Risk Analysis Report

Overview:

The analysis aims to evaluate how well the logistic regression model predicts loan risk and to provide insights into its performance.

Model Performance:

Accuracy, Precision, and Recall:
Accuracy, precision, and recall scores for the model are detailed in a bulleted list.
Summary and Recommendations:
A summary of the model’s performance, including whether the model is recommended for use based on its predictive ability.
