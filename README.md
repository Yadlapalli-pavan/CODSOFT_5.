# 💳 Credit Card Fraud Detection 
**#📌 Project Overview**
This project builds a Machine Learning model to detect fraudulent credit card transactions.

Credit card fraud detection is a highly imbalanced classification problem because fraudulent transactions are very rare compared to normal transactions.
The goal of this project is to:

      Analyze the dataset
      Handle imbalanced data
      Train multiple ML models
      Compare their performance
      Identify the best performing model
**#📂 Dataset**
The dataset used is the Credit Card Fraud Detection dataset from Kaggle.
Contains transactions made by European cardholders
Highly imbalanced:
0 → Non-Fraud
1 → Fraud
Fraud cases are less than 1% of total transactions
**Models Used**
1. Logistic Regression
2. Decision Tree
3. Random Forest
4. Gradient Boosting

**Model Comparison (Typical Results):**
┌──────────────────────┬──────────┬─────────┬──────────┐
│ Model                 │ ROC AUC  │ PR AUC  │ Accuracy │
├──────────────────────┼──────────┼─────────┼──────────┤
│ Random Forest         │ 0.95     │ 0.85    │ 0.999    │
│ Gradient Boosting     │ 0.94     │ 0.82    │ 0.999    │
│ Logistic Regression   │ 0.92     │ 0.78    │ 0.999    │
│ Decision Tree         │ 0.90     │ 0.75    │ 0.999    │
└──────────────────────┴──────────┴─────────┴──────────┘

**Conclusion**

This project demonstrates a complete end-to-end Machine Learning pipeline for fraud detection — from data exploration to model evaluation and comparison.

