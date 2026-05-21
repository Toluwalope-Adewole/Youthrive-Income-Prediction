# Youthrive-Income-Prediction
# Income Level Prediction

**Domain:** Census Data · Classification
**Programme:** Youthrive Data Science Capstone

---

## Overview

A binary classification model that predicts whether an
individual earns above or below $50,000 per year using
US Census demographic data. Three algorithms compared
with full hyperparameter tuning.

---

## Problem

Understanding what demographic and occupational factors
drive income levels is useful for policy targeting,
financial inclusion, and social programme design.

---

## Workflow

1. Loaded UCI Adult Census dataset
2. Replaced missing placeholders and imputed values
3. Label-encoded categorical features
4. Scaled numerical features using StandardScaler
5. Applied 70/30 train-test split
6. Trained Logistic Regression, Random Forest (GridSearchCV),
   and SVM
7. Evaluated all three with classification report and
   confusion matrix

---

## Models Compared

- Logistic Regression
- Random Forest (with GridSearchCV tuning)
- Support Vector Machine (SVM)

---

## Tools

Python · pandas · scikit-learn · Matplotlib · Seaborn
Google Colab

---

## Dataset

UCI Adult Census dataset.
Target variable: income (≤50K / >50K)
Key features: age, education, occupation, workclass,
hours per week, marital status

---

## Author

Adewole Toluwalope Olumide
Agricultural Economist & Data Scientist
Lagos, Nigeria
github.com/Adewole-Toluwalope
