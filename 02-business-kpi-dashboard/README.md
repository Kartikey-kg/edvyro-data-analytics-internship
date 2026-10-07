# Task 2 — Business KPI Dashboard

## Objective
Build a decision-ready dashboard explaining churn, retention, revenue risk, and customer segments.

## Files
- `dashboard.html` — interactive browser dashboard with Contract, Tenure, and Payment Method filters
- `Business_KPI_Dashboard.xlsx` — spreadsheet dashboard and supporting KPI tables
- `customer_churn_cleaned.csv` — analysis-ready dataset
- `README.md` — task documentation

## KPI definitions
- **Churn Rate:** Churned customers / selected customers
- **Retention Rate:** Retained customers / selected customers
- **Revenue at Risk:** Sum of monthly charges from churned customers in the selected population
- **Average Tenure:** Mean completed months since signup

## Full-sample KPI snapshot
- Customers: **15**
- Churn rate: **46.7%**
- Retention rate: **53.3%**
- Monthly revenue at risk: **₹409.93**
- Average tenure: **18.8 months**
- Median tenure: **15.0 months**

## Initial decision insight
Prioritize **Month-to-Month customers with 3+ support tickets** for first retention outreach. In the supplied sample, this segment contains 6 customers and all 6 churned.

This is a small synthetic sample, so the result is uncertain and descriptive. It does not establish that contract type or support tickets cause churn.
