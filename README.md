# INCUBATOR HUB HR DATA ANALYSIS TRACKER

[Project Overview](#project-overview) 

[Data Sources](#data-sources)

[Data Collected](#data-collected)

[Project Objective ](#project-objective)

[Tools used](#tools-used)

[Key Metrics](#key-metrics)

[Data Cleaning and Preparations](#data-cleaning-and-preparations)

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
- Power BI [Download here][ ](   )

  1. For Data cleaning and preparation,
  2. Analysis and
  3. Visualization
  
- Github for Portfolio Building

### Key Metrics
---
1. Attrition rate
2. Job satisfaction rating
3. Total number of current employees- total number of current employees.
4. Yearly income

### Data Cleaning and Preparations
---
1. Power BI:
   - Transform data was used for cleaning the dataset.
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
   - Card, Charts, Matrix, Tables,ets - for visualizations       
     
                                                                                            |A|
## Attrition Rate and Count of Attrition

### Exploratory Data Analysis 
---
The use of Power Bi table to organize, summarize, and analyze datasets, making it easier to discover patterns and insights in the dataset.


### Data Visualization
---




### Inferences
---
1. Overall Revenue Trends
2. Regional Performance
3. Revenue Distribution
4. Strategic Implication
   
### Conclusion
---

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



