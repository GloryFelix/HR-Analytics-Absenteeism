
# Arima Insurance Global - HR Analysis on Absenteeism

## Introduction
The analysis focuses on the absenteeism case study of Arima Insurance global. The objective is to know the causes of absenteeism, the department with most absent days and how to improve employee presence in Arima. The analysis was carried out using Microsoft Power Bi.

## Data Gathering
The dataset used in this analysis was provided by [10Alytics](https://www.10alytics.io/) during the growth internship program. 
The datasets consist of a single table which is the fact table and consist of 8,336 records and 13 attributes which includes: EmployeeNumber, Surname, GivenName, Gender, City, JobTitle, Department, StoreLocation, Division, Age, LengthService, AbsentHours and BusinessUnit.

## Data Transformation/Cleaning
Data was efficiently cleaned and transformed with the Power Query Editor of Power BI. The Arima data table was transformed to ensure faultless and clean data. Some of the applied steps included:
- Changing data types to the right one
- Merged the Surname and GivenName columns to a single column and renamed the column to Name
- Added conditional columns for length of service group.
- Added a second conditional column for age called age group. The group is divided into 5; 0–29, 30–39, 40–49, 50–59 and 60 years and above.
- Added a third conditional column for AbsentHours called AbsentHoursGroup
  The transformed data was loaded into the power bi desktop.

## Data Modelling
There was no data modelling because we have only one table.

## Data Analysis and Visuals
The analysis was divided into 3 categories:
- The total number of employees is 8,366 having males(4,216) and 4,120 females.
- Vancouver had the highest number of employees (1,780)

![cities with the highest nmber of employee](/images/01_chart.png)

Blue River, Keremeos and Lytton had the least number of cities of 2 employees each.

![cities with least nmber of employee](/images/02_chart.png)

Customer Service Department had the highest employees of 1,737 while legal department had the least employees(3)

![dept with highest and least employess](/images/funnel_chart.png)

Absent hours is converted to absent days.
From the analysis female workers missed work than male workers. Also, workers that stays at Vancouver are absent most days than others.
length of service are grouped into level 1(1-5yrs), level 2(6-10yrs), level 3(11-15yrs), level 4(16-20yrs), level 5(21-25yrs) and level 6(above 27yrs). level 1 misseed work more compared to other levels.

![dashbord](/images/dashboard.png)

You can interact with the dashboard here [HR_Analytics-Absenteeism case study](https://app.powerbi.com/view?r=eyJrIjoiMjA2ZTNkMGQtZTEwMy00ZWFkLWEyODAtYjlmZGM3NDE5OGQ1IiwidCI6ImM3ZTFiYjRlLTU1OTYtNDQyZS1iYThiLWM1MDUzOWZlZjUyZCJ9&pageName=ReportSection937e5db4bd726e17c670)
## Limitations and Conclusions
The data provided do not include the calendar so we can’t draw a conclusion on whether the weather affects the presence of employees at work. Also, we can’t tell for sure the mode of each worker, if it is remote or otherwise. This information will be needed for further analysis to be carried out.
The higher the number of employees in a department and higher the absent hours/days. Also, employees with less than 6yrs experience at Arima pastry missed more days at work than those with higher experience level.


