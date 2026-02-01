# WellCo Churn Reduction — Data Science Assignment

## Overview
WellCo is experiencing increased member churn and seeks to reduce it through targeted outreach.  
This repository contains an end-to-end, reproducible data science solution that identifies **which members to prioritize for outreach** and determines the **optimal outreach size (`n`)**, balancing impact and cost.

The final output is a **ranked list of members** based on their predicted churn risk, enabling WellCo to allocate outreach efforts efficiently.

---

## Problem Framing
This problem is framed not only as a churn prediction task, but as a **prioritized intervention problem**.

Key questions addressed:
- Which members are most likely to churn?
- Which members should be contacted first?
- How many members should receive outreach before marginal benefit diminishes?

Outreach is assumed to have a constant (but unknown) marginal cost, making **ranking and cutoff selection** critical.

---

## Data
### Training Data
- `web_visits.csv`
- `app_usage.csv`
- `claims.csv`
- `churn_labels.csv`

### Test Data
- `test_web_visits.csv`
- `test_app_usage.csv`
- `test_claims.csv`
- `test_members.csv`

Additional reference files:
- `wellco_client_brief.txt`
- Schema documentation (`schema_*.md`)

All feature engineering and model evaluation are performed on the training data and applied consistently to the test data.

---

## Feature Engineering
- TODO
  
---

## Modeling Approach
### Target
- Binary churn label (`1 = churned`, `0 = retained`)

### Models
- TODO

### Evaluation Metrics
- TODO

These metrics emphasize **ranking quality**, which is essential for outreach prioritization.

---

## Outreach Strategy & Selecting `n`
TODO

---

## Final Output
TODO
