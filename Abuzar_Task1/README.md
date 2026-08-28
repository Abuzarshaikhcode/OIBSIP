# Task 1 — Iris Flower Classification

## Project Overview

This project focuses on classifying iris flowers into three different species: Setosa, Versicolor, and Virginica.

The classification is based on four physical measurements:
- Sepal Length
- Sepal Width
- Petal Length
- Petal Width

## Objective

The main objective of this project is to develop a machine learning classification model that can predict the species of an iris flower from its physical measurements.

## Dataset

The Iris dataset was loaded directly from the `scikit-learn` library using `load_iris()`. No external dataset was required.

The dataset contains 150 observations and 4 numerical features divided into 3 flower species.

## Exploratory Data Analysis

The dataset was explored using:

- Dataset shape
- Data types
- Missing value check
- Descriptive statistics
- Feature distributions
- Pairwise feature relationships
- Box plots

The analysis was used to understand the structure of the dataset and identify features that can effectively separate the flower species.

## Feature Selection

Petal length and petal width were found to be particularly useful for distinguishing between the three iris species because their distributions show clear differences among the classes.

## Machine Learning Models

Two classification models were trained and evaluated:

1. Logistic Regression
2. Random Forest Classifier

The dataset was divided into training and testing sets using an 80/20 split.

## Model Evaluation

The models were evaluated using:

- Accuracy
- Precision
- Recall
- F1-score
- Confusion Matrix

## Best Performing Model

Logistic Regression achieved an accuracy of approximately **93.33%** on the test dataset and was selected as the best-performing model among the tested classifiers.

## Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn
- Jupyter Notebook

## Conclusion

This project demonstrates the application of supervised machine learning for iris flower classification. The exploratory analysis helped identify the most informative features, and Logistic Regression provided strong classification performance on the test data.