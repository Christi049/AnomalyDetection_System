# 🚨 Credit Card Fraud Detection using Isolation Forest

## 📌 Overview
This project implements an **anomaly detection system** to identify fraudulent credit card transactions using **Isolation Forest**.  
Due to extreme class imbalance, fraud detection is treated as an **unsupervised learning problem** rather than traditional classification.

---

## 📊 Dataset
- Link: [Kaggle Dataset](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud)
- Credit Card Transactions Dataset (European cardholders, Sept 2013)
- Total transactions: **284,807**
- Fraud cases: **492 (0.172%)**
- Features:
  - `V1`–`V28`: PCA-transformed numerical features
  - `Time`: Time elapsed since first transaction
  - `Amount`: Transaction amount
  - `Class`:  
    - `0` → Normal  
    - `1` → Fraud

---

## 🧠 Approach
1. Drop `Class` label during training  
2. Scale features using standardization  
3. Train **Isolation Forest** on unlabeled data  
4. Predict anomalies  

---

## ⚙️ Tech Stack
- Python  
- Pandas, NumPy  
- Scikit-learn  
- Google Colab

---

## 📎 Reference
- Kaggle Credit Card Fraud Detection Dataset
- Geeks for geeks what is isolation forest?
