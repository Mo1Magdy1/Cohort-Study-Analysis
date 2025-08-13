# 🩺 Cohort Diabetes Prediction Analysis

## 🎯 Objective
Predict the risk of diabetes in patients using clinical and demographic data. This project implements logistic regression, evaluates model performance, and generates key metrics for prediction accuracy.

## 🛠 Work Done
- 📊 **Data Import & Exploration**
  - Load CSV dataset (`diabetes.csv`)
  - Display first 10 rows
  - Calculate descriptive statistics: mean, standard deviation, min, max, and count

- 🔬 **Data Preprocessing**
  - Stratify `Age` into groups
  - Handle missing values (if any)
  - Split dataset into **train (70%)** and **test (30%)** sets

- 📈 **Modeling**
  - Train **Logistic Regression** model on predictors:
    - Age, BMI, DBP, Diabetes Pedigree Function, Glucose, Insulin, Pregnancies, SkinThickness
  - Include `AgeGroup` as categorical variable

- 📉 **Model Evaluation**
  - Compute **Odds Ratios** with 95% Confidence Intervals
  - Generate **ROC Curve** and calculate **AUC**
  - Predict probabilities and convert to binary outcomes

- 📊 **Performance Metrics**
  - Confusion Matrix
  - Accuracy, Sensitivity, Specificity

- 💻 **Languages Used**
  - SAS, R and Python (scikit-learn, statsmodels, tidyverse, caret)

