# HR Analytics Dashboard

An interactive **Power BI HR Analytics Dashboard** built to help HR teams understand workforce composition, employee attrition, and the factors associated with employee turnover.

## Dashboard overview

The dashboard provides a consolidated view of employee demographics, compensation, job characteristics, satisfaction, and attrition. It can be used by HR leaders and department managers to:

- Monitor the size and composition of the workforce.
- Compare attrition across departments, age groups, job roles, and salary bands.
- Identify employee groups that may require retention attention.
- Explore the relationship between business travel, job satisfaction, tenure, income, and attrition.
- Support evidence-based workforce planning and retention initiatives.

## Key metrics

The report is based on the employee-level data in [`HR_Analytics-4.csv`](HR_Analytics-4.csv) and includes measures such as:

- Employee headcount
- Attrition count and attrition rate
- Active employees and employees who have left
- Average age and average monthly income
- Department and job-role distribution
- Employee satisfaction and involvement
- Years at company and years since the last promotion
- Business-travel and overtime patterns
- Salary-band distribution

## Insights from the dashboard

The dashboard highlights the following HR patterns:

1. **Attrition is concentrated in specific employee segments.** Early-career employees and employees in lower job levels are more likely to leave than established employees. This makes structured onboarding, career development, and mentoring important retention levers.

2. **Sales and technical/front-line roles require close monitoring.** These roles combine higher operational pressure, customer or production demands, and—in many cases—greater travel requirements. Attrition should therefore be reviewed at role and department level rather than only at company level.

3. **Frequent travel is a notable risk indicator.** Employees who travel frequently show greater exposure to work-life-balance pressure. Flexible scheduling, travel-load reviews, and manager check-ins can help reduce avoidable turnover.

4. **Compensation and career progression matter.** Employees in lower salary bands, lower job levels, or with limited promotion opportunities are important retention-risk groups. Pay-equity reviews and transparent internal mobility paths can address these risks.

5. **Overtime and work pressure are linked to retention risk.** Employees working overtime should be monitored alongside satisfaction, involvement, and tenure. Workforce balancing and workload planning may improve both engagement and retention.

6. **Job satisfaction and the work environment provide actionable signals.** Low satisfaction scores can help HR prioritize targeted interventions such as manager coaching, recognition programs, team-level listening sessions, and workplace improvements.

7. **Distance from home can add to employee strain.** Long commutes may compound the effects of overtime and frequent travel. Hybrid-work options or location-aware staffing policies may be useful where feasible.

> These insights describe patterns visible in the dashboard data. They should be treated as signals for further investigation, not as proof that any single factor causes attrition.

## Recommended actions

- Create a retention plan for early-career and lower-job-level employees.
- Review attrition by department, job role, salary band, and travel frequency together.
- Establish regular career conversations and promotion-readiness plans.
- Track overtime and workload at team level and intervene where sustained pressure is visible.
- Use employee-satisfaction results to guide manager and workplace interventions.
- Build a recurring Power BI refresh and review the dashboard with HR business partners each month.

## Data fields explored

The source data includes employee ID, age and age group, attrition status, business travel, department, distance from home, education, job role and level, marital status, income and salary band, overtime, satisfaction scores, years at company, years in current role, and years since last promotion.

## Files in this repository

- `HR_Analytics-4.csv` — employee-level HR dataset used for analysis.
- `HR_Analytics_Dashboard.pdf` — exported dashboard/report.
- `README.md` — project description and dashboard insights.

## Tools used

- **Power BI** for data modelling, measures, visualisations, and dashboard design.
- **CSV** as the source data format.

## Disclaimer

This is an analytical and portfolio project. The findings are based on the supplied dataset and should be validated against current HR systems and qualitative employee feedback before being used for employment decisions.
