# HR Employee Attrition Analysis
### IBM HR Dataset — 1,470 Employees

## The Business Problem
16.1% of employees are leaving. Every departure costs 
the company 6-9 months of that employee's salary in 
recruiting and training costs.

I wanted to find out: who's leaving, why, and can we 
predict it before it happens?

## What I Found

- **Sales team has highest attrition (20.6%)** — 
  above company average
- **Young employees (18-25) leave at 34.8%** — 
  nearly 1 in 3
- **Overtime workers leave 3x more** (30.5% vs 10.4%)
- **Leavers earn $2,046 less** per month than stayers

## What I Built

- Attrition analysis across Department, Age, Income, Overtime
- Random Forest model predicting attrition with **87.4% accuracy**
- Identified top 10 factors driving employee turnover

## Business Recommendations

1. **Cut overtime in Sales** — highest risk department 
   with highest overtime rate
2. **Review junior salaries** — 18-25 group leaving fastest, 
   likely underpaid
3. **Flag employees earning below $5,000/month** — 
   highest churn risk group

## Tools
Python · Pandas · Scikit-learn · Matplotlib · Seaborn

## Files
- hr_analysis.ipynb
- hr_dashboard.png
- attrition_factors.png
