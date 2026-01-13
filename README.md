# Fraud Detection using Machine Learning

## Project Overview
This project implements an end-to-end fraud detection system using machine learning
on large-scale financial transaction data.

## Dataset
- 6.3M+ financial transactions
- Highly imbalanced fraud data
- Target variable: isFraud  
⚠️ Dataset not uploaded due to large size.

## Technologies Used
- Python
- Pandas, NumPy
- Scikit-learn
- SMOTE (imbalanced-learn)
- XGBoost
- Matplotlib, Seaborn

## Methodology
1. Data preprocessing & feature engineering
2. Handling class imbalance using SMOTE
3. Logistic Regression as baseline model
4. XGBoost as final model
5. Evaluation using ROC-AUC, Confusion Matrix & Recall
6. Threshold tuning for business use-case
7. Feature importance analysis

## Results
- XGBoost ROC-AUC ≈ 0.999
- High fraud recall ensuring minimal fraud leakage

## How to Run
```bash
pip install -r requirements.txt
# Author -GINNI CHAUDHARY
