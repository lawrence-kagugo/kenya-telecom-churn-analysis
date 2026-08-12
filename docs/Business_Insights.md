# Business Insights — Kenya Telecom Customer Churn Analysis

Synthesized from Exploratory Data Analysis (Step 8) and Statistical Analysis (Step 9).
Each insight below is backed by evidence and statistically validated (p<0.05) unless noted otherwise.

## 1. Contract structure is the strongest actionable lever
Contract structure is the strongest actionable lever identified in the analysis.
Month-to-month customers churn at nearly twice the rate of 24-month customers
(26.7% vs 14.2%), and the relationship is statistically significant
(χ²=100.0, p<0.0001), indicating that contract design should be a central
component of the company's retention strategy.

## 2. The first six months are the critical retention window
Churn is extremely high among customers in their first 6 months (49.4%) and
declines sharply with tenure (t=23.5, p<0.0001) — the strongest statistical
relationship found in this analysis. Retention resources should be
concentrated heavily on early-stage customers rather than spread evenly
across the customer base.

## 3. Disengagement and dissatisfaction provide measurable warning signals
Churned customers consistently show lower engagement and satisfaction across
seven independent metrics, with all differences statistically significant
(p<0.0001). This suggests these measures can help identify customers at risk
before churn occurs, rather than only explaining it after the fact.

## 4. Churn rate and financial exposure tell different stories
Government has the highest churn rate (37.3%), while Corporate has the
greatest CLV lost (KES 48.9M) - both relationships statistically confirmed
(χ²=147.9, p<0.0001 for segment association). Retention strategy should
weigh both churn probability and customer value, not rate alone.

## Notes on findings NOT included as insights

**Billing behavior:** No statistically significant relationship was found
between billing metrics (LatePayments p=0.118, OutstandingBalance p=0.060)
and churn. This is evidence of absence of a detectable effect in this
dataset, not proof that billing is irrelevant to churn generally.

**ChurnRiskScore:** Shows a statistically meaningful, directionally correct
relationship with churn (clear separation between churned/retained
distributions). However, this analysis only tested descriptive association,
not predictive performance - actual deployment as a targeting tool would
require formal classification validation (precision, recall, ROC-AUC,
out-of-sample testing), which is outside the scope of this analysis.
