## Overview
This project builds a churn prediction model for fintech investment platforms like Carry (getcarry.com). The goal is to identify users who have deposited capital but are at high risk of leaving before making an investment — enabling advisory teams to intervene proactively.

## Key Findings
- 20.4% churn rate across 10,000 users
- Inactive users churn at nearly 2x the rate of active users
- Highest risk users: older (avg. 44), high balance ($91K+), low product engagement
- Final model: Random Forest with 84% accuracy and 59% churn recall

## Tools & Methods
- Python (pandas, scikit-learn, seaborn, matplotlib)
- Logistic Regression → SMOTE balancing → Random Forest
- Churn risk scoring table with High/Medium/Low tiers

## Files
- `carry_dormant_capital.ipynb` — full analysis notebook
- `carry_churn_data.csv` — dataset
- `carry_risk_scores.csv` — output risk scoring table
