# Recommendations — Kenya Telecom Customer Churn Analysis

Derived from Business Insights (Step 10). Each recommendation includes the
justifying evidence, priority, and how success will be measured.

## Priority Framework
Recommendations 1-3 are ranked by statistical strength and directness of
action. Recommendation 4 (segment targeting) is not ranked against them -
it is a targeting layer applied across all three, determining *who* receives
each intervention first (Government and Corporate customers, given highest
churn rate and highest revenue exposure respectively).

---

## 1. Contract Conversion Campaign — HIGH PRIORITY
**Action:** Launch a targeted 12/24-month conversion offer for month-to-month
customers, using discounted pricing or added benefits to encourage commitment.

**Evidence:** Month-to-month customers churn at ~2x the rate of 24-month
customers (26.7% vs 14.2%, χ²=100.0, p<0.0001).

**Measurement:**
- Leading indicator: 12/24-month conversion rate among targeted customers (3-6 months)
- Outcome check: Subsequent churn rate among converted customers vs. a
  comparable control group who did not receive the offer
- Success criterion: Meaningful conversion uptake AND lower subsequent churn
  vs. control - conversion alone is not sufficient, since a customer can
  convert and still churn later.

## 2. Structured Onboarding Journey (0-6 Months) — HIGH PRIORITY
**Action:** Build a 0-6 month retention journey with proactive check-ins at
30/60/90/180 days, personalized onboarding, and early-retention incentives.

**Evidence:** Churn is 49.4% in months 0-6, declining sharply with tenure
(t=23.5, p<0.0001) - the strongest driver identified in this analysis.

**Measurement:**
- Leading indicator: 90-day engagement/feature-adoption rate among new customers
- Outcome check: 6-month churn rate vs. a control group or pre-campaign baseline

## 3. Early-Warning Trigger System — HIGH PRIORITY
**Action:** Build an automated system flagging customers with declining
usage, feature adoption, NPS, or CSAT for proactive retention outreach.

**Evidence:** Engagement and satisfaction metrics are consistently and
significantly lower among churned customers across 7 independent metrics
(all p<0.0001).

**Measurement:**
- Trigger validity check: Flagged customers should show measurably higher
  churn risk than unflagged customers *before* any intervention (confirms
  the trigger itself is catching real risk, not noise)
- Intervention outcome: Churn rate among flagged customers post-outreach vs.
  a comparable unflagged/control group over the following 3-6 months

## 4. Segment-Weighted Targeting — APPLIED ACROSS ALL THREE
**Action:** Prioritize Government (highest churn rate, 37.3%) and Corporate
(highest CLV lost, KES 48.9M) customers first when rolling out
Recommendations 1-3, rather than treating this as a separate initiative.

**Evidence:** Segment is significantly associated with churn (χ²=147.9,
p<0.0001), and churn rate/financial exposure diverge by segment.

**Measurement:** All KPIs from Recommendations 1-3 broken out by segment
(e.g. conversion rate: Government vs. Corporate vs. other). Success means
the same interventions produce stronger outcomes when targeted at the
highest-risk/highest-value segments.

## Explicitly Not Recommended
**Billing-focused retention outreach:** No statistically significant
relationship was found between billing behavior and churn in this dataset
(p=0.118, p=0.060). Retention budget is better allocated to the four
recommendations above.
