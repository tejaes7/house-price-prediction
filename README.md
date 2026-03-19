# California Housing Price Prediction

This notebook demonstrates the process of building and comparing two regression models, Linear Regression and Random Forest Regressor, to predict median house values in California using the `fetch_california_housing` dataset from `sklearn.datasets`.

## Table of Contents
1.  **Data Loading and Initial Exploration:** Loads the California housing dataset and displays basic information.
2.  **Linear Regression Model:** Implements a Linear Regression model, including data splitting, scaling, training, and evaluation.
3.  **Random Forest Regressor Model:** Implements a Random Forest Regressor model, including data splitting, training, and evaluation.
4.  **Model Performance Insights:** Compares the performance of both models and provides conclusions based on MSE and R-squared scores.

## Dataset
The dataset used is the California Housing dataset, which contains information about housing prices in California. Key features include median income, house age, average rooms, average bedrooms, population, average occupancy, latitude, and longitude, with the target variable being `MedHouseVal` (median house value).

## Models Used
- **Linear Regression:** A basic linear model to establish a baseline.
- **Random Forest Regressor:** An ensemble learning method that builds multiple decision trees and merges their predictions to improve accuracy and control overfitting.

## Key Findings
The Random Forest Regressor model significantly outperforms the Linear Regression model, indicating that the relationship between the features and house prices is likely complex and non-linear.
