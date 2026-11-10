# People Management Analytics Dashboard

## Project Overview

People Management Analytics is a data analysis project developed using Microsoft Power BI and Power Query. It focuses on workforce insights, including employee distribution, job roles, performance scores, salary, gender, departments, and employee status.

## Tools & Technologies

- **Microsoft Power BI Desktop** — Dashboard development and visualization
- **Power Query Editor** — Data cleaning and transformation
- **CSV / Excel** — Dataset source and data storage

## Dataset

The project uses a people management dataset containing employee information such as:

- Employee ID and age
- Gender and department
- Job role
- Joining date and exit date
- Performance score
- Salary
- Employee status and location

## Power Query Data Cleaning

The dataset is prepared using Power Query Editor in Power BI.

The documented cleaning workflow includes:

1. Importing the original dataset using Get Data.
2. Opening Power Query Editor using Transform Data.
3. Applying Trim to remove leading and trailing spaces from text fields.
4. Applying Clean to remove non-printing characters.
5. Standardizing category values where inconsistencies exist.
6. Assigning appropriate data types to numeric, text, and date columns.
7. Reviewing missing values and duplicate employee records.
8. Validating employee status and exit dates.
9. Reviewing the Applied Steps and selecting Close & Apply.

For the detailed workflow, see [`POWER_QUERY_CLEANING_STEPS.md`](power_query/POWER_QUERY_CLEANING_STEPS.md).

## Dashboard Features

The Power BI dashboard includes:

- Department, JobRole, Gender, and Status filters
- Employee count by job role
- Employee performance score analysis
- Gender-wise employee trends over the years
- Salary and performance overview
- Gender distribution
- Employee count by department
- Employee status distribution for Active, Resigned, and Retired employees.


## Learning Outcomes

- Understanding data preparation using Power Query
- Working with data types and text transformations
- Reviewing data quality and validating records
- Creating interactive Power BI dashboards
- Presenting workforce insights through data visualization

## Conclusion

This project demonstrates a data analytics workflow that combines data cleaning, validation, and interactive dashboard development to support people management analysis.
