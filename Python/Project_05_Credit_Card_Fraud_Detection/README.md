# Credit Card Fraud Detection 

---

## Overview
This project focuses on detecting fraudulent credit card transactions using machine learning techniques. The objective is to build and evaluate classification models capable of identifying rare fraud cases within a highly imbalanced dataset, while balancing detection performance and false alarm rates.

The project emphasizes practical fraud analytics, model evaluation, and business-aware decision making.

---

## Dataset
- Credit card transaction dataset
- Highly imbalanced classes:
  - Legitimate transactions (majority)
  - Fraudulent transactions (minority)
- Numerical features derived from transaction behavior
- Binary classification task:
  - 0 → Legitimate
  - 1 → Fraud

---

## Objectives
- Explore and understand transaction data characteristics
- Address class imbalance in fraud detection
- Train classification models for fraud identification
- Evaluate models using appropriate metrics beyond accuracy
- Analyze trade-offs between fraud detection and false positives

---

## Data Preparation
- Loaded transaction data using Python
- Performed exploratory data analysis (EDA)
- Handled class imbalance during modeling
- Split data into training and test sets
- Prepared features for machine learning models

---

## Machine Learning Models
- Implemented baseline classification models
- Trained supervised learning models for fraud detection
- Compared model performance under different thresholds
- Evaluated predictions using confusion matrices

---

## Evaluation & Analysis
- Used evaluation metrics suitable for imbalanced data:
  - Precision
  - Recall
  - F1-score
- Analyzed false positives vs false negatives
- Demonstrated why accuracy alone is misleading in fraud detection
- Assessed model performance under different decision thresholds

---

## Tools & Libraries Used
- Python
- NumPy
- Pandas
- Matplotlib
- Scikit-learn

---

## Project Files

[Credit Card Fraud Detection Dataset.pdf](https://github.com/user-attachments/files/24386614/Credit.Card.Fraud.Detection.Dataset.pdf)

---

## Key Takeaways
- Fraud detection requires metrics beyond overall accuracy
- Class imbalance significantly impacts model evaluation
- Threshold tuning is critical for controlling alert rates
- Business context is essential when interpreting fraud models
