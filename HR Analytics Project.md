# HR Analytics Project

## Dataset Overview

### Dataset Description

The HR Analytics project involves analyzing a dataset containing various employee-related attributes. The dataset includes the following columns:

- **Age:** The age of employees.
- **Attrition:** Whether an employee has attrited (left the company) or not (binary: "Yes" or "No").
- **BusinessTravel:** The frequency of business travel ("Travel_Rarely," "Travel_Frequently," or "Non-Travel").
- **DailyRate:** The daily rate of pay for employees.
- **Department:** The department in which the employee works.
- **DistanceFromHome:** The distance from the employee's home to the workplace.
- **Education:** Employee's level of education (ranging from 1 to 5).
- **EducationField:** The field of education of the employee.
- **EmployeeCount:** A constant value (likely 1) representing the count of employees.
- **EmployeeNumber:** A unique identifier for each employee.
- **EnvironmentSatisfaction:** Satisfaction level with the work environment (ranging from 1 to 4).
- **Gender:** Employee's gender ("Male" or "Female").
- **HourlyRate:** The hourly rate of pay for employees.
- **JobInvolvement:** Level of job involvement (ranging from 1 to 4).
- **JobLevel:** Employee's job level within the company (e.g., 1, 2, 3).
- **JobRole:** The role or position of the employee.
- **JobSatisfaction:** Satisfaction level with the job (ranging from 1 to 4).
- **MaritalStatus:** Marital status of the employee ("Single," "Married," or "Divorced").
- **MonthlyIncome:** Monthly income of employees.
- **MonthlyRate:** Monthly rate of pay for employees.
- **NumCompaniesWorked:** The number of companies the employee has worked for.
- **Over18:** Indicates whether employees are over 18 (likely binary: "Yes" or "No").
- **OverTime:** Whether employees work overtime ("Yes" or "No").
- **PercentSalaryHike:** The percentage of salary hike received by employees.
- **PerformanceRating:** Performance rating of employees (likely 3 or 4).
- **RelationshipSatisfaction:** Satisfaction level with work relationships (ranging from 1 to 4).
- **StandardHours:** Standard number of work hours (likely 80 for full-time employees).
- **StockOptionLevel:** Level of stock options granted to employees (ranging from 0 to 3).
- **TotalWorkingYears:** Total years of work experience.
- **TrainingTimesLastYear:** Number of training sessions attended by employees in the last year.
- **WorkLifeBalance:** Satisfaction with work-life balance (ranging from 1 to 4).
- **YearsAtCompany:** Years spent working at the current company.
- **YearsInCurrentRole:** Years spent in the current job role.
- **YearsSinceLastPromotion:** Years since the last promotion.
- **YearsWithCurrManager:** Years working with the current manager.

### Data Exploration

Before diving into HR analytics, it's essential to explore and clean the dataset. Key data exploration steps include:

1. **Data Cleaning:**
   - Remove redundant columns like "EmployeeCount" and "Over18."
   - Handle missing values (NaNs) if present.
   - Check for and remove duplicate rows.
   - Rename columns for clarity and consistency.

2. **Initial Insights:**
   - Calculate summary statistics (mean, median, etc.) for numeric variables.
   - Explore the distribution of categorical variables through frequency counts and visualizations.
   - Identify any outliers or unusual patterns in the data.

3. **Data Visualization:**
   - Create visualizations to better understand relationships between variables.
   - Plot histograms, bar charts, and scatter plots as needed.
   - For numeric variables, consider creating a correlation matrix to identify potential correlations.

Once the data is cleaned and explored, you can proceed with more in-depth HR analytics, including attrition analysis, employee satisfaction assessments, and more.

[Link to Data Cleaning and Visualization](#) (Provide a link to a separate document or section for detailed data cleaning and visualization steps.)
