# Flight Price Prediction

This project focuses on predicting flight ticket prices, addressing the common challenge of fluctuating prices in the airline industry. The machine learning model built here aims to provide insights and predictions based on historical flight data.

## Problem Statement

Flight ticket prices are known for their unpredictability, often varying from day to day. The objective of this project is to leverage machine learning techniques to demonstrate that, given the right data, flight ticket prices can be predicted. The dataset used includes prices of flight tickets for various airlines between March and June 2019, across different cities.

## Datasets

Two datasets, namely Train data and Test data, are utilized in this project. The training data consists of 10,683 rows, incorporating both categorical and numerical features. The test data, containing 2,671 rows, lacks the 'Price' column, which needs to be predicted using the trained model.

## Python Coding Steps

Step 1: Import Relevant Libraries

The initial step involves importing essential libraries in Python to facilitate the subsequent data analysis and model building.

Step 2: Import and Append Train and Test Data

Train and test datasets are imported and appended to streamline data processing. After transformations, they can be separated into train and test datasets again.

Step 3: Feature Generation

This step focuses on data transformation and cleaning, including the splitting of date-related columns, extracting arrival and departure times, handling total stops, and processing route information.

Step 4: Prepare Categorical Variables

Label encoding is employed to convert categorical text data into numerical data, making it understandable for machine learning models.

Step 5: Divide the Dataset

The dataset, now numerical after label encoding, is divided into training and testing sets. The 'Price' column is dropped from the test set as it is the target variable.

Step 6: Build Model

Various regression techniques, including Linear Regression, Ridge Regression, Lasso Regression, Elastic Net Regularization, Extreme Gradient Boosting (XGBoost), Light GBM, and Stacking, are employed to build and evaluate the predictive models.

## Model Performance (Root Mean Square Error - RMSE)

Linear Regression: 3238.32

Ridge Regression: 3238.15

Lasso Regression: 3238.32

Elastic Net Regularization: 3238.30

XGBoost: 1297.70

Light GBM: 1411.42

Stacking: 1448.53

The XGBoost model demonstrates superior performance in this context. The stacking technique, which combines multiple models, also provides competitive results.

## Final Steps

The project concludes with exporting the predictions into a CSV file for submission. It emphasizes the importance of feature engineering and suggests avenues for further model improvement through parameter tuning.

Feel free to explore the project and share your thoughts or report any issues.





