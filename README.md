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

[Overall Recommendation](#overall-recommendation)

    
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
8. Job role- This is the job function of each employee.
9. Education- level of education attained by employees
  
### Project Objective  
--- 
This project is to address the following analysis objectives and goals.
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
- Power BI [Download here](https://github.com/Oluwakemi-moyin/HR_DATA/blob/3a19c3707487eecfd42244839de1342ce23fd081/INCUBATOR%20HUB%20HR%20DATA%20ANALYSIS.pbix)

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
![Screenshot 2024-11-07 114641](https://github.com/user-attachments/assets/3a5571f7-b9eb-43ea-a068-f1a70368fe63)
![Screenshot 2024-11-07 114621](https://github.com/user-attachments/assets/eed2a92c-3664-458b-beca-85f3dbe1bb25)
![Screenshot 2024-11-07 114712](https://github.com/user-attachments/assets/9cc79714-d682-4beb-9b17-6182fa92f48b)



                                                                                            |A|
## Attrition Rate and Count of Attrition

### Exploratory Data Analysis 
---
The use of Power BI table and cards visualisations to organize, summarize, and analyze datasets, making it easier to discover patterns and insights in the dataset.

![Screenshot 2024-11-03 213742](https://github.com/user-attachments/assets/df5bbe11-4019-43c8-abb6-5b4a95946b44)  ![Screenshot 2024-11-03 213717](https://github.com/user-attachments/assets/4541507b-d1b9-4771-b947-9702274a686d)
![Screenshot 2024-11-03 213705](https://github.com/user-attachments/assets/db5e0d11-c0b7-4366-9570-3e5c66d58f8f)

![Screenshot 2024-11-03 211841](https://github.com/user-attachments/assets/6d06dcaa-8dc5-49fc-8cf3-1a1ce5ba00bc)

### Data Visualization
---
![Screenshot 2024-11-03 212157](https://github.com/user-attachments/assets/d0cec4e7-c71a-43e8-b0d0-26cf2f51de2c)    ![Screenshot 2024-11-03 212351](https://github.com/user-attachments/assets/7fe04874-5b82-4631-9f77-11fe9133de34)

![Screenshot 2024-11-03 213025](https://github.com/user-attachments/assets/c8e6a2eb-b7e3-4f23-9d23-1eff053c4e86)    ![Screenshot 2024-11-03 212113](https://github.com/user-attachments/assets/58d96ccd-6d89-4d96-ad76-9288bc4a51cf)

### Inferences
---
1. Overall Income Trends
   - Employee with number -259 has the highest income of 239,988/year.
   - The Lowest Income per year for the organisation is 12,108 which was a Research Scientist from R&D Department (an ex-employee) followed by 12,602 also a Research Scientist from same department (a current employee).
   - The highest Income per year for the organization is 239,988 who is a Manager from the department of R&D (current employee)
   - The average of count of attrition is more likely to increase, by 0.19units when sum of Yearly Income is 33,600 or less than otherwise.
   - Also, when the sum of Yearly Income is greater than 165,096 the average of count of attrition is 0.14units lower compared to other values.
2. Departmental Performance
   - In terms of population, the R&D department has the highest population of 961people of the overall population of 1,470people.
   - The R&D department had the highest count of attrition of 133people which is 56.12% of the overall attrition count of the three departments.
   - The HR department had the lowest count of attrition of 12people which is 5.06% of the overall attrition count of the three departments.
   - The R&D department has an attrition rate of 13.8% out of the overall population count of 1,470people in the organisation.
   - The attrition count is mostly from the ageband of 25-34 which is 348people out of the R&D department's total population of 961people.
3. Job role Performanance
   - Attrition count is more likely to decrease when job role is 'Research Director' than otherwise(on average). When job role is 'Research Director', the average count of attrition is 0.14units lower compared to all other         Job roles.
   - Sales representatives have the highest attrition rate of 39.8%. Laboratory technicians have the highest attrition count of 62people, but due to a larger staff strength as compared to sales representatives, the attrition 
     rate is higher for sales represntatives with a smaller staff strength. 
   - Research directors have the lowest attrition rate of 2.5%.
3. Gender Performance
   - Male staffs have the highest % of Attrition rate, which is 17% of the overall population.
   - Female staffs have the lowest % of Attrition rate, which is 14.8% of the overall population.
4. Age_band Performance
   - The Age band of 25-34 had the highest attrition count of 112 which is 7.6% of the overall attrition rate and an attrition rate of 20.2% of the age band's population. However, the age band of under 25 had the highest           attrition rate of 39%.
   - The over 55 age band have the lowest attrition count of 11 which is 0.748% of the overall attrition rate amd an attrition rate of 15.9% of the age band's population. However, the age band of 35-44 had the lowest               attrition rate of 10.1%.
5. Satisfaction Rating
   - The Sales representatives have the highest very dissatisfied ratings of 58.3% as compared to Mangers with 4.8%.
   - The high dissatisfaction ratings comes mostly from those with lower working years in the company as compared to those who have spent longer who have higher satisfaction ratings.
6. Strategic Implication
   - The Income(monthly &Yearly) is a major influencer of the count of atttrition. There is a negative relationship between the two.
   - An increase in income causes attrition count to decline by about 0.14units and a decrease in income levels causes attrition count to rise by about 0.19units on average.
   - The Attrition falls mostly in the R&D department (under 25) age band segment despite the fact that 25-34 has the highest attrition count. This is because, on a closer view, with respect to population, it is seen that 
     under 25 group had a higher attrition rate of 32.8% compared to 25-34 group with 18.7% attrition rate.
   - From the above, it is possible that under 25 group left for futher studies as opposed to 25-34 leaving mostly due to low income.
   - The Manager role in the R&D department are not as affected by attrition as compared to the Research Scientist role among others.
   - Sales representatives are mostly affected by the attrition. Out of a total of 83 staffs, 33 left. Leaving their current population as 50 staffs
   
### Conclusion
---
The R&D department(junior staffs like Research scientist, etc) and Sales Department(sales representatives) are the most affected departments which is mostly due to low average yearly income. The company should do a review of their salaries, once their salaries are increased, there will be a reduction in the rate of attrition.

                                                                                        |B|
## Current Employees

### Exploratory Data Analysis 
---
The use of Power BI table to organize, summarize, and analyze datasets, making it easier to discover patterns and insights in the dataset.

![Screenshot 2024-11-03 213119](https://github.com/user-attachments/assets/8018040b-d815-42ec-962e-49e11178566a)
![Screenshot 2024-11-04 140339](https://github.com/user-attachments/assets/619be2f5-0ba1-4c7e-9cce-b8d2ef8a633f)



### Data Visualization
---
![Screenshot 2024-11-03 213204](https://github.com/user-attachments/assets/38105b35-639c-41bd-a80a-b987b1725d7e)
![Screenshot 2024-11-03 211857](https://github.com/user-attachments/assets/08a2e011-8851-4c75-bace-c09636dc1e77)



### Inferences:
---
1. Overall Income Trends
   - The overall total sum of yearly income for current employees is 101,097,216.
   - The Employee with the highest income is STAFF-259 with a sum of yearly income of 239,988.
   - The count of current employees is 1,233.
   
3. Departmental Performance
   - R&D department have the highest current employee count of 828staffs. 
   - HR department have the lowest current employee count of 51staffs.
4. Job Role performance
   - Sales executives have the highest population among the current employees with 269 people and
   - Human resources staffs have the lowest population among current employees with 40people.
5. Age band Performance
   - 35-44 have the highest current employee count of 454persons
   - over 55 have the smallest current employee count of 58persons. Followed by under 25 age group with 59persons.
   - A total of 38people left the organisation within the age band of under 25. 
6. Gender Performance
   - Married males have the highest population count of current employees with a sum of 348staffs
   - Divorced Females have the lowest population count of 108 women.
   - More males left the organization as compared to females.
7. Strategic Implication
   - Overall 237 people left the organization making it a total of 1233 persons remaining in the organisation.
   - The age band with the most population after the attrition of staffs is the 35-44 group. In an organization, there is need for more vibrancy which is usually brought by the 25-34 age group.
   
### Conclusion
---
The management team of the organization has to meet with the hr team to do a salary upward review for all affected departments and job roles. 

                                                                                        |C|

## Yearly Income

### Exploratory Data Analysis 
---
The use of Power BI tables and cards to organize, summarize, and analyze datasets, making it easier to discover patterns and insights in the dataset.

![Screenshot 2024-11-03 213705](https://github.com/user-attachments/assets/18ca119e-556f-4610-87d7-32f1aed1168a)
![Screenshot 2024-11-04 142527](https://github.com/user-attachments/assets/117c6bfa-40e7-4eaf-97a8-a7f87d42adfa)



### Data Visualization
---
![Screenshot 2024-11-04 142718](https://github.com/user-attachments/assets/d0120225-c2a6-451e-bfcc-883ae78bb813)
![Screenshot 2024-11-04 143834](https://github.com/user-attachments/assets/1afd984a-6ede-49db-8f9b-eea75899d012)
![Screenshot 2024-11-04 145034](https://github.com/user-attachments/assets/e6981d7c-c1af-4d4b-9062-3c38b4bd9bc9)
![Screenshot 2024-11-04 160527](https://github.com/user-attachments/assets/eb3cb312-0c18-413e-890f-ddedf6384949)


### Inferences:
---
1. Overall Income Trends
   - The Top 5 employees by Yearly income are; STAFF-259, STAFF-1035, STAFF-1191, STAFF-226, STAFF-787 accordingly. They are all from R&D department and are in top Managerial positions like Managers and Research Director.
   - Staff-259 has the highest Yearly income of 239,988 
   - The R&D department has a total sum of yearly income of 72,435,408 followed by sales department with 37,245,492
   - HR department has the lowest total sum of yearly income with 5,030,808.
   
2. Departmental & Job Role Performances
   - The R&D department has a total sum of yearly income of 72,435,408 followed by sales department with 37,245,492
   - HR department has the lowest total sum of yearly income with 5,030,808.
   - On average, Managers have the highest sum of yearly income of 206,180.
   - Sales representatives have the lowest average of sum of yearly income of 31,512. This can be due to population.
3. %Salary hike 
   - On average, sales representatives have salary hike of 15.67% followed by Manaufacturing Directors with 15.59%.
   - Human resources staffs have the least avg salary hike of 14.81%.
5. Age band & Gender Performance
   - 35-44 have the highest sum of yearly income of 41,133,504
   - Under 25 have the least sum of yearly income of 3,094,812
   - Males have the highest sum of yearly income of 67,531,296 which is 30% higher than Females sum of yearly income 
6. Education Performance
   - Staffs with Bacherlor's degree have the highest sum of yearly income of 44,734,500 followed by those with Masters' degree
   - Doctoral degree staffs have the least sum of yearly income of 4,767,924
7. Marital status
   - Married staffs have the overall highest sum of yearly income of 54,865,692
   - Divorced staffs have the lowest with 26,629,392.
8. Strategic Implication
   - R&D department is receiving the top 5 highest salaries.
   - There is no gender equality in the organization as we have a difference of almost 21million between Males and Females.
   - Sales reps have had more salary raises than Human resources staffs, on average.
   
### Conclusion
---

The company should encourage further educational studies which will not only help boost knowledge but also help the staffs on their jobs. Also, the salary line between Top managers and junior staffs should be reviewed especially in the R&D department so staffs can receive salaries according to job experience, job knowledge and expertise and also education level.
HR should focus on bridging the gap in gender equality.
### Overall Recommendation
---
🥇💻- The R&D department and Sales Department are the most affected departments which is mostly due to low average yearly income. The company should do a review of their salaries, once their salaries are increased, there will be a reduction in the rate of attrition.🥇 💻




