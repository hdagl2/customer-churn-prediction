# customer-churn-prediction

# Customer Churn Prediction with Explainable AI

[View Live Tableau Dashboard 🔗](https://public.tableau.com/views/customer-churn-prediction/CustomerChurnDashboard?:language=en-US&publish=yes&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link)

## Project Overview

This project uses machine learning and explainable AI to predict customer churn, understand the drivers behind churn, and communicate insights through an interactive Tableau dashboard.

## Goals

- Predict customer churn using logistic regression
- Use SHAP values for explainability
- Build an interactive dashboard for business stakeholders

## Tools Used

| Category      | Tools/Technologies                     |
|---------------|----------------------------------------|
| Modeling      | Python (pandas, scikit-learn)          |
| Explainability| SHAP                                   |
| Dashboard     | Tableau Public                         |
| Hosting       | Tableau Public Link                    |

## Dashboard Features

- Churn rates by contract type
- Heatmap of churn risk by tenure and monthly charges
- Distribution of predicted churn probabilities
- KPI cards: total customers, churn %, avg tenure
- Filterable by contract type, senior citizen status, and more

## Files

| File Name                 | Description                                      |
|---------------------------|--------------------------------------------------|
| WA_Fn-UseC_-Telco-Customer-Churn 2.csv| Raw data with model predictions                 |
| churn_with_predictions.csv   | Cleaned dataset for Tableau                      |
| customer-churn-prediction.twbx | Packaged Tableau dashboard (exported workbook)  |

## Business Insights

- **Month-to-month contracts** show the highest churn rate
- Customers with **low tenure** and **high monthly charges** are more likely to churn
- Retention efforts should focus on these segments

---

## How to Use

1. Open the `.twbx` file in Tableau Desktop or Tableau Public
2. Explore filters and visuals
3. Connect your own data to replicate or extend the project

---

