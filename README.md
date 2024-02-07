# Capstone Project: Breast Cancer Binary Classification
## Overview
This capstone project aims to create a binary classification model for breast cancer detection using the provided dataset. The dataset contains various features related to breast cancer tumors, and the goal is to develop a model capable of distinguishing between malignant and benign tumors.

## Dataset
The dataset used for this project is the Breast Cancer dataset, which includes a set of features derived from clinical measurements. The target variable is binary, indicating whether a tumor is malignant (1) or benign (0). The dataset is provided in a CSV format.

## Project Objectives
Exploratory Data Analysis (EDA):

1. Explore the dataset to understand its structure and characteristics.
- Perform data scaling to standardize the features.
- Implement Principal Component Analysis (PCA) to reduce dimensionality.
- Address the issue of class imbalance, if present.
2. Data Splitting:
- Split the dataset into training, validation, and test sets.
3. Cross-Validation:
- Implement 10-fold cross-validation to ensure robust model evaluation.
4. Classification Models:
- Compare the performance of various classification algorithms:
	- Logistics Regression
	- K-Nearest Neighbors (KNN)
	- Support Vector Machine (SVM)
	- Random Forest (RF)
	- XGBoost
5. Evaluation Metrics:
- Evaluate the models using the following metrics:
	- ROC-AUC (Receiver Operating Characteristic - Area Under the Curve)
	-Accuracy
	-F1 Score
##Conclusion
This capstone project provides a comprehensive exploration of the breast cancer dataset, develops a binary classification model using multiple algorithms, and assesses their performance using various evaluation metrics. The goal is to create an accurate and reliable model for breast cancer detection