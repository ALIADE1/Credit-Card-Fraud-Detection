Credit Card Fraud Detection
📖 Description
This project involves detecting fraudulent transactions in credit card data. Using machine learning techniques, we explore the dataset, preprocess the data, and apply models to identify potential fraud cases. The project aims to address class imbalance and improve model accuracy through techniques like SMOTE and hyperparameter tuning.

🛠️ Key Features
Exploratory Data Analysis (EDA):
Visualized class imbalance using heatmaps, boxplots, and pie charts.
Analyzed the correlation between features to detect patterns.
Preprocessing:
Used SMOTE for oversampling the minority class (fraudulent transactions).
Cleaned the data by handling missing values and duplicates.
Models:
Random Forest: Achieved balanced performance with good precision (0.89) and recall (0.77).
XGBoost: Achieved 99.89% accuracy with strong recall for fraud (0.80) and precision (0.63).
Logistic Regression: Accuracy of 98.35%, though struggles with fraud detection due to low precision.

📊 Results
Best Model: XGBoost
Accuracy: 99.89%
Precision for Fraud: 0.63
Recall for Fraud: 0.80
ROC-AUC: 0.90

🧠 Technologies Used
Python, Pandas, NumPy
Scikit-learn, XGBoost
Matplotlib, Seaborn

