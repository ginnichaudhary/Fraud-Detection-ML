# Fraud Detection using Machine Learning

## 📌 Project Overview
This project implements an end-to-end fraud detection system using machine learning techniques
on large-scale financial transaction data. The objective is to accurately identify fraudulent
transactions while minimizing false negatives, which is critical for real-world financial systems.

---

## 📊 Dataset
- Over **6.3 million financial transactions**
- Highly **imbalanced dataset**
- Target variable: `isFraud`

⚠️ **Note:**  
The original dataset is not included in this repository due to size limitations.
It can be shared separately upon request.

---

## 🛠️ Technologies & Tools
- **Python**
- **Pandas, NumPy**
- **Scikit-learn**
- **SMOTE (imbalanced-learn)**
- **XGBoost**
- **Matplotlib, Seaborn**
- **Jupyter Notebook**

---

## 🧠 Methodology
1. Data cleaning and preprocessing
2. Feature engineering (transaction amount, balance differences, transaction types)
3. Handling class imbalance using **SMOTE**
4. Baseline model: **Logistic Regression**
5. Advanced model: **XGBoost Classifier**
6. Model evaluation using:
   - ROC-AUC
   - Confusion Matrix
   - Precision, Recall, F1-score
7. Threshold tuning based on business use-case
8. Feature importance analysis

---

## 🚀 Results
- **Logistic Regression ROC-AUC:** ~0.98
- **XGBoost ROC-AUC:** ~0.999
- Achieved **high fraud recall**, reducing the risk of missing fraudulent transactions

---

## 📈 Key Insights
- Fraudulent transactions are more frequent in **TRANSFER** and **CASH_OUT** types
- Sudden balance changes and high transaction amounts are strong fraud indicators
- Class imbalance handling significantly improves fraud detection performance

---

## ▶️ How to Run the Project
1. Install required libraries:
   ```bash
   pip install -r requirements.txt


