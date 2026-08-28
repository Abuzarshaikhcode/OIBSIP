# Task 3 — Car Price Prediction with Machine Learning

## Project Overview

This project uses machine learning to estimate the selling price of used cars based on different vehicle characteristics.

## Objective

The main objective is to build regression models that can predict the selling price of a used car using information such as its age, present price, kilometers driven, fuel type, seller type, transmission, and previous ownership.

## Dataset

The project uses the Vehicle Dataset from CarDekho.

The dataset contains information about used cars, including:

- Car Name
- Manufacturing Year
- Present Price
- Kilometers Driven
- Fuel Type
- Seller Type
- Transmission
- Number of Previous Owners
- Selling Price

## Data Cleaning

The dataset was examined and prepared by:

- Checking for missing values
- Checking duplicate records
- Reviewing categorical values
- Converting data into suitable formats
- Preparing numerical and categorical features for machine learning

## Feature Engineering

Two additional features were considered during preprocessing:

- **Car Age** — calculated from the manufacturing year
- **Brand** — extracted from the car name

These features provide additional information that can help the regression models estimate the selling price.

## Exploratory Data Analysis

The analysis includes:

- Selling price distribution
- Selling price by fuel type
- Selling price versus car age
- Feature correlation analysis

A correlation heatmap was also used to understand relationships between numerical variables.

## Machine Learning Models

Two regression models were trained and compared:

1. Linear Regression
2. Random Forest Regressor

The dataset was divided into training and testing sets before model training.

## Model Evaluation

The models were evaluated using:

- Mean Absolute Error (MAE)
- Root Mean Squared Error (RMSE)
- R² Score

These metrics were used to compare the prediction performance of the models.

## Best Model

Based on the evaluation results from this implementation, **Linear Regression** performed better than the Random Forest Regressor.

The Linear Regression model achieved an R² score of approximately **0.779** on the test data.

## Feature Importance

Feature relationships and model-based analysis were used to understand which characteristics contribute most to used-car prices.

## Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn
- Jupyter Notebook

## Conclusion

This project demonstrates how machine learning and feature engineering can be applied to used-car price prediction. The comparison of regression models provides an understanding of how different algorithms perform on the same dataset.