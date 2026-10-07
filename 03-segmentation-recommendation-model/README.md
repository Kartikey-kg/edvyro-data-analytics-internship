# Task 3 — Segmentation and Recommendation Model

## Objective
Segment customers by behavior and create a transparent rule-based churn-risk score.

## Model
The score uses four explainable signals:
- Month-to-Month contract: +2
- 3+ support tickets: +2
- Tenure ≤6 months: +1
- Monthly charge ≥ sample median (₹79.99): +1

Maximum score: 6.

Risk bands:
- High: 4–6
- Medium: 2–3
- Low: 0–1

The score is a prioritization index, not a probability of churn.

## Segments
- High-touch monthly
- New high-support
- Stable contracted
- High-value support
- Standard

## Recommendation
Prioritize **High-touch monthly** customers for proactive retention/support follow-up.

The dataset is only 15 synthetic records, so the result is uncertain and descriptive. It does not establish causation.

## Files
- `Segmentation_Recommendation_Model.ipynb` — analysis notebook
- `customer_segments_risk_scores.csv` — customer-level segments and scores
- `segment_summary.csv` — segment-level summary
- `risk_band_summary.csv` — risk-band summary
- `recommendation_memo.md` — recommendation memo
- `customer_churn_sample.csv` — source data
