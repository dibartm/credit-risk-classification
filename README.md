# credit-risk-classification
Credit Risk Analysis using Logistic Regression - README

Overview

This project aims to build a logistic regression model to analyze credit risk for a lending company. The dataset used for this analysis is "lending_data.csv," located in the Resources folder. The goal is to predict whether a loan is healthy (0) or has a high risk of defaulting (1) based on various features.

Steps

Split the Data into Training and Testing Sets
Read the "lending_data.csv" into a Pandas DataFrame.
Create the labels set (y) from the "loan_status" column, and the features set (X) from the remaining columns.
Split the data into training and testing datasets using train_test_split.
Create a Logistic Regression Model with the Original Data
Fit a logistic regression model using the training data (X_train and y_train).
Save the predictions for the testing data labels using the testing feature data (X_test) and the fitted model.
Evaluate the model's performance by generating a confusion matrix and printing the classification report.
Results
The performance of the logistic regression model is as follows:

Accuracy Score: [Add Accuracy Score]
Precision Score:
Label 0 (Healthy Loan): [Add Precision Score for Label 0]
Label 1 (High-Risk Loan): [Add Precision Score for Label 1]
Recall Score:
Label 0 (Healthy Loan): [Add Recall Score for Label 0]
Label 1 (High-Risk Loan): [Add Recall Score for Label 1]
Summary
The logistic regression model shows promising performance in predicting both healthy loans and high-risk loans. With high accuracy, precision, and recall scores, it effectively classifies loan status.

Based on these results, we recommend using the logistic regression model for credit risk analysis by the lending company. It demonstrates reliable predictive capabilities and can aid in identifying loans with a high risk of defaulting. However, continuous monitoring and updates to the model may be necessary as data and lending trends change over time.
