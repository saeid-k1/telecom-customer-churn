Telecom Customer Churn Prediction

Project Overview

This project uses customer data to analyze and predict telecom customer churn.

Problem Statement

Telecom companies may lose customers when they stop using their services. This project aims to identify customers who are more likely to leave so the company can prioritize customer retention efforts.

Project Objectives

- Explore customer data and identify churn patterns.
- Prepare data for machine learning.
- Train and compare classification models.
- Evaluate model performance.
- Provide business recommendations to support customer retention.

Best Model

The tuned HistGradientBoosting model achieved the following results on the test set:

- Accuracy: 63.79%
- Precision: 63.12%
- Recall: 64.78%
- F1-score: 63.94%
- ROC-AUC: 0.6923

The model can help prioritize customers based on predicted churn risk. Its performance is moderate, and retention campaigns should be tested before drawing conclusions about their effectiveness.

Project File

- "Telecom_Churn_Analysis.ipynb": Contains the data analysis, model training, evaluation, and business recommendations.

Data

The dataset files are not included in this repository. Use the authorized source to obtain them.

Tools

Python, pandas, NumPy, Matplotlib, Seaborn, and scikit-learn.