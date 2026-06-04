# AIML-INTERNSHIP-TASK4
AIML Internship Task 4 Solution
Logistic Regression Classification

Overview
This project demonstrates a Binary Classification model using Logistic Regression on the Breast Cancer Wisconsin Dataset. The model predicts whether a tumor is malignant or benign based on various medical features.

Objective
Build a binary classifier using Logistic Regression.
Evaluate the model using Confusion Matrix, Precision, Recall, and ROC-AUC Score.
Visualize ROC Curve and Sigmoid Function.

Tools & Libraries:-
Python
Pandas
NumPy
Matplotlib
Scikit-learn
Dataset
Breast Cancer Wisconsin Dataset.

Steps Performed:-
Imported required libraries.
Loaded the Breast Cancer dataset.
Split the dataset into training and testing sets.
Standardized the features using StandardScaler.
Trained a Logistic Regression model.
Predicted test data.

Evaluated model performance using:
Confusion Matrix
Precision
Recall
F1-Score
ROC-AUC Score

Plotted:
ROC Curve
Sigmoid Function
Results
Dataset Shape
Plain text
(569, 30)
Confusion Matrix

ROC-AUC Score
Plain text
0.997
Model Accuracy
Plain text
97%
Evaluation Metrics
Precision
Measures how many predicted positive cases are actually positive.
Recall
Measures how many actual positive cases are correctly identified.
F1-Score
Harmonic mean of Precision and Recall.
ROC-AUC
Measures the model's ability to distinguish between classes.
Sigmoid Function
The Logistic Regression model uses the Sigmoid Function:
It converts values into probabilities between 0 and 1.

Conclusion
The Logistic Regression model achieved high accuracy and ROC-AUC score on the Breast Cancer dataset. The model effectively classified tumors as malignant or benign, making it suitable for binary classification tasks.
