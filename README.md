# Iris Flower Classification

A Machine Learning project that classifies Iris flowers into different species using Logistic Regression and the Iris dataset. This project demonstrates the complete machine learning workflow including preprocessing, model training, evaluation, prediction, and model saving.

---

## Overview

The model predicts the species of an Iris flower based on the following features:

- Sepal Length
- Sepal Width
- Petal Length
- Petal Width

### Predicted Classes

- Iris Setosa
- Iris Versicolor
- Iris Virginica

---

## Features

- Data Preprocessing
- Exploratory Data Analysis
- Logistic Regression Model
- Train-Test Splitting
- Model Evaluation
- Prediction on New Data
- Model Saving using Joblib

---

## Tech Stack

- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn
- Joblib
- Google Colab

---

## Dataset

This project uses the Iris dataset available in Scikit-learn.

### Dataset Details

- Total Samples: 150
- Number of Classes: 3
- Number of Features: 4

---

## Model Performance

The Logistic Regression model achieved high accuracy on the test dataset.

### Evaluation Metrics

- Accuracy Score
- Confusion Matrix
- Classification Report

---

## Sample Prediction

```python
sample = [[5.1, 3.5, 1.4, 0.2]]

prediction = model.predict(sample)

print(prediction)
