# Credit-Risk-Scoring-Model
Project Objective
To develop a Credit Risk Scoring Model that predicts the likelihood of borrower default using historical lending data.
The project calculates the Probability of Default (PD) for each borrower, evaluates model performance using ROC curves, and generates classification reports for two algorithms: Logistic Regression and Random Forest.
Methodology
1.Load Lending Dataset - Features include income, loan amount, credit score, age, and default history.
2.Preprocess Data - Handle missing values, normalize/scale features if needed.
3.Split Dataset - 70% training set, 30% testing set.
Model Building - Train Logistic Regression and Random Forest classifiers.
PD Calculation - Extract model-predicted probabilities as borrower PD values.
Model Evaluation - Compute ROC Curve and AUC for both models , Generate classification reports and confusion matrices.
Visualization - Plot ROC curves for model comparison , Display PD distributions.
ROC Curve Comparison
Logistic Regression AUC = 0.82
Random Forest AUC = 0.88
Classification Report – Logistic Regression
Precision: 0.78
Recall: 0.70
F1-score: 0.74
Classification Report – Random Forest
Precision: 0.81
Recall: 0.75
F1-score: 0.78
Conclusion
This project demonstrates the practical application of statistical and machine learning models to credit risk analysis.
By predicting borrower PD and comparing algorithm performance, lenders can better identify high-risk customers, reduce default rates, and optimize lending decisions.
The ROC and classification reports provide clear insights into model accuracy and trade-offs, supporting better credit policy design.
