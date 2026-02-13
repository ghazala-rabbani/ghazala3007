# Risk Rating Analysis using Logistic Regression

## Overview

This project builds a binary classification model to predict financial *Risk Rating* (High Risk vs Low Risk) using Logistic Regression.

The dataset is synthetically generated to simulate financial risk evaluation.

---

## Problem Statement

Given financial features:

•⁠  ⁠Age  
•⁠  ⁠Income  
•⁠  ⁠Credit Score  

Predict:

•⁠  ⁠1 → High Risk  
•⁠  ⁠0 → Low Risk  

High Risk is defined when:

•⁠  ⁠Credit Score < 600  
OR  
•⁠  ⁠Income < 40000  
OR  
•⁠  ⁠Age < 25  

---

## Dataset

Synthetic data is generated using NumPy:

•⁠  ⁠1000 records
•⁠  ⁠Age range: 18–70
•⁠  ⁠Income range: 20,000–150,000
•⁠  ⁠Credit Score range: 300–850

This allows the project to run independently without requiring external datasets.

---

## Model Used

Logistic Regression (Scikit-learn)

This model is suitable for binary classification problems and serves as a strong baseline classifier.

---

## Workflow

1.⁠ ⁠Generate synthetic dataset  
2.⁠ ⁠Create pandas DataFrame  
3.⁠ ⁠Split dataset into training (80%) and testing (20%)  
4.⁠ ⁠Train Logistic Regression model  
5.⁠ ⁠Evaluate model using:
   - Accuracy
   - Classification Report (Precision, Recall, F1-score)  
6.⁠ ⁠Make predictions on new sample data  

---

## Evaluation Metrics

The model performance is evaluated using:

•⁠  ⁠Accuracy Score  
•⁠  ⁠Precision  
•⁠  ⁠Recall  
•⁠  ⁠F1-Score  
•⁠  ⁠Classification Report  

---

## Example Prediction

The model predicts risk rating for new individuals based on their:

•⁠  ⁠Age
•⁠  ⁠Income
•⁠  ⁠Credit Score
