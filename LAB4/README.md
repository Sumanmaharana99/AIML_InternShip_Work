Logistic Regression on Breast Cancer Dataset
Project Overview

This project implements a Logistic Regression model to classify breast tumors as either Malignant (Cancerous) or Benign (Non-Cancerous) using the Breast Cancer Wisconsin Dataset.

Steps Performed
1. Data Loading
Loaded the Breast Cancer dataset.
Inspected the dataset structure and target variable.
2. Data Preprocessing
Separated features and target variable.
Prepared the dataset for model training.
3. Train-Test Split
Split the dataset into training and testing sets.
Used 80% of the data for training and 20% for testing.
4. Feature Scaling
Standardized all feature values to ensure consistent scaling across features.
5. Model Training
Trained a Logistic Regression model on the training dataset.
6. Prediction
Generated class predictions on the test dataset.
Obtained prediction probabilities for each sample.
7. Threshold Tuning
Applied a custom classification threshold to analyze its impact on model performance.
Compared predictions based on probability values.
8. Model Evaluation

Evaluated the model using:

Confusion Matrix
Precision Score
Recall Score
ROC-AUC Score
Results
Accuracy: 98.25%
Precision: 100%
Recall: 95.35%
ROC-AUC Score: 99.77%
Key Findings
The model achieved excellent classification performance.
All predicted malignant cases were correctly classified.
The model successfully identified most malignant tumors with very few missed cases.
ROC-AUC score indicates outstanding class separation capability.