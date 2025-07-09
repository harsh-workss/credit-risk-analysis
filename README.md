# Credit Risk Analysis 🧠📊

This project focuses on analyzing and predicting customer delinquency risk using financial data. It was developed as part of a data analytics internship and includes exploratory data analysis (EDA), feature engineering, and a conceptual predictive modeling framework using machine learning tools.

## 📁 Dataset Overview

- **Records:** 500 customer records
- **Features:** 19 financial and behavioral attributes, including:
  - Age, Income, Credit Score
  - Credit Utilization, Missed Payments
  - Employment Status, Debt-to-Income Ratio
  - Monthly Payment History (Month_1 to Month_6)
- **Target Variable:** `Delinquent_Account` (0 = Not Delinquent, 1 = Delinquent)

## 🧪 Techniques Used

- **EDA:** Identified patterns, anomalies, and key risk indicators.
- **Data Cleaning:** Handled missing values via imputation (mean/median).
- **Visualization:** Matplotlib and Seaborn for pattern detection.
- **Model Planning:** Logistic Regression chosen for explainability and risk transparency.

## 🚩 Key Insights

- High Credit Utilization (> 0.6) and low Credit Score (< 450) are strong delinquency signals.
- Customers with high Debt-to-Income Ratio and frequent missed payments are more likely to default.
- Some high-income customers still defaulted — indicating behavioral risk.

## 🧠 Tools & Libraries

- Python
- Pandas & NumPy
- Scikit-learn (for modeling logic)
- Matplotlib & Seaborn (for visualization)
- Jupyter Notebook

## 📝 Report & Summary

This project was completed as part of a GenAI Data Analytics Virtual Internship by Tata iQ. Full EDA Summary Report and modeling plan are available in the repository.
