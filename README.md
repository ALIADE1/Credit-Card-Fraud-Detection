# Credit Card Fraud Detection
https://www.kaggle.com/code/a7lia8del/credit-card-fraud-detection


## Overview
This project focuses on detecting fraudulent credit card transactions using machine learning models. Given the highly imbalanced nature of the dataset, specific preprocessing techniques are applied to improve model performance.

## Dataset
The dataset used is the "Credit Card Fraud Detection" dataset, which consists of anonymized transaction details, including numerical features extracted using PCA and a binary target variable (0 = legitimate, 1 = fraud).

## Steps in the Notebook

### 1. Data Loading and Libraries
- Load the dataset using `pandas`.
- Import necessary libraries such as `numpy`, `matplotlib`, and `seaborn` for analysis and visualization.
- Handle class imbalance using `imblearn` techniques like `RandomUnderSampler`.

### 2. Data Preprocessing
- Apply `StandardScaler` and `RobustScaler` to normalize transaction amounts and features.
- Split the dataset into training and testing sets.

### 3. Modeling
- Implement multiple classification models:
  - **Logistic Regression**
  - **Random Forest Classifier**
  - **XGBoost Classifier**
- Train models on the processed dataset.

### 4. Evaluation
- Assess model performance using:
  - **Accuracy Score**
  - **Classification Report**
  - **Confusion Matrix**
- Use visualization techniques to analyze fraud detection efficiency.
