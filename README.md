# Diabetes Prediction using Logistic Regression
This project applies Logistic Regression to predict whether a patient is diabetic or not based on medical features from the Pima Indians Diabetes Dataset(sourced from Kaggle).

## Overview
The goal of this notebook is to build a simple yet effective classification model that helps identify diabetic patients using features such as:
- Glucose
- BMI
- Age
- Pregnancies
These were selected after visual exploration showed they best separate the two outcome classes.

## Steps Performed
1. Importing Libraries – Loaded all required Python libraries like pandas, seaborn, matplotlib, and scikit-learn.
2. Loading Dataset – Read and examined the Kaggle diabetes dataset.
3. Exploratory Data Analysis (EDA) – Used pairplots and visualizations to understand feature relationships.
4. Feature Selection – Chose the most discriminative features (Glucose, BMI, Age, Pregnancies).
5. Model Training – Trained a Logistic Regression model on the processed dataset.
6. Evaluation – Compared training and testing accuracies, analyzed confusion matrix, and reviewed precision/recall scores.

## Results
- Accuracy: 82%
- Precision (Class 0 – Non-Diabetic): 0.84
- Recall (Class 0): 0.92
- Precision (Class 1 – Diabetic): 0.76
- Recall (Class 1): 0.60
The model performs well overall, especially for non-diabetic cases.
However, it misses some diabetic cases, showing lower recall for class 1.

## Conclusion

The model demonstrates good predictive performance but shows bias toward the non-diabetic class. Future improvements could involve:
- Dataset balancing (e.g., SMOTE or undersampling)
- Adjusting the classification threshold
- Including additional relevant features
