# Dentistry Gender Prediction Project
## **Project Overview**
This project aims to predict gender based on dental measurements using various machine learning models. The dataset consists of dental features such as canine distances and widths.
## **Data Preprocessing**
1. *Handling Missing Values
2. *Encoding Categorical Features
3. *Scaling Features
## Exploratory Data Analysis (EDA)
1. *Outliers Detection:* Outliers are detected using the IQR (Interquartile Range) method. Outliers are values that fall below Q1 - 1.5IQR or above Q3 + 1.5IQR.
2. *Correlation Analysis:* Features that are highly correlated with each other are identified and dropped to reduce multicollinearity, which can negatively affect the model performance.
## Model Building

Several machine learning models are trained and evaluated for gender prediction.

1. *Linear Regression:* Although primarily used for regression tasks, it’s included for comparison.
2. *Decision Tree Classifier:* A simple, interpretable model that splits the data based on feature values.
3. *Random Forest Classifier:* An ensemble method that builds multiple decision trees and combines their predictions.
4. *XGBoost Classifier:* A powerful gradient boosting algorithm known for its high performance.
## Evaluation Metrics

The models are evaluated using various metrics to determine their performance:

1. *Confusion Matrix:* Provides a summary of prediction results on the classification problem. It shows the number of true positives (TP), true negatives (TN), false positives (FP), and false negatives (FN).
2. *Accuracy:* Measures the proportion of correctly classified instances out of the total instances.
3. *ROC Curve (Receiver Operating Characteristic Curve):* Plots the True Positive Rate (TPR) against the False Positive Rate (FPR) at different threshold settings.
4. *AUC (Area Under the ROC Curve):* Provides an aggregate measure of the model’s performance across all classification thresholds.
