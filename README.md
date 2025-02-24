# Credit Card Fraud Detection - Jupyter Notebook
https://www.kaggle.com/code/a7lia8del/credit-card-fraud-detection

## Overview
This Jupyter Notebook explores methods to detect fraudulent credit card transactions while handling the class imbalance issue. It covers data preprocessing, model training, and evaluation.

## Notebook Workflow

### 1. Data Preprocessing
- **Handling Missing Values**: Checked for missing data (none found in this dataset).
- **Feature Scaling**: Applied standardization to the `Amount` feature.
- **Splitting Data**: Divided into training and test sets.

### 2. Handling Imbalanced Data
- **Oversampling**: Synthetic Minority Over-sampling Technique (SMOTE).
- **Undersampling**: Random undersampling of the majority class.
- **Combination Methods**: Using both oversampling and undersampling for better balance.

### 3. Model Training
The notebook trains and compares multiple models:
- **Logistic Regression**
- **Random Forest**
- **Gradient Boosting (XGBoost)**
- **Neural Network (MLPClassifier)**
- **Anomaly Detection Approaches** (e.g., Isolation Forest)

### 4. Model Evaluation
- **Performance Metrics**:
  - Precision, Recall, F1-Score (to assess fraud detection effectiveness)
  - ROC-AUC Score (to measure classifier performance)
  - Confusion Matrix (to analyze correct and incorrect predictions)

### 5. Results & Insights
- **Baseline models** struggled due to class imbalance.
- **SMOTE & cost-sensitive learning** improved recall for fraud detection.
- **Anomaly detection models** provided alternative methods for identifying fraudulent transactions.
