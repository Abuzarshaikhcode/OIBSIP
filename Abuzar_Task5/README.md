# Task 5 — Sales Prediction Using Python

## Project Overview

This project uses machine learning to predict product sales based on advertising expenditure across different media channels.

The analysis focuses on TV, Radio, and Newspaper advertising spend and their relationship with sales.

## Objective

The main objective is to understand how advertising expenditure affects sales and build regression models that can predict sales from advertising data.

## Dataset

The project uses the `Advertising.csv` dataset.

It contains the following variables:

- TV — advertising expenditure on TV
- Radio — advertising expenditure on Radio
- Newspaper — advertising expenditure on Newspaper
- Sales — product sales

## Exploratory Data Analysis

The dataset was explored using:

- Missing-value checks
- Descriptive statistics
- Pairplot
- Scatter plots
- Correlation analysis

Individual scatter plots were created to examine the relationship between sales and each advertising channel.

## Correlation Analysis

A correlation heatmap was used to understand the relationships between advertising expenditure and sales.

The analysis showed that TV advertising has a strong relationship with sales, while Radio also has a meaningful relationship.

## Machine Learning Models

Two regression approaches were used:

1. Linear Regression
2. Random Forest Regressor

The data was divided into training and testing sets before model training.

## Model Evaluation

The models were evaluated using:

- Mean Absolute Error (MAE)
- Root Mean Squared Error (RMSE)
- R² Score

These metrics were used to compare prediction accuracy and overall model performance.

## Best Performing Model

Based on the evaluation results from this implementation, **Random Forest Regressor** performed better than Linear Regression.

The Random Forest model achieved an R² score of approximately **0.955**, compared with approximately **0.906** for Linear Regression.

Therefore, Random Forest Regressor was selected as the best-performing model.

## Feature Importance

Feature importance analysis showed that **TV advertising expenditure** had the strongest contribution to sales prediction among the three advertising channels.

Radio also had a noticeable contribution, while Newspaper had a comparatively smaller impact.

## Residual Analysis

A residual plot was created for the best-performing model to examine whether prediction errors were randomly distributed or showed any systematic pattern.

## Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn
- Jupyter Notebook

## Conclusion

This project demonstrates how regression techniques can be used to predict product sales from advertising expenditure. The comparison showed that Random Forest Regressor provided stronger predictive performance than the Linear Regression baseline on the tested data.