# Crown Industries — B2B Customer Segmentation and Lifecycle Analytics

> Portfolio simulation using synthetic data. This project contains no actual customer, order, financial, or confidential Crown Industries information.

## Business scenario

Crown Industries is modeled as a B2B packaging-machinery manufacturer with a growing account base across the United States. Marketing and sales teams need a practical way to identify high-value relationships, accounts at risk, new customers requiring onboarding, and opportunities for repeat purchases or cross-selling.

## Project objective

Build an account-level CRM analytics framework that answers:

- Which customer segments contribute the most revenue?
- Which high-value accounts require retention or recovery outreach?
- Where are accounts in the customer lifecycle?
- Which CRM action should be assigned to each account?
- How can onboarding, nurture, cross-sell, and win-back campaigns be prioritized?

## Dataset

The synthetic dataset includes:

- 360 B2B customer accounts
- 1,282 orders from January 2024 through June 2026
- Four U.S. regions and five manufacturing subsegments
- Five acquisition channels and five product categories
- Account-level order frequency, cumulative revenue, recency, segment, lifecycle stage, and recommended CRM action

## Analysis approach

Accounts are evaluated using recency, frequency, and monetary value:

| Dimension | Definition |
|---|---|
| Recency | Days between the account's latest order and June 30, 2026 |
| Frequency | Number of orders placed by the account |
| Monetary value | Cumulative account revenue |

The scoring logic assigns accounts to seven actionable segments:

- Champions
- Loyal Growth
- High Value At Risk
- New Accounts
- Promising
- Needs Nurture
- Dormant

Accounts are also classified into five lifecycle stages: New, Active, One-time, At Risk, and Lapsed.

## Portfolio findings

1. Loyal Growth is the largest revenue segment, making expansion and cross-sell programs a priority.
2. Champions generate substantial value and should receive retention, advisory, and advocacy programs.
3. High Value At Risk accounts require coordinated sales recovery based on purchase and service history.
4. New and one-time accounts need structured onboarding and second-order conversion campaigns.
5. At Risk and Lapsed accounts should receive different CRM treatments instead of one generic re-engagement campaign.

## Recommended CRM actions

1. Assign Champions to quarterly business reviews, service-plan cross-sell, and referral development.
2. Contact High Value At Risk accounts within 14 days using product and service history.
3. Use 30-, 60-, and 90-day onboarding sequences to increase second purchases.
4. Separate active-account expansion, churn prevention, and low-frequency win-back journeys.

## Tools and skills demonstrated

- RFM-style customer segmentation
- B2B lifecycle and retention analysis
- Account-level CRM action planning
- Excel formulas, conditional formatting, and native charts
- Executive KPI dashboarding
- Synthetic-data design and documentation

## Files

- `crown-industries-b2b-customer-segmentation.xlsx` — dashboard, segment analysis, account scoring, order history, and methodology
- `crown-industries-segmentation-dashboard.png` — dashboard preview

## Interview explanation

“I built a simulated B2B customer-segmentation framework for a packaging-machinery manufacturer. I analyzed 360 synthetic accounts and 1,282 orders using recency, frequency, monetary value, and lifecycle stage. I then created an Excel dashboard that identifies high-value relationships, at-risk accounts, onboarding needs, and repeat-purchase opportunities. Each account receives a recommended CRM action, connecting the analysis directly to retention, cross-sell, nurture, and win-back campaigns.”
