# Task 4 — Executive Analytics Capstone

## Objective
Combine the customer churn analysis into a concise executive story for a nontechnical decision-maker.

## Decision question
Which customer groups should a fictional subscription team contact first to reduce avoidable churn?

## Executive result
- Customers: 15
- Observed churn: 46.7% (7 of 15)
- Retention: 53.3%
- Observed monthly revenue at risk: ₹409.93
- Average tenure: 18.8 months
- Median tenure: 15 months
- Priority segment: Month-to-Month + 3 or more support tickets
- Priority segment size: 7 customers
- Priority segment observed churn: 100%

## Five decision-relevant insights
1. Month-to-Month customers: 7/7 churned in this sample.
2. Month-to-Month customers average 4.3 support tickets, versus 1.5 for One Year and 0.5 for Two Year.
3. Basic customers show 71.4% observed churn (5/7).
4. UPI shows 75% observed churn (3/4); Debit Card shows 100% (2/2), but both groups are small.
5. A transparent 0–6 prioritization score places 7 customers in High risk and 8 in Low risk; all observed churn is in High risk.

## Expected impact scenario
A planning scenario of preventing 25%–50% of the observed churn pool implies approximately ₹102.48–₹204.97 monthly gross run-rate protection, or ₹1,229.79–₹2,459.58 annualized if retained for 12 months.

This is **not a forecast** and does not establish causal impact.

## Limitations
- 15 synthetic customers only.
- Observational data; no causal inference.
- Risk score is a prioritization index, not a churn probability.
- No randomized retention experiment.
- One observation period.

## Files
- `dashboard.html` — dashboard from Task 2
- `Business_KPI_Dashboard.xlsx` — dashboard workbook
- `customer_churn_sample.csv` — supplied source dataset
- `Executive_Analytics_Capstone.pdf` — executive PDF
- `Executive_Analytics_Capstone.pptx` — executive presentation
- `presentation_recording_script.md` — 3-minute recording script

## Submission
Submit the public/view-only GitHub repository URL. Keep this folder inside the same internship repository so one link contains the supporting files.

## Important wording
The analysis is descriptive. Avoid saying that contract type, support tickets, payment method, or subscription type *causes* churn.
