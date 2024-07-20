# HR Department Absenteeism Analysis Project

## Problem Statement
This report is designed to assist the HR department in managing employee absenteeism. With a large number of employees, it is crucial to monitor absenteeism patterns to maintain work quality and take necessary actions.

## Solution Approach
The analysis was conducted using SQL Server for data analysis, followed by data visualization and dashboard creation in Power BI. Two dashboards were developed to provide comprehensive insights:

- [Absenteeism Analysis Performance](https://github.com/Abdoo50/HR-Department-Reports/blob/main/Absenteesm%20Analysis%20Performance.png)
- [Reasons and Employee Report](https://github.com/Abdoo50/HR-Department-Reports/blob/main/Reasons%20and%20Employee%20Report.png)

## Tools Used
- **SQL Server**: For data extraction, transformation, and analysis.
- **Power BI**: For creating interactive dashboards.

## Insights and Recommendations
### Absenteeism Analysis Performance Dashboard
![Absenteeism Analysis Performance](https://github.com/Abdoo50/HR-Department-Reports/blob/main/Absenteesm%20Analysis%20Performance.png)

Key Insights:
- **Average Absenteeism Time**: 6.92 hours per employee.
- **Total Absenteeism Hours**: 5124 hours.
- **Correlation with BMI**: Higher absenteeism in employees with higher BMI.
- **Absenteeism by Month**: Peaks in January and October.

Recommendations:
- Implement wellness programs to address health issues related to higher BMI.
- Investigate the reasons for increased absenteeism in specific months and take preventive measures.

### Reasons and Employee Report Dashboard
![Reasons and Employee Report](https://github.com/Abdoo50/HR-Department-Reports/blob/main/Reasons%20and%20Employee%20Report.png)

Key Insights:
- **Primary Reasons for Absenteeism**: Medical issues and personal reasons.
- **Absenteeism by Department**: Higher in certain departments indicating possible work environment issues.
- **Trends Over Time**: Identifiable patterns that can help in forecasting future absenteeism.

Recommendations:
- Address department-specific absenteeism by improving work conditions and employee engagement.
- Provide support for employees with frequent medical absenteeism through health benefits and flexible working conditions.

## Dataset Features
The dataset includes the following features:
- **Employee ID**: Unique identifier for each employee.
- **Age**: Age of the employee.
- **BMI**: Body Mass Index of the employee.
- **Department**: Department where the employee works.
- **Absenteeism Hours**: Number of hours the employee was absent.
- **Absenteeism Reason**: Reason for the absenteeism.
- **Absenteeism Date**: Date of the absenteeism.

## Conclusion
This analysis provides a clear view of absenteeism patterns within the company, helping the HR department to take data-driven actions to improve employee attendance and overall productivity.
