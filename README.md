# HR_Data

## PROJECT OVERVIEW
Employee attrition most times is a critical concern in most organization or businesses, especially when the rate is high. This project focuses on analysing employee attrition data to understand that influences employee turnover in the organization. The goal of this analysis is to identify patterns, and key drivers of attrition, so implemention can be done by organiztion if attrition rate is high.

## OBJECTIVES
- Analyse employee demographics, job roles, and satisfaction levels to identify trends to attrition
- Determine which factor have the most significant impact on employee turnover.
- Provide actionable insight to help HR department improve employee retention strategies

## DATA DESCRIPTION 
- Datasets: The datasets includes various attribute of employee such as:
   - EmployeeID, Age, Gender, Department, Job role
   - Job Satisfaction
   - Attririon (whether the employee left the organization or not)
   - OvertTome, Work Life Balance

## DATA CLEANING AND PREPROCESSING
- Dataset was scanned for duplicte and missing values
- I converted the first row to headings becaust the headings were written columns instead of a proper heading title
- I created new features such as Attrition count, Age sort, job satisfaction rating using conditional column

## EXPLORATORY DATA ANALYSIS (EDA)
- I analysed the distribution of employees who have left verses current employess
- I visualized trends using Donut chart, clustered column chart, pie chart, slicer of filter, and matrix

## DATA VISUALIZATION
Key insights were visualized using Power BI library 
- Total Number of Employee: I checked out for the total number of employee using a card chart (Q/A chart was also able to achieve that too, but I observed that filters can not be 
  implemented using the the Q/A chart)
- Total Number of Attrition: I also looked out for the number of persons that have left the organization using Card chart
- Total Number of Current Emloyee: I looked out for the total number of current employee using card chart
- Attrition Rate: Attrition rate was also necessary to be checked to determine if the company is heathy or not and also to determine turnoever
- Average Age: This was determine to know the average age of employees and a Card chart was used for visualization 
- Attrition Count by Department: This was visualized to find out the department with the highest attrition level, Donut chart  was used for visualization, which showed that R&D have the 
  higest attrition rate with 20 total number of attrition. 
- Attrition Count by Educational Field: This was visualized using a pie chart. The total number of attrition by educational feild was from the is as follow; life sciences > medical > 
  marketing > technical degree > other > human resources 
- Attrition Count by Gender: Attrition was checked by gender using a pie chart, with the male gender having the higest attrition rate (150) and the female with the attrition rate of 87
- Attrition based on Age groups and Gender: Attrition was also checked by age group and gender to know the age group of of the differnt gender that left the company the most.
  - Attrition under age 25
  - Attrition of 25 - 34
  - Attrition of 35 - 44
  - Attrition of 44 - 55
  - Attrition over 55
- 
