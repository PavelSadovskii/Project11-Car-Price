# Project Description

This project involves building a model to determine the cost of cars based on historical data, including technical specifications, equipment, and prices of cars.

## Project Goal

The goal of this project is to develop a model that can predict the market value of cars accurately and efficiently. The quality of prediction, prediction speed, and training time are essential criteria for the customer.

## Tools and Libraries

The following tools and libraries were used for this project:

- Python
- NumPy
- Pandas
- Scikit-Learn
- LightGBM

## Project Steps

### Step 1: Data Preparation

- Download the dataset from the file path: `/datasets/autos.csv`.
- Explore the dataset and handle missing values and anomalies.
- Prepare the data for model training.

### Step 2: Model Training

- Divide the dataset into training, validation, and test sets.
- Preprocess categorical features using one-hot encoding.
- Scale numeric features.
- Train different regression models, including Linear Regression, Decision Tree, and LightGBM.
- Optimize hyperparameters for the LightGBM model using grid search.

### Step 3: Model Evaluation

- Evaluate the models based on the root mean squared error (RMSE) metric.
- Select the best-performing model based on RMSE.

### Step 4: Conclusion

Summarize the results and findings of the project, including the chosen model and its performance.

## Findings

- The LightGBM model outperformed other models in terms of RMSE.
- The RMSE achieved by the LightGBM model is 1703, meeting the customer's requirement of an RMSE below 2500.

## Possible Reasons for Data Gaps

Data gaps in the dataset may be due to incomplete data collection, errors in data entry, or missing information from certain car listings.

## Why LightGBM Was Chosen as the Best Model

LightGBM was chosen as the best model due to its superior performance in terms of prediction accuracy and speed. It outperformed both Linear Regression and Decision Tree models, making it the ideal choice for predicting car prices in this project.

## General Conclusion

The developed model, based on LightGBM, can accurately predict the market value of cars. It meets the customer's requirements for prediction quality, speed, and training time, making it a valuable tool for pricing used cars in the "Not beaten, not beautiful" service.
