# Recommendation Memo — Segmentation and Churn-Risk Prioritization

## Decision question
Which customer groups should a fictional subscription team contact first to reduce avoidable churn?

## Approach
A transparent rule-based prioritization score was created using four observable account/behavior signals:

| Signal | Points |
|---|---:|
| Month-to-Month contract | +2 |
| 3+ support tickets in previous 90 days | +2 |
| Tenure ≤ 6 months | +1 |
| Monthly charge ≥ sample median (₹79.99) | +1 |

**Maximum score: 6.**

Risk bands:
- **High:** 4–6
- **Medium:** 2–3
- **Low:** 0–1

The score is a prioritization index, **not a probability of churn** and not a causal model.

## Segments
The segmentation uses transparent business rules:

- **High-touch monthly:** Month-to-Month + 3 or more support tickets
- **New high-support:** ≤6 months tenure + 2 or more support tickets
- **Stable contracted:** One/Two Year contract + 0–1 support tickets
- **High-value support:** Monthly charge at/above the sample median + 2 or more support tickets
- **Standard:** All remaining customers

## Recommendation

### Primary audience
**High-touch monthly customers** should be contacted first.

### Decision
Use proactive support and a retention-oriented follow-up for this group, especially where support issues remain unresolved.

### Supporting metric
The segment contains **7 customers**, and **7 churned** in the supplied sample.

### Secondary audience
Customers in the **High** risk band should receive the next level of attention because they meet multiple transparent risk rules.

## Uncertainty and limitations

- The dataset contains only **15 synthetic customer records**.
- The score weights are business rules chosen for transparency, not statistically estimated coefficients.
- Observed churn rates are unstable with such a small sample.
- The score should not be interpreted as a calibrated probability.
- Correlation/association does not establish causation.

## Next measurement
After outreach, compare retention/churn for contacted customers against an appropriate comparison group. Track:
1. retention rate,
2. churn rate,
3. monthly revenue retained,
4. support-ticket resolution,
5. retention uplift versus the comparison group.

Recalibrate the score only after collecting a substantially larger sample.

## Validation
All customers received exactly one segment, risk band, score, and recommended action. Scores were constrained to 0–6 and customer IDs were checked for duplicates.
