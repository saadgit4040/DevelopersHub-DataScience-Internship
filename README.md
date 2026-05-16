# DevelopersHub Corporation — Data Science & Analytics Internship

> Completed intital 5 tasks for the DevelopersHub Corporation Data Science Internship Program.

---

## Tasks Overview

| # | Task | Dataset | Model Type | Key Metric |
|---|------|---------|------------|------------|
| 1 | Iris Dataset Exploration | Iris (seaborn) | EDA / Visualization | — |
| 2 | Credit Risk Prediction | Loan Prediction | Logistic Regression, Decision Tree | Accuracy, Confusion Matrix |
| 3 | Customer Churn Prediction | Churn Modelling | Random Forest | Accuracy, ROC-AUC |
| 4 | Insurance Claim Prediction | Medical Cost Personal | Linear Regression, Random Forest | MAE, RMSE, R² |
| 5 | Personal Loan Acceptance | Bank Marketing | Logistic Regression, Decision Tree, Random Forest | Accuracy, ROC-AUC |

---

## Task 1: Exploring and Visualizing the Iris Dataset
**Objective:** Load, inspect, and visualize the Iris dataset to understand feature distributions and relationships.  
**Approach:** Used pandas for data inspection and seaborn/matplotlib for scatter plots, histograms, box plots, and a correlation heatmap.  
**Results:** Petal length and petal width are the most discriminating features. Setosa is cleanly separable; Versicolor and Virginica overlap in sepal space.

---

## Task 2: Credit Risk Prediction
**Objective:** Predict whether a loan applicant will default.  
**Approach:** Cleaned missing data using mode/median imputation. Encoded categorical features. Trained Logistic Regression and Decision Tree classifiers.  
**Results:** Both models achieve ~80%+ accuracy. Credit history is the strongest predictor of loan approval.

---

## Task 3: Customer Churn Prediction
**Objective:** Identify bank customers likely to leave.  
**Approach:** Encoded Geography (One-Hot) and Gender (Label Encoding). Trained Logistic Regression, Decision Tree, and Random Forest. Analyzed feature importances.  
**Results:** Random Forest achieved best AUC. Age, NumOfProducts, and IsActiveMember are top churn drivers. German customers churn most.

---

## Task 4: Predicting Insurance Claim Amounts
**Objective:** Estimate medical insurance charges based on personal data.  
**Approach:** Trained Linear Regression, Ridge Regression, and Random Forest Regressor. Evaluated with MAE, RMSE, and R².  
**Results:** Random Forest outperformed linear models (R²≈0.88). Smoking status is the single most impactful feature — smokers pay 3–4× more.

---

## Task 5: Personal Loan Acceptance Prediction
**Objective:** Predict which customers will accept a personal loan offer.  
**Approach:** Performed EDA on age, income, education, and CD account. Trained Logistic Regression, Decision Tree, and Random Forest. Extracted business insights by customer segment.  
**Results:** Random Forest achieved ~90% accuracy and AUC > 0.95. Income and CD Account are the top predictors. Recommendation: target high-income CD account holders.

---

## Tech Stack
- **Language:** Python 3
- **Platform:** Google Colab
- **Libraries:** pandas, numpy, matplotlib, seaborn, scikit-learn



## Repository Structure
```
├── Task1_Iris_Exploration.ipynb
├── Task2_Credit_Risk_Prediction.ipynb
├── Task3_Customer_Churn_Prediction.ipynb
├── Task4_Insurance_Claim_Prediction.ipynb
├── Task5_Loan_Acceptance_Prediction.ipynb
└── README.md
```
