# INCUBATOR HUB HR DATA ANALYSIS TRACKER

[Project Overview](#project-overview) 

[Data Source](#data-source)

[Data Collected](#data-collected)

[Project Objective ](#project-objective)

[Tools used](#tools-used)

[Key Metrics](#key-metrics)

[Data Cleaning and Preparations](#data-cleaning-and-preparations)

[Dashboard Overview](#dashboard-overview)

[Exploratory Data Analysis](#exploratory-data-analysis)

[Data Visualization](#data-visualization)

[Table](#table)

    
### Project Overview
---
Collection and analysis of HR data across the company's various educational fields, attrition rate, cf_age band. The goal of the project is to provide insights into number of attrition, attrition rate, number of current employees and Job satistaction rate for the data period. The analysis focuses on understanding attrition trends across various departments and age-group and calculating key performance indicators like; total number of attrition, rate of attrition, number of current employees and job satisfaction rate.
    
### Data Source
---    
Company HR Data

### Data Collected
---    
This data contains some key columns.
1. Attrition rate : rate at which employee leave the organisation. Both voluntary or involuntary without replacement. Calculated as; count of attrition/total number of employees
2. CF_age_band - age range of employees.
3. CF_current_employee- total number of current employees. 
4. Job satisfaction : shows level of satisfaction of employees with their jobs
5. Yearly income- how much is being paid to employees per year. Calculated as; monthly income*12
7. Gender - defines the gender classification of the employees in the company.
8. Job role- it is the job functions of each employee
9. Education- level of education attaned by employees
  
### Project Objective  
--- 
This project is to address the following analysis goals.
1. Attrition Rate
2. Number of current Employees
3. Attrition count by Educational field
4. Department by attrition count
5. Current employees by Age band
6. Attrition count by Age groups by Gender
7. No of employees by job role
8. Cuurent employee by marital status by gender
9. Job satisfaction by job role by attrition rate


### Tools used
---
- Power BI [Download here](   )

  1. For Data cleaning and preparation,
  2. Analysis and
  3. Visualisation
  
- Github for Portfolio Building

### Key Metrics
---
1. Attrition rate
2. Job satisfaction rating
3. Total number of current employees
4. Yearly income

### Data Cleaning and Preparations
---
1. Power BI:
   - Transform data  was used for cleaning the dataset.
   - Conditional Column(DAX Function) - Count of Attrition
     ```
     Formula:
     IF Count Attrition equals 'Yes' then 1
              else 0
   
     ```
   - Conditional Column(DAX Function) - Age Sort
     ```
     Formula:
     IF Age-band is 'Under 25' then  1
     IF Age-band is '25-34' then  2
     IF Age-band is '35-44' then  3
     IF Age-band is '45-54' then  4
     IF Age-band is 'Over 55' then  5
     ```
   - Calculated Measure- Rate of Attrition
      ```
     Formula: Count of Attrition / Total number of employees
   
     ```
   - Card, Charts, Matrix, Tables,etc - for visualisations       
  

## Dashboard Overview

![Screenshot 2024-11-03 210532](https://github.com/user-attachments/assets/b462f251-0b76-4ca7-b5bf-f5afa4233bc9)

![Screenshot 2024-11-03 204742](https://github.com/user-attachments/assets/06639bb6-90b6-4348-aaec-aa1372f9efd1)




                                                                                            |A|
## Attrition Rate and Count of Attrition

### Exploratory Data Analysis 
---
The use of Power BI table and cards visualisations to organize, summarize, and analyze datasets, making it easier to discover patterns and insights in the dataset.
![Screenshot 2024-11-03 211841](https://github.com/user-attachments/assets/6d06dcaa-8dc5-49fc-8cf3-1a1ce5ba00bc)
![Screenshot 2024-11-03 213742](https://github.com/user-attachments/assets/df5bbe11-4019-43c8-abb6-5b4a95946b44)
![Screenshot 2024-11-03 213717](https://github.com/user-attachments/assets/4541507b-d1b9-4771-b947-9702274a686d)
![Screenshot 2024-11-03 213705](https://github.com/user-attachments/assets/db5e0d11-c0b7-4366-9570-3e5c66d58f8f)


### Data Visualization
---
![Screenshot 2024-11-03 212157](https://github.com/user-attachments/assets/d0cec4e7-c71a-43e8-b0d0-26cf2f51de2c)    ![Screenshot 2024-11-03 212351](https://github.com/user-attachments/assets/7fe04874-5b82-4631-9f77-11fe9133de34)

![Screenshot 2024-11-03 213025](https://github.com/user-attachments/assets/c8e6a2eb-b7e3-4f23-9d23-1eff053c4e86)    ![Screenshot 2024-11-03 212113](https://github.com/user-attachments/assets/58d96ccd-6d89-4d96-ad76-9288bc4a51cf)

### Inferences
---
1. Overall Income Trends
   - The Lowest Yearly income for the organisation is 12,108 which was from R&D Department (an ex-employee) followed by 12,602 also from same department (a current employee).
   - 
2. Departmental Performance
   
3. Gender Performance

4. Age_band Performance
   
5. Strategic Implication
   
### Conclusion
---


                                                                                        |B|
## Current Employees

### Exploratory Data Analysis 
---
- The use of Pivot table to organize, summarize, and analyze datasets, making it easier to discover patterns and insights in the dataset.




### Data Visualization
---



### Inferences:
---
1. Overall Revenue Trends
2. Regional Performance
3. Revenue Distribution
4. Strategic Implication
   
### Conclusion
---
                                                                                    |C|

## Total number of Employees

### Exploratory Data Analysis 
---
- The use of Pivot table to organize, summarize, and analyze datasets, making it easier to discover patterns and insights in the dataset.




### Data Visualization
---

### Inferences:
---
1. Overall Revenue Trends
2. Regional Performance
3. Revenue Distribution
4. Strategic Implication
   
### Conclusion
---


                                                                                        |D|



## Yearly Income

### Exploratory Data Analysis 
---
- The use of Pivot table to organize, summarize, and analyze datasets, making it easier to discover patterns and insights in the dataset.




### Data Visualization
---

### Inferences:
---
1. Overall Revenue Trends
2. Regional Performance
3. Revenue Distribution
4. Strategic Implication
   
### Conclusion
---


## Table
🥇

💻
TOTAL REVENUE

|Heading 1|Heading 2|Heading 3|
|----|----|----|
|2014|2015|TOTAL DATA|
|48,464,608,200.00|24,567,382,080.00|73,031,990,280.00|

TOTAL AVERAGE REVENUE

|Heading 1|Heading 2|Heading 3|
|----|----|----|
|2014 DATA|2015 DATA|TOTAL DATA|
|2383427.18|2347575.93|4731003.10|

Total Units Sold

|Heading 1|Heading 2|Heading 3|
|----|----|----|
|2014 data|2015 data|Total DATA|
|517013.00|269665.00|786678.00|



