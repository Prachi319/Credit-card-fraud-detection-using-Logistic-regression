# 💳 Credit Card Fraud Detection

This project focuses on building a machine learning model to detect fraudulent credit card transactions. The dataset is highly imbalanced and contains anonymized features, making it an ideal challenge for applying data preprocessing, feature engineering, and model evaluation techniques.

## 📂 Dataset

The dataset used is publicly available on Kaggle:
👉 [Credit Card Fraud Detection Dataset on Kaggle]
"https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud"

It contains transactions made by European cardholders in September 2013. The dataset presents transactions that occurred over two days, with 492 frauds out of 284,807 transactions — highlighting the class imbalance.

## 📊 Features

- **Time**: Seconds elapsed between each transaction and the first transaction
- **V1–V28**: PCA-transformed features for confidentiality
- **Amount**: Transaction amount
- **Class**: Target variable (0 = Not Fraud, 1 = Fraud)

## 🧠 Techniques Used

- Exploratory Data Analysis (EDA)
- Data Cleaning & Preprocessing
- Feature Scaling
- Handling Imbalanced Data (e.g. Undersampling)
- Logistic Regression
- Model Evaluation Metrics: Accuracy

## 🛠️ Tools & Libraries

- Python
- pandas, NumPy
- scikit-learn
- imbalanced-learn 
- matplotlib, seaborn
- Logistic Regression


