# Employee Workforce Analytics

## Employee Attendance, Workforce & Compensation Analysis

An end-to-end employee analytics project using Python and Power BI to clean workforce attendance data, analyze employee attendance patterns, and generate insights across departments, locations, employment types, lateness, overtime, and compensation.

## Project Overview

This project focuses on transforming employee attendance data into structured information for workforce analysis and management reporting.

The analysis covers:

* Data cleaning and validation
* Duplicate detection and removal
* Missing-value handling
* Standardization of employee attributes
* Attendance analysis
* Department analysis
* Location analysis
* Monthly attendance trends
* Lateness analysis
* Overtime analysis
* Salary analysis
* Outlier detection
* Power BI dashboard development

## Data Cleaning

The Python workflow includes:

* Checking missing values
* Removing exact duplicate records
* Removing leading and trailing spaces
* Converting date columns
* Converting numeric columns
* Handling missing numeric values using median values
* Standardizing department names
* Standardizing location names
* Standardizing employment types
* Standardizing attendance statuses
* Removing attendance records occurring before an employee's joining date
* Validating employee email addresses

## Feature Engineering

Additional analytical fields were created during the cleaning and analysis process:

* `Total_Compensation`
* `Late_Flag`
* `Overtime_Flag`
* `Attendance_Year`
* `Attendance_Month`
* `Attendance_Month_Name`

These fields support deeper workforce and attendance analysis.

## Exploratory Data Analysis

The project investigates:

### Workforce Overview

* Total employees
* Department distribution
* Employment type distribution
* Location distribution
* Employee status

### Attendance Analysis

* Attendance status distribution
* Overall attendance rate
* Department-level attendance
* Location-level attendance
* Monthly attendance trends

### Lateness Analysis

* Average late minutes
* Maximum late minutes
* Records with lateness
* Lateness by department
* Lateness by location

### Overtime Analysis

* Total overtime hours
* Average overtime hours
* Overtime by department
* Overtime by location

### Salary Analysis

* Average basic salary
* Minimum salary
* Maximum salary
* Average salary by department
* Average salary by designation

### Outlier Analysis

The project applies the IQR method to investigate potential outliers in:

* Late minutes
* Overtime hours
* Basic salary
* Allowance

Outliers are investigated as potential data-quality or workforce patterns rather than automatically removed.

## Power BI Dashboard

The cleaned employee data was used to create an interactive Power BI dashboard for workforce and attendance analysis.

The dashboard supports analysis across areas such as:

* Employee workforce overview
* Attendance performance
* Department comparison
* Location comparison
* Monthly attendance trends
* Lateness
* Overtime
* Compensation

## Visual Analysis

The Python analysis includes visualizations for:

* Attendance status distribution
* Attendance rate by department
* Attendance rate by location
* Monthly attendance trends
* Overtime by department
* Average lateness by department
* Salary distribution

## Tools & Technologies

* Python
* Pandas
* NumPy
* Matplotlib
* Power BI
* Data Cleaning
* Exploratory Data Analysis
* Data Validation
* Feature Engineering
* KPI Analysis
* Workforce Analytics

## Project Workflow

**Raw Employee Data → Data Cleaning → Validation → Feature Engineering → EDA → Visualization → Power BI Dashboard → Workforce Insights**

## Repository Contents

| File                      | Description                           |
| ------------------------- | ------------------------------------- |
| `Employeedata.ipynb`      | Python data cleaning and EDA notebook |
| `EMPLOYEE_DASHBOARD.pbix` | Power BI workforce dashboard          |

> The source employee CSV dataset is not included unless permission is available to publish it publicly.

## Skills Demonstrated

* Data Cleaning
* Data Validation
* Exploratory Data Analysis
* Python Data Analysis
* Data Visualization
* Power BI
* Workforce Analytics
* Attendance Analytics
* Compensation Analysis
* Business Intelligence
