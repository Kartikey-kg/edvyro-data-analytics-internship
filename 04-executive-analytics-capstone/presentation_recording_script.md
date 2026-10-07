# 3-Minute Presentation Recording Script — Task 4

## Slide 1 — Opening (20–25 sec)
“Hello. This is my Executive Analytics Capstone on customer churn.
The decision question is: which customer groups should a subscription team contact first to reduce avoidable churn?
The dataset contains 15 customers. Observed churn is 46.7%, and the monthly revenue associated with churned customers is ₹409.93.”

## Slide 2 — Five key insights (45–50 sec)
“Five findings matter most.
First, all 7 Month-to-Month customers in this sample churned.
Second, that group also has the highest support demand, averaging 4.3 tickets.
Third, Basic customers have the highest subscription-level observed churn at 71.4%.
Fourth, UPI and Debit Card show high churn rates, but their groups are small, so I treat payment method as a secondary signal.
Fifth, a transparent risk score separates 7 high-risk customers from 8 low-risk customers, with all observed churn in the high-risk group.”

## Slide 3 — Revenue risk (25–30 sec)
“The main financial signal is concentration. The observed monthly revenue at risk is ₹409.93, and the Month-to-Month group accounts for all of it in this sample.
That makes a focused retention workflow more reasonable than treating every customer equally.”

## Slide 4 — Recommendation (30 sec)
“My recommendation is for the retention and support team to contact Month-to-Month customers with at least three recent support tickets first.
The team should review unresolved issues, remove blockers, and then test a targeted retention offer.
Payment friction and Basic-plan onboarding can be checked as secondary opportunities.”

## Slide 5 — Expected impact (25–30 sec)
“For planning, if an intervention prevented 25 to 50 percent of the observed churn pool, the monthly run-rate protected would be approximately ₹102.48 to ₹204.97.
This is a scenario range, not a forecast. It assumes the retained customers continue for 12 months at the same monthly charge and ignores costs and future churn.”

## Slide 6 — Limitations (25–30 sec)
“There are important limitations. The dataset has only 15 synthetic customers, so percentages are unstable.
The analysis is observational and does not prove causation.
The risk score is a prioritization index, not a calibrated probability.
There is also no randomized experiment to estimate the true effect of a retention action.”

## Slide 7 — Close (15–20 sec)
“The bottom line is to start narrow with the 7 high-touch Month-to-Month customers, run a measurable pilot, and track 30- and 60-day churn, support tickets, payment friction and retained revenue.
The decision should be expanded only if the next observation period shows improvement.”
