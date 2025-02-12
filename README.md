# Description:-
https://www.kaggle.com/code/a7lia8del/credit-card-fraud-detection

This notebook provides a comprehensive approach to **Credit Card Fraud Detection** by applying data preprocessing, visualization, and machine learning techniques.

## Key Steps

### Data Analysis
- Investigates the dataset to understand the class imbalance and identifies fraudulent and valid transactions.
- Uses descriptive statistics to summarize the "Amount" feature for fraudulent and valid transactions.

### Data Visualization
- Heatmaps to analyze feature correlations.
- Boxplots for feature distribution and outlier detection.
- Pie charts to visualize the total amounts for fraud and valid transactions.

### Data Preprocessing
- Removes duplicates and cleans the data.
- Applies **SMOTE** to oversample the minority class (fraudulent transactions).

### Modeling
- Trains multiple machine learning models:
  - **Random Forest Classifier**
  - **Logistic Regression**
  - **XGBoost Classifier**
- Models are tuned with relevant hyperparameters and evaluated on a test set.

### Evaluation Metrics
- Confusion matrices and heatmaps to assess model predictions.
- Key metrics: **accuracy**, **precision**, **recall**, **F1-score**, and **ROC-AUC score**.
