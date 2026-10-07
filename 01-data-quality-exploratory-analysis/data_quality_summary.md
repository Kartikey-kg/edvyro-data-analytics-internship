# Customer Churn — Data Quality Summary

## Dataset profile
- **Records:** 15
- **Columns:** 11
- **Overall churn:** 46.7%
- **Dataset type:** Synthetic practice dataset

## Audit results
- Missing values: **0**
- Duplicate full rows: **0**
- Duplicate CustomerID values: **0**
- Invalid categories: **None found**
- Impossible numeric values: **None found**
- IQR-defined numeric outliers: **None found**
- `TotalCharges` consistency check: **Passed**

### IQR details
- **Age:** Q1=30.00, Q3=47.00, IQR=17.00, bounds=4.50 to 72.50, outliers=0
- **TenureMonths:** Q1=7.00, Q3=27.00, IQR=20.00, bounds=-23.00 to 57.00, outliers=0
- **MonthlyCharges:** Q1=49.99, Q3=114.99, IQR=65.00, bounds=-47.51 to 212.49, outliers=0
- **TotalCharges:** Q1=449.91, Q3=3209.73, IQR=2759.82, bounds=-3689.82 to 7349.46, outliers=0
- **SupportTickets:** Q1=1.00, Q3=4.00, IQR=3.00, bounds=-3.50 to 8.50, outliers=0

## Cleaning decisions
No records were removed or imputed. The dataset is already analysis-ready under the documented rules. Keeping all 15 records preserves reproducibility and avoids silently deleting inconvenient observations.

## Initial exploratory patterns
1. Month-to-month contracts show the strongest observed churn pattern.
2. Higher support-ticket counts are associated with higher observed churn.
3. Shorter-tenure customers are also worth monitoring.
4. These are descriptive associations only; they do not establish causation.
5. With only 15 synthetic customers, percentages have substantial uncertainty.

## Recommended first audience
**Month-to-month customers with 3+ support tickets.**

- Segment size: **7**
- Churned: **7**
- Observed churn rate: **100.0%**
- Overall churn rate: **46.7%**

### Decision
Prioritize a retention/support follow-up for this segment.

### Uncertainty
The sample is small and synthetic. A 100% observed segment churn rate should not be generalized to the broader customer population.

### Next measurement
Track retention after outreach and compare the contacted segment with an appropriate comparison group using a larger dataset.
