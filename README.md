![Financial Impact of Fraud Detection](https://github.com/Rohi-16/credit-card-fraud-risk-analysis/blob/main/graph3.png)
# Credit Card Fraud Risk Analysis

An end-to-end fraud analytics project focused on detecting fraudulent credit card transactions and translating model predictions into financial risk insights.

## Project Objective

The goal was to evaluate fraud detection models while balancing:
- Fraud detection
- False alerts
- Model precision and recall
- Financial exposure from detected and missed fraud

## Tools & Techniques

- **Python:** Pandas, NumPy, Matplotlib, Seaborn
- **Machine Learning:** Scikit-learn
- **Data Analysis:** Exploratory analysis, correlation analysis, class imbalance analysis
- **Models:** Logistic Regression, Class-Weighted Logistic Regression, Random Forest
- **Evaluation:** Precision, Recall, F1-Score, PR-AUC, Confusion Matrix
- **Risk Analysis:** Probability threshold optimization and financial impact analysis

## Key Results

- Random Forest PR-AUC: **0.806**
- Selected probability threshold: **0.20**
- Precision: **93.67%**
- Recall: **77.89%**
- F1-Score: **85.06%**
- Fraud transactions detected: **74 / 95**
- False alerts: **5**
- Fraud value detection rate: **72.71%**
- Detected fraud value: **$10,736**
- Missed fraud value: **$4,030**

## Key Insight

The project demonstrates why fraud detection should not be evaluated using accuracy alone. Threshold selection creates a trade-off between detecting more fraud and generating unnecessary alerts, while financial-value analysis shows the monetary impact of model decisions.

## Dataset

[Credit Card Fraud Dataset – Kaggle](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud)

## Notebook

The complete analysis and modeling workflow is available in the Jupyter notebook included in this repository.
