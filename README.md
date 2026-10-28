# HR-Workforce-Dashboard-Excel-
Excel dashboard showing headcount, salary, gender mix and hiring trends for 500 employees.
Project Overview

HR teams are regularly asked simple but important questions: How many people do we have? Where do they sit? How does pay compare across teams? How fast are we hiring?

This project answers those questions for a company of 500 employees across 10 departments, and presents the results in a clean dashboard that a non-technical manager can read in under a minute.

Goal: practise the full workflow of an entry-level HR / people-analytics task: clean the data, summarise it, visualise it and write up the findings.

Dashboard at a Glance
KPI	Value
Total employees	500
Average age	40.8 years
Departments	10
Average salary	₹6,65,024 per year

Charts

Employee headcount by department: horizontal 3D bar chart
Employee distribution by gender: doughnut chart with percentages
Average salary by department: 3D column chart
Annual hiring trends (2005–2025): line chart
Key Findings
Engineering pays the most: ₹10.87 L on average, about 1.6× the company average of ₹6.65 L. Sales is the lowest at ₹5.00 L.
IT is the largest department with 63 employees (12.6% of the workforce). Customer Support is the smallest with 40.
Gender mix is close to even: 48.8% Female (244), 47.0% Male (235) and 4.2% Non-binary (21).
Hiring peaked in 2025 at 44 new employees, up from 25 in 2024 and from 8 in 2005.

1 L (lakh) = 100,000 INR.

Dataset

A sample HR dataset of 500 employees (IDs 1001–1500) with 21 columns. Email addresses use the example.com domain, so the file contains no real personal data.

Group	Columns
Identity	EmployeeID, FirstName, LastName, Gender, DOB, Age, MaritalStatus, Education
Job	Department, JobTitle, ManagerID, Location, EmploymentType, Active
Pay & performance	SalaryINR, PerformanceScore, WorkExperienceYears
Dates	HireDate, LastPromotionDate
Contact	Email, Phone

Data notes

The cleaned sheet has a proper header row and 500 unique employee records.
ManagerID (90 blanks) and LastPromotionDate (229 blanks) are left empty on purpose, since not every employee has a manager on file or a promotion yet.
One employee has no Age, so average age is based on 499 employees.
Workbook Structure

HR_Dashboard_Project.xlsx contains four sheets:

Sheet	What it holds
RAW data	The original data as received
cleaned data	The cleaned dataset used for all analysis
HR analysis	PivotTables: headcount by department, employees by job title, average salary by department, gender distribution, hiring by year
Dashboard	KPI cards, four PivotCharts and the key findings

Tools & Skills Used
Microsoft Excel: PivotTables, PivotCharts, data cleaning, formatting
Dashboard design: KPI cards, colour contrast, layout and readable labels
HR analytics: headcount analysis, compensation analysis, diversity mix, hiring trends
Communication: turning numbers into plain-English findings

Business Questions Answered
How is the workforce distributed across departments?
Which departments pay the most and the least?
How balanced is the workforce by gender?
How has hiring changed over the years?

About Me

Charan L: aspiring HR professional interested in people analytics.

LinkedIn: https://www.linkedin.com/in/charan-l-7b8a18445/
Email: charann.web@gmail.com

If you have feedback on this project, I'd love to hear it.
