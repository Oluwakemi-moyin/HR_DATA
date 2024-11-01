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

    
### Project Overview
---
Collection and analysis of HR data across the company's various educational fields, attrition rate, cf_age band. The goal of the project is to provide insights into number of attrition, attrition rate, number of current employees and Job satistaction rate for the data period. The analysis focuses on understanding attrition trends across various departments and age-group and calculating key performance indicators like; total number of attrition, rate of attrition, number of current employees and job satisfaction rate.
    
### Data Source
---    
Company HR Data

### Data Collected
---    
This data contains some key columns.
1. Attrition
2. CF_age_band
3. CF_current_employee
4. Job satisfaction
5. Daily rate
6. Momthly income
7. Gender
8. Years at Company
9. Educational Field
  
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
- Power BI [Download here][sales data.xlsx](https://github.com/user-attachments/files/17345479/sales.data.xlsx)

  1. For Data cleaning,
  2. Analysis and
  3. Visualization
  
- Github for Portfolio Building

### Key Metrics
---
1. No of Attrition: calculated by multiplying the selling price of each item by the total units sold for the item.
2. Job satisfaction rating
3. Total number of current employees
4. Attrition rate

### Data Cleaning and Preparations
---
1. Power BI:
   - Transform data was used for cleaning the dataset.
   - Conditional Column(DAX Function) - Number of attrition
     ```
     Formula:
     IF Attrition equals 'Yes' then 1
              else 0
   
     ```
   - Conditional Column(DAX Function) - Age Sort
     ```
     Formula:
     IF Age-band is '15-44' then  1
     IF Age-band is '15-44' then  2
     IF Age-band is '15-44' then  3
     IF Age-band is '15-44' then  4
     ```
   - Calculated Measure- Rate of Attrition
      ```
     Formula: Number of Attrition / Total number of employees
   
     ```
   - Card, Charts, Matrix, Tables,ets - for visualizations       
     
                                                                                            |A|
## Revenue by Region

### Exploratory Data Analysis 
---
- The use of Pivot table to organize, summarize, and analyze datasets, making it easier to discover patterns and insights in the dataset.


![Revenue for 2014-pivot table](https://github.com/user-attachments/assets/c41c43da-c0ee-4e91-aa4c-bc8340d754dd)
![Revenue for 2015- pivot table](https://github.com/user-attachments/assets/be2ba993-1c8e-49a6-ada3-b1928059c1b8)

### Data Visualization
---

1. Filtered chart for year 2014
   
![REVENUE BY REGION](https://github.com/user-attachments/assets/d1909c79-f6a9-4088-9100-1c55f3409e21)


2. Filtered chart for year 2015

![RECVENUE BY REGION-2015](https://github.com/user-attachments/assets/274a596d-a8c3-4015-a1db-da71ba321d00)


### Inferences
---
1. Overall Revenue Trends
2. Regional Performance
3. Revenue Distribution
4. Strategic Implication
   
### Conclusion
---

## Region by Units Sold

### Exploratory Data Analysis 
---
- The use of Pivot table to organize, summarize, and analyze datasets, making it easier to discover patterns and insights in the dataset.

![Region by unit sold-2014-pivot table](https://github.com/user-attachments/assets/c7b15ecc-9b24-4326-9fc7-86761b51c0b1)
![Region by unit sold-2015-pivot table](https://github.com/user-attachments/assets/fec678cd-ff57-402b-869e-d2ab650e959b)


### Data Visualization
---
Filtered chart for year 2014

![Region by Units sold-2014](https://github.com/user-attachments/assets/640ada20-4aa8-484f-973b-9b3dc7565c8d)


Filtered chart for year 2015

![Region by Units sold-2015](https://github.com/user-attachments/assets/20696812-ba1d-4606-b08b-6765b14f54da)


### Inferences:
---
1. Overall Revenue Trends
2. Regional Performance
3. Revenue Distribution
4. Strategic Implication
   
### Conclusion
---

## Region by Average Revenue

### Exploratory Data Analysis 
---
- The use of Pivot table to organize, summarize, and analyze datasets, making it easier to discover patterns and insights in the dataset.

![Region by average revenue-2015-pivot table](https://github.com/user-attachments/assets/02ef8232-c1c7-4f61-b8cf-1aeba3228329)
![Region by average revenue-2014-pivot table](https://github.com/user-attachments/assets/66d25dd3-1fd1-42ee-861b-ede0491314da)


### Data Visualization
---
Filtered chart for year 2014

![average revenue by region-2014](https://github.com/user-attachments/assets/6f68776c-1f58-4901-94f7-1a28620e209a)


Filtered chart for year 2015

![average revenue by region-2015](https://github.com/user-attachments/assets/797c1da0-e432-4172-aa9d-9e47029c97d7)


### Inferences:
---
1. Overall Revenue Trends
2. Regional Performance
3. Revenue Distribution
4. Strategic Implication
   
### Conclusion
---



🥇

💻
TOTAL REVENUE

|Heading 1|Heading 2|Heading 3|
|2014|2015|TOTAL DATA|
|48,464,608,200.00|24,567,382,080.00|73,031,990,280.00|

TOTAL AVERAGE REVENUE

|Heading 1|Heading 2|Heading 3|
|2014 DATA|2015 DATA|TOTAL DATA|
|2383427.18|2347575.93|4731003.10|

Total Units Sold

|Heading 1|Heading 2|Heading 3|
|2014 data|2015 data|Total DATA|
|517013.00|269665.00|786678.00|



