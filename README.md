# HR Analytics Dashboard

An interactive HR Analytics Dashboard built with Microsoft Power BI to analyze employee attrition, workforce demographics, salary distribution, job satisfaction, departmental trends, and employee experience.

![HR Analytics Dashboard](screenshots/dashboard-overview.png)

---

## Project Overview

This project analyzes employee data to identify workforce trends and patterns related to employee attrition.

The dashboard transforms HR data into interactive visualizations and key performance indicators (KPIs) that provide insights into:

- Employee headcount
- Active employees
- Employee attrition
- Attrition rate
- Department distribution
- Salary slab distribution
- Job satisfaction
- Employee demographics
- Gender distribution
- Employee experience

The goal of this project is to demonstrate how data analytics and visualization can be used to support data-driven HR decision-making.

---

## Dashboard Overview

The dashboard provides an interactive overview of the organization's workforce and employee attrition.

### Key Performance Indicators

- **Total Employees:** 1,417
- **Active Employees:** 1,186
- **Attrition Count:** 231
- **Attrition Rate:** 16.3%
- **Average Age:** 36.94 years
- **Average Experience:** 10 years

### Interactive Filters

The dashboard allows users to filter employee data by:

- Age Group
- Department

All visualizations update dynamically based on the selected filters.

---

## Key Insights

Based on the current analysis:

### Employee Attrition

The dataset contains **1,417 employees**, of which:

- **1,186 employees** are active.
- **231 employees** have left the organization.
- The overall attrition rate is **16.3%**.

This provides an overview of the organization's employee retention and workforce stability.

---

### Department Distribution

Operations has the largest employee population with **512 employees**, followed by:

- Administration: 406 employees
- Sales: 207 employees
- IT: 166 employees
- Marketing: 64 employees
- Human Resources: 39 employees
- Finance: 23 employees

The size of each department provides important context when analyzing attrition across departments.

---

### Age Group Distribution

The largest age group is **26–35 years old**, with **588 employees**, followed by:

- 36–45: 446 employees
- 46–55: 222 employees
- 18–25: 117 employees
- 55+: 44 employees

The workforce is primarily composed of employees between 26 and 45 years old.

---

### Attrition by Salary Slab

The dashboard compares employee attrition across different salary ranges.

The analysis allows users to identify potential patterns in employee turnover across:

- 0–3 LPA
- 3–6 LPA
- 6–10 LPA
- 10+ LPA

This can help organizations investigate whether compensation levels may be associated with employee attrition.

---

### Job Role and Satisfaction

The dashboard analyzes job roles across different job satisfaction levels.

This allows HR teams to identify:

- Job roles with higher employee populations
- Job roles with lower satisfaction levels
- Potential relationships between job satisfaction and employee attrition

---

### Gender Distribution

The dataset contains:

- 146 male employees
- 85 female employees who have left the organization

The dashboard allows employee attrition to be analyzed by gender.

---

### Employee Experience

The dashboard analyzes attrition across different levels of total work experience.

This helps identify potential patterns in employee turnover across different stages of an employee's career.

---

## Dashboard Visualizations

### Attrition by Department

Analyzes the distribution of employee attrition across different departments.

### Attrition by Salary Slab

Compares employees who stayed and left across different salary ranges.

### Attrition by Job Role and Satisfaction

Analyzes job satisfaction levels across different job roles.

### Age Group Distribution

Shows the distribution of employees across different age groups.

### Attrition by Gender

Compares employee attrition across gender groups.

### Attrition Trend by Experience

Analyzes employee attrition across different levels of total work experience.

### Department-Wise Employee Count

Shows the number of employees within each department.

---

## Data Analysis Process

### 1. Data Preparation

The HR dataset was reviewed and prepared for analysis.

The preparation process included:

- Reviewing the dataset structure
- Checking data types
- Identifying relevant fields
- Reviewing categorical and numerical variables

### 2. Data Cleaning and Transformation

The dataset was prepared for dashboard analysis by:

- Reviewing data quality
- Standardizing categorical variables
- Creating age group categories
- Creating salary slab categories
- Preparing calculated metrics
- Preparing fields for visualization

### 3. Data Modeling

The data was structured to analyze relationships between:

- Employee demographics
- Department
- Job role
- Salary
- Job satisfaction
- Work experience
- Attrition

### 4. Dashboard Development

The dashboard was developed using:

- KPI cards
- Bar charts
- Donut charts
- Area charts
- Matrix tables
- Interactive filters

---

## Key Metrics

### Total Employees

The total number of employees included in the dataset.

**Value: 1,417 employees**

### Active Employees

The number of employees who remain active in the organization.

**Value: 1,186 employees**

### Attrition Count

The number of employees who have left the organization.

**Value: 231 employees**

### Attrition Rate

The percentage of employees who have left the organization compared to the total number of employees.

```text
Attrition Rate = Attrition Count / Total Employees
