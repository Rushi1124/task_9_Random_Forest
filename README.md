# 🛡️ Credit Card Fraud Detection
## 📌 Project Overview

This project demonstrates credit card fraud detection using a Random Forest classifier. It handles highly imbalanced datasets, compares a baseline Logistic Regression model, evaluates using precision, recall, and F1-score, and identifies key features through feature importance analysis.

The project uses Python, Scikit-learn, and Pandas, and includes model persistence for deployment.

## 🎯 Objective

Detect fraudulent credit card transactions accurately.

Handle imbalanced data where fraud cases are rare.

Compare performance of baseline and ensemble models.

Save trained models for reuse in production.

## 🛠️ Tools & Libraries

Python

Pandas & NumPy

Scikit-learn

Matplotlib & Seaborn

Joblib

## ⚙️ Techniques

Data exploration to understand fraud vs non-fraud distribution

Feature scaling using StandardScaler for Amount and Time

Stratified train-test split to maintain class ratio

Baseline modeling with Logistic Regression

Random Forest classifier with n_estimators=100

Class imbalance handling with class_weight='balanced'

Model evaluation using Precision, Recall, F1-Score

Feature importance analysis for fraud detection indicators

Model persistence using .pkl files

## Dataset 

Creditcard dataset

## Author

Rushita Bhosale 
