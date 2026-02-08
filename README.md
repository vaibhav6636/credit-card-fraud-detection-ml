# Credit Card Fraud Detection Using Statistical and Machine Learning Techniques

## 📌 Project Overview
This project focuses on detecting fraudulent credit card transactions using statistical analysis and machine learning models. The study combines behavioral analysis, time-based statistical testing, and predictive modeling to identify fraud patterns.

## 🎯 Objectives
- Analyze time-based transaction behavior and inter-transaction gaps
- Study merchant category influence on fraud occurrence
- Build and compare machine learning models for fraud detection

## 📊 Dataset
- Source: Kaggle – Credit Card Transactions Fraud Detection Dataset (2019–2020)
- Records: 1,048,575 transactions
- Features include transaction amount, time, merchant details, and customer attributes

## 🔍 Exploratory Data Analysis
- Fraud vs Non-Fraud distribution
- Transaction amount distribution
- Hour-wise and weekday-wise fraud patterns
- Category-wise fraud risk
- Time-gap behavioral analysis

## 📈 Statistical Analysis
- Descriptive statistics of time gaps
- Normality test (Minitab)
- Mann–Whitney U Test confirming significant difference in transaction timing

## 🤖 Machine Learning Models Used
- Logistic Regression (Balanced & SMOTE)
- Random Forest Classifier
- XGBoost Classifier

## 🏆 Best Model
**XGBoost** achieved the best performance with:
- High Recall and Precision for fraud detection
- ROC-AUC showing excellent discrimination capability

## 💡 Key Findings
- Fraud transactions typically involve higher amounts
- Fraud occurs more frequently during late-night hours
- Short time gaps between transactions indicate suspicious behavior
- Merchant category influences fraud probability

## 🚀 Tools & Technologies
Python, Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn, XGBoost, Minitab, MS Excel, Jupyter Notebook

## 📄 Project Report
The complete academic project report is included in this repository.

---

⭐ This project demonstrates the application of statistics and machine learning in solving real-world financial fraud problems.
