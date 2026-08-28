# Task 4 — Email Spam Detection with Machine Learning

## Project Overview

This project uses Natural Language Processing (NLP) and machine learning techniques to classify messages as either spam or legitimate (ham).

## Objective

The main objective is to build a text classification system that can automatically identify unwanted spam messages and distinguish them from legitimate messages.

## Dataset

The project uses the SMS Spam Collection dataset.

The dataset contains text messages labeled as:

- Spam
- Ham

## Data Exploration

The dataset was explored to understand:

- Number of spam messages
- Number of ham messages
- Class distribution
- Text data characteristics

## Text Preprocessing

The text data was prepared before feature extraction using techniques such as:

- Converting text to lowercase
- Removing punctuation
- Removing unnecessary characters
- Removing common stopwords
- Normalizing the text

## TF-IDF Feature Extraction

TF-IDF (Term Frequency-Inverse Document Frequency) was used to convert text messages into numerical features.

TF-IDF gives greater importance to words that are useful for distinguishing documents while reducing the importance of words that occur very frequently across the dataset.

## Machine Learning Models

Two classification models were trained:

1. Multinomial Naive Bayes
2. Logistic Regression

The dataset was divided into training and testing sets before model training.

## Model Evaluation

The models were evaluated using:

- Accuracy
- Precision
- Recall
- F1-score
- Confusion Matrix

## Importance of Recall

Recall is particularly important in spam detection because it measures how many actual spam messages are correctly identified.

A low recall means that more spam messages may be incorrectly classified as legitimate messages and reach the user.

## Best Performing Model

The model with the stronger evaluation results on the test dataset was selected as the best-performing classifier.

The comparison was based on accuracy, precision, recall, and F1-score rather than accuracy alone.

## Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- NLTK / Regular Expressions
- Matplotlib
- Jupyter Notebook

## Conclusion

This project demonstrates how Natural Language Processing and machine learning can be combined to detect spam messages. TF-IDF provides numerical text features, while classification algorithms use these features to distinguish spam from legitimate messages.