# HR Attrition Dashboard (Power BI)

## Business question
Which factors (overtime, pay, job satisfaction, age, department) are most associated with employee attrition, and where should HR focus retention efforts?

## Dataset
IBM HR Analytics Employee Attrition & Performance (sample dataset, 1,470 employees, 35 columns). This is a fictional dataset, so the results illustrate the analysis method rather than a real company.

## Tools
- Power BI Desktop
- Power Query (data cleaning and new columns)
- DAX (measures)

## What I did
1. Cleaned the data in Power Query: removed constant columns, set data types, created an Attrition Flag and Age Group column.
2. Created an Income Band column in DAX.
3. Wrote DAX measures: Total Employees, Attrition Count, Attrition Rate %, Avg Monthly Income and Avg Years at Company.
4. Built a one-page dashboard with KPI cards and five charts, plus a findings and recommendations page.

## Dashboard
![Dashboard](Screenshot%202026-10-08%20222030%20HR.png)

## Key findings
- Overall attrition is 16.1% (237 of 1,470 employees).
- **Overtime** is the strongest driver: 30.5% attrition for employees working overtime vs 10.4% for those who don't.
- **Pay:** employees earning under $3k left at 28.6%, vs 8.9% for those earning $10k+.
- **Job satisfaction:** the lowest score had 22.8% attrition vs 11.3% for the highest.
- **Age:** employees under 30 had 27.9% attrition vs 9.7% for ages 40-49.
- **Department:** Sales had the highest attrition (20.6%), followed by Human Resources (19.1%) and R&D (13.8%).

## Recommendations
1. Review overtime workloads and rebalance hours in the highest-risk teams.
2. Benchmark pay for roles under $3k and consider targeted pay or progression changes.
3. Run regular satisfaction check-ins and act on low scores early.
4. Build mentoring and career pathways for employees under 30.
5. Investigate why Sales turnover is high (targets, workload, management).

![Recommendations](Screenshot%202026-10-08%20222054%20HR.png)

## Files
- `HR_Attrition_Dashboard.pbix`: Power BI report
- `HR_Attrition_Dashboard.pdf`: PDF export
- `WA_Fn-UseC_-HR-Employee-Attrition.csv`: source data

## Notes
These findings show associations, not proof of cause. Next steps could include a statistical test or a predictive model.
