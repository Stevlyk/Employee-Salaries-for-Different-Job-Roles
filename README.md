# Employee Salaries for Different Job Roles

## Overview
This repository contains an analysis of employee salaries across different job titles and experience levels. The main objectives of this analysis are to:
* Show salary trends across various job titles and experience levels.
* Investigate the impact of remote work on compensation.
* Compare salary levels between full-time and part-time employment.
* Understand the correlation between company size and employee salaries.
  
## Dataset
The dataset includes the following columns:

work_year: The year the data was collected.
experience_level: The experience level of the employee (SE: Senior, MI: Mid-level, EN: Entry-level, EX: Executive).
employment_type: The type of employment (FT: Full-time, PT: Part-time, CT: Contract, FL: Freelance).
job_title: The job title of the employee.
salary: The salary of the employee.
salary_currency: The currency of the salary (USD, EUR, GBP, etc.).
salary_in_usd: The salary converted to USD.
employee_residence: The country of residence of the employee.
remote_ratio: The percentage of remote work (100, 50, 0).
company_location: The location of the company.
company_size: The size of the company (M: Medium, L: Large, S: Small).

## Analysis
1. Salary Trends Across Job Titles and Experience Levels
Objective: To understand how salaries vary across different job titles and levels of experience.
Method: Grouping data by job_title and experience_level, and calculating the average salary in USD.
2. Impact of Remote Work on Compensation
Objective: To investigate how remote work affects employee salaries.
Method: Grouping data by remote_ratio and analyzing the average salary in USD.
3. Comparison of Salary Levels Between Full-Time and Part-Time Employment
Objective: To compare the salaries of full-time and part-time employees.
Method: Grouping data by employment_type and calculating the average salary in USD.
4. Correlation Between Company Size and Employee Salaries
Objective: To understand the relationship between company size and employee compensation.
Method: Grouping data by company_size and analyzing the average salary in USD.

## Code
The analysis is conducted in a Jupyter Notebook. The key steps include:

Data Cleaning and Preparation: Checking for missing values and ensuring data consistency.
Exploratory Data Analysis (EDA): Visualizing data to identify patterns and trends.
Detailed Analysis: Using grouping and aggregation to draw insights from the data.

## Visualization
The analysis includes various visualizations to help understand the data better:

Bar plots showing average salaries by job title, experience level, employment type, and remote ratio.
Heatmaps to visualize the impact of remote work on different job titles and experience levels.

## Conclusion
This analysis provides valuable insights into how salaries vary based on job roles, experience levels, remote work, employment type, and company size. It can be used by employees and employers to make informed decisions about compensation.
