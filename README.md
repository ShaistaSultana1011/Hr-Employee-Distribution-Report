# HR Employee Distribution Report 

## Business Problem

Managing an organization's workforce effectively requires a clear understanding of employee demographics, departmental distribution, work locations, and employee retention. Without a consolidated view of these factors, HR teams may find it difficult to identify workforce imbalances, understand employee turnover, and plan future staffing requirements.

This project focuses on analyzing HR employee data to uncover workforce trends, evaluate employee distribution across departments and locations, and examine hiring, termination, and tenure patterns. The insights help organizations make informed decisions about workforce planning, employee retention, and overall HR management.

---

## Objective

Analyze employee data to understand workforce demographics, evaluate employee distribution across departments and locations, examine employee tenure, and identify turnover patterns. The goal is to generate actionable insights that support workforce planning, employee retention, and strategic HR decision-making.

---

## Tools Used

- MySQL
- Power BI
- Microsoft Excel / CSV

---

## Dashboard Preview

![HR Employee Distribution Dashboard](Screenshot/Screenshot%202026-04-05%20211113.png)

---

## Analysis Performed

- Data cleaning and preprocessing
- Missing value and duplicate record analysis
- Data type validation and date formatting
- Employee gender distribution analysis
- Race and ethnicity distribution analysis
- Age group segmentation and age distribution analysis
- Headquarters versus remote workforce analysis
- Employee distribution by state and location
- Average employee length of employment analysis
- Department-wise employee distribution
- Job title distribution analysis
- Department-wise employee turnover rate analysis
- Employee hiring and termination trend analysis
- Department-wise employee tenure analysis
- Interactive dashboard development using Power BI

---

## Key Insights

The SQL analysis and Power BI dashboards explore the following aspects of workforce composition and HR performance:

- **Gender Distribution:** The dashboard shows 212 male employees, 202 female employees, and 10 non-conforming employees, providing an overview of gender representation across the workforce.

- **Race and Ethnicity Distribution:** The dashboard examines employee representation across different racial and ethnic groups. The largest displayed group is White employees, followed by Asian and Black employees.

- **Age Distribution:** The dashboard highlights employees aged 25–34, 35–44, and 45–54 as the largest age groups. Employees aged 18–24 and 55–64 represent smaller portions of the workforce.

- **Workforce Location:** The dashboard compares headquarters-based and remote employees. Approximately 75% of employees work at headquarters, while 25% work remotely.

- **Employee Tenure:** The dashboard reports an average employment length of approximately 8 years, providing an overview of workforce experience and retention.

- **Department and Job Title Distribution:** The SQL analysis examines employee counts across departments and job titles to identify workforce concentration and understand how employees are distributed across business functions.

- **Department-wise Gender Distribution:** The dashboard compares male, female, and non-conforming employees across age groups and departments, helping HR teams examine differences in workforce representation.

- **Employee Turnover:** The SQL analysis calculates department-wise termination rates using employee termination records and total employee counts. The dashboard highlights differences in the reported rates across departments, which may require further investigation.

- **Geographical Distribution:** The dashboard and SQL queries examine employee distribution across states and locations, helping identify areas with higher employee concentrations.

- **Hiring and Termination Trends:** The SQL analysis examines annual hiring and termination patterns to understand workforce changes over time.

- **Department-wise Tenure:** The SQL analysis calculates average employee tenure across departments to compare workforce experience and identify potential differences in retention patterns.

---

## Business Recommendations

- **Promote Workforce Diversity:** Monitor gender and race representation across departments and job titles to support fair recruitment, equal opportunities, and inclusive career development.

- **Plan for Different Age Groups:** Use age distribution insights to support succession planning, knowledge transfer, employee development, and long-term workforce planning.

- **Optimize Remote and Headquarters Staffing:** Evaluate the distribution of headquarters-based and remote employees to ensure that workplace facilities, resources, and collaboration practices meet organizational needs.

- **Improve Employee Retention:** Investigate departments with higher termination rates to understand potential reasons for employee turnover and develop targeted retention strategies.

- **Strengthen Departmental Workforce Planning:** Use department-wise employee counts and job title distributions to identify staffing gaps, avoid resource imbalances, and allocate employees effectively.

- **Monitor Hiring and Termination Trends:** Track annual hiring and termination patterns to understand workforce growth, anticipate staffing needs, and improve recruitment planning.

- **Enhance Employee Engagement:** Examine departments with shorter average tenure or higher termination rates to identify opportunities to improve employee satisfaction, career progression, and retention.

- **Support Data-Driven HR Decisions:** Combine demographic, geographical, tenure, and turnover insights to support informed decisions about recruitment, employee development, and workforce allocation.

- **Review Workforce Distribution Across Locations:** Use state-wise employee counts to support regional staffing decisions and ensure that workforce resources are appropriately distributed.

- **Encourage Continuous HR Monitoring:** Use the Power BI dashboard to regularly review workforce composition, employee turnover, and hiring trends so that HR teams can identify changes and respond proactively.

---

## Project Files

- **SQL Analysis:** `hr data questions.sql`
- **Power BI Dashboard:** HR Employee Distribution Report
- **Dashboard Screenshots:** `Screenshot/`
- **Dataset:** HR employee records dataset

---

## Conclusion

This project demonstrates how SQL and Power BI can be used together to transform HR employee records into meaningful workforce insights. By analyzing employee demographics, department and job title distribution, geographical location, tenure, and turnover patterns, the project provides a clearer understanding of workforce composition and organizational staffing trends.

The resulting insights can help HR teams improve workforce planning, monitor employee retention, support diversity initiatives, and make informed decisions about recruitment and employee development. The interactive Power BI dashboard also provides a convenient way to explore workforce metrics and support data-driven HR management.
