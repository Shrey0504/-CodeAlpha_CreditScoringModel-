# CodeAlpha_CreditScoringModel-
CodeAlpha - Credit Scoring Model

Objective: Predict whether an individual is creditworthy using their financial history (income, debts, payment history, loan amount, etc.).

Approach: Built and compared three classification models — Logistic Regression, Decision Tree, and Random Forest — after feature engineering (debt-to-income and loan-to-income ratios) and feature scaling.

Results:

Model	Precision	Recall	F1-Score	ROC-AUC
Logistic Regression	0.863	0.792	0.826	0.915
Decision Tree	0.800	0.618	0.698	0.817
Random Forest	0.816	0.773	0.794	0.897

Best model: Logistic Regression gave the strongest overall performance on this dataset, with the highest ROC-AUC (0.915) and F1-Score (0.826).

Tools used: Python, Pandas, NumPy, Scikit-learn, Matplotlib

Internship: CodeAlpha Data Science Internship — Task 1
