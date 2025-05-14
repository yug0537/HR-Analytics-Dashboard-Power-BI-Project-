# HR_Analytics_Dashboard_Power BI_Project
To analyze employee attrition data across various dimensions such as age, gender, salary, education, department, and job role, with the goal of uncovering trends and patterns that can inform HR strategies to reduce turnover and improve retention.

## Project Objective
To analyze employee attrition data across various dimensions such as age, gender, salary, education, department, and job role, with the goal of uncovering trends and patterns that can inform HR strategies to reduce turnover and improve retention.

## Dataset Used
<a href="https://github.com/yug0537/HR-Analytics-Dashboard-Power-BI-Project-/blob/main/HR_Analytics.csv">Raw Data<a/>

## KPIs
- Total Employees : 1,470
- Attrition Count(Number of employees who have left the company: 237
- Attrition Rate (%) : 16.1%
  - Formula: (Attrition Count / Total Employees) × 100
  - Purpose: Measures the percentage of employees leaving the company. A crucial metric for workforce stability.
- Average Age: 37 years
  - Purpose: Gives insight into the age distribution of the workforce and helps identify which age group has higher attrition.
- Average Salary: ₹6.5K/month
- Average Tenure (Years at Company): 7.0 years
- Attrition by Gender: Male (140), Female (79)
- Attrition by Department
- Attrition by Job Role
  - Laboratory Technician (62)
  - Sales Executive (57)
  - Research Scientist (47)
- Attrition by Age Group: 26–35 years (116 employees)
- Attrition by Salary Slab: Up to ₹5K/month (163 employees)
  - Purpose: Reveals that lower-paid employees are more likely to leave.
- Attrition by Years at Company
  - Insight: Highest attrition in the first 2 years
  - Purpose: Helps HR focus on early retention strategies.
 
## Dashboard Interaction
<a href="https://github.com/yug0537/HR-Analytics-Dashboard-Power-BI-Project-/blob/main/HR_Analytics_dashboard.pbix">Dashboard<a/>

## Process
- Data Acquisition: Used the HR_Analytics.csv dataset containing employee demographic and job information, attrition status, salary, department, and years at the company.
- Data Cleaning & Preparation:
   - Removed nulls and inconsistencies.
   - Created calculated columns such as:
   - Salary Slab
   - Age Groups
  - Years at Company Buckets
-  Data Modeling in Power BI:
   - defined relationships and calculated key measures like:
   - Attrition Count
   - Attrition Rate (%)
   - Avg Salary
   - Avg Age
   - Years at Company
-  Dashboard Development:
   - used a dark-themed, professional design.
   - Incorporated slicers (Department, Gender).
   - Created intuitive visuals: bar charts, donut charts, line graphs, and KPIs.
 
## Dashboard View
<img width="1283" alt="Screenshot 2025-05-14 at 11 58 05" src="https://github.com/user-attachments/assets/5be9efc1-f1fe-4002-ba1a-98f23eedc56d" />

## Key Insights
- Overall Attrition Rate: 16.1% (237 out of 1470 employees).
- Age Group Most Affected: 26–35 years (116 attritions), followed by 18–25.
- Employees earning ≤ ₹5K/month account for ~69% of total attrition.
- Highest attrition from Life Sciences (38%) and Medical (27%) backgrounds.
- Research & Development shows high attrition, especially in Laboratory Technicians (62),Research Scientists (47)
- Job Roles with High Turnover: Sales Executive (57),Sales Representative (33)
- Male: 140 | Female: 79 — indicating a broader attrition challenge across both genders.
- Majority of attrition occurs within the first 2 years, highlighting potential onboarding or early engagement issues.

## Conclusion
The HR analytics dashboard reveals that attrition is largely concentrated among young employees in low-paying roles within the R&D and Sales departments. Key contributing factors include:
	-	Low starting salary
	-	Early-career stage
	-	Specific job functions with limited growth or high pressure

## Recommendation
Enhance retention through salary restructuring, mentorship programs, and career path visibility.
	-	Focus on early engagement and employee development, especially within the first 2 years.
	-	Conduct department-specific retention reviews, especially in R&D and Sales.




