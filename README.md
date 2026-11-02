# HR-Workforce-Attrition-Dashboard

HUMAN RESOURCES
Workforce & Attrition Dashboard — Analysis Report
Source: 08_hr_attrition.csv · 1,600 employees
Prepared by: Arunabha Lahiri
Report type: Dashboard analysis & insights summary
Companion to: portfolio dashboard build
Executive Summary
Across 1,600 employees, overall attrition rate is 23.8%, with average tenure of 4.6 years and average monthly income of $6.6K. The clearest single driver identified is overtime: employees working overtime leave at 35.5% versus 18.8% for those who don't — a gap of 16.7%. Early-tenure employees (under 2 years) also show elevated risk at 33.0%, well above the company-wide average. High performers are not disproportionately leaving (22.8% attrition vs. 23.8% overall), which is a reassuring finding — the company is not preferentially losing its strongest people.
Detailed Analysis
1. Attrition by Department
Attrition rate by department: Data & Analytics: 25.9%, Research & Development: 25.2%, Finance: 24.4%, IT: 24.0%, Human Resources: 21.7%, Sales: 21.7%. Data & Analytics runs highest at 25.9%, while Sales is lowest at 21.7%.
The spread between departments (roughly 4.3 percentage points) is moderate rather than extreme, suggesting attrition drivers are more behavioral/role-based (overtime, tenure, satisfaction) than department-specific.
2. Overtime & Work-Life Balance
This is the strongest single relationship in the dataset: overtime workers leave at 35.5% versus 18.8% for non-overtime employees, a gap of 16.7%. This is the single most actionable retention lever identified in this analysis.
Recommendation: audit overtime distribution — is it concentrated in a few roles/teams, or spread broadly? Targeted workload rebalancing there would likely have the largest retention impact of any intervention tested here.
3. Tenure-Band Risk
Attrition by tenure: 0-1 yrs: 33.0%, 2-4 yrs: 20.5%, 5-9 yrs: 20.2%, 10+ yrs: 15.7%. Risk is clearly concentrated in the 0-1 year band at 33.0%, roughly double the rate seen in tenured employees (10+ years, 15.7%). This is a classic early-tenure risk curve.
Recommendation: strengthen onboarding and 90-day check-ins, since the largest single attrition risk window is an employee's first year.
4. Satisfaction, Performance & Pay
Attrition drops sharply once job satisfaction reaches level 3 or 4: employees at satisfaction level 1 or 2 leave at 35.9% on average, compared to roughly 17.3% for satisfaction level 3-4 — satisfaction is a meaningfully predictive signal.
By department, average monthly income ranges from $6.3K to $7.0K — pay does not obviously track with the departments showing highest attrition, suggesting compensation alone is not the primary driver here relative to overtime and tenure.
Key Recommendations
1. Address overtime load first — it shows the largest attrition gap in the analysis (16.7%).
2. Strengthen first-year onboarding and manager check-ins, since 0-1 year tenure is the highest-risk band.
3. Investigate Data & Analytics's elevated attrition specifically, though the department effect is secondary to overtime and tenure.
4. Continue monitoring job-satisfaction scores as a leading indicator — the sharp drop in attrition above satisfaction level 2 makes it a useful early-warning signal.
Data & Methodology Notes
This dataset is synthetically generated for portfolio purposes; attrition, satisfaction and income figures are randomly distributed and do not reflect a real company's workforce. A production version of this analysis would also incorporate exit-interview themes and manager-level attrition clustering, which are not available in this dataset.
Methodology: figures in this report are computed directly from the underlying row-level dataset (not estimated), using the same aggregation logic as the DAX measures defined for the companion dashboard, so the numbers here should reconcile with the dashboard's KPI cards and charts.
