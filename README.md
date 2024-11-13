# LITA_Class_Documentation
---       

[Project Overview](#project-overview)

[Data Sources](#data-sources)

[Tools Used](#tools-used)

[Data Cleaning and preparation](#data-cleaning-and-preparation)

[Exporatory Data Analysis](#exporatory-data-analysis)

[Data Analysis and Findings](#data-analysis-and-findings)

[Data Visualization](#data-visualization)




## Project Title: Employees Attrtion  Analysis
---                          

### Project Overview:
---              
The essense of this project is to analyze employee attrition patterns within the organization, focusing on how factors like job title, educational field, gender, age band, and job satisfaction impact turnover. By understanding these relationships, by analysing the various parameters in this data the insight gathered will be aimed to guide strategies for employee retention, satisfaction improvement, and optimized workforce planning.

### Data Sources:
---       
The primary source of this data is HR DATA.excel provided by LITA and this is an open sources data that can freely downloaded without any restriction, online such as kaggle or fred, data.gov as well as any other sources like industry report.

### Tools Used:
---        
- Microsoft Excel[Download Here](https://www.microsoft.com)
   1. for data storage
   2. for data cleaning
   3. for ata analysing
   4. for data visualization
- SQL- Structure query language
   1.  for quering of data
   2. for relational database stores
- Power BI-Power Business Intelligence[download Here](https://www.microsoft.com)
  - for data cleaning under table View  to quickly sort and filter data columns for more focused data inspection.
  - table View under power bi allows you to see any need for calculated columns, measures or both which can be created within the context of the table.
   - report view for data analysis and visualization
- Github account[Download Here](https://www.github.com)
  1. for portfolio building

### Data Cleaning and preparation
---
In the initial stage of the data cleaning and preparations; the following are the actions taken;
  -  the data loading and inspection through power query editor- i ensured it was put in transform state.
  -  The data transformation also took place in the table view by creating more insight
  -  ata cleaning and formatting of additional columns and measure within the context of the table.
  -  n-deptt scrutinising of data to ensure they are put in their correct usuable types.

### Exporatory Data Analysis
---
 EDA is used to analyze the data set by answering some questons about the data, such as;
  - The TotaL Nnumber of employees
  - What is the current employees in the company
  - What is the attrition Rate
  - Which department have the highest attrition
  - The percentage attrition rate per department
  - what impact does job satisfaction have on the employee turnover
  - Does Educational field and age band has impact on attrition rate.
  - The impact of Job role on the

### Action point
---
To answer the above questions the following steps were taken:
 - Calculation of attrition Count USING Calculated col Calculation of attrition rate through measure
 - The use of thebelow visualization tools was employed to generate a well organised dashboard for effective analysis:
   1. Tables
   2. Matrix
   3  Column bar chat
   4. Pie chat
   5. Donot
   6. Slicer



### Data Analysis and Findings
---
 This is where i included some basic lines of code/ queries or even some of the DAX expression used during analysis;
 In the analysis of the data given the following was found

- The total number of employees is 1470

- Attritions Count  is 237

- Total number of current employees is 1233

- Average age is 37

- Attrition rate is 16%
- Attrition by Age-band
   1. Under 25 total Attrition count is 38 Employees
   2. 25-34 Total attrition count is 112 Employees
   3. 35-44 Total attrition count is 51 Employees
   4. 45-54 Total attrition count is 25 Employees
   5. 55 and above attrition count is 11 Employees
 
   The age band with the highest attrition rate is age-band 25-34
 

### Data Visualization

- Attrition per department
There are three department in the organisation whose data is been analysed 
- Research and Development (R&D)
- Human Resourses (HR)
- Sales
  
  The visual below explicitly shows the breakdown of the employees turnover in the organistation in relation to department amongst other parameters.
  
  1. R & D has a total of 133 employees equivalent to  56.12% contribution
  2. HR has 5,06% which is equal to 12 employees
  3. Sales department has 92 employees involved amounting to  38.82% contribution.
    among the three departments, Reseach and development contributed 56.12% of attrition ie employees' turnover.
     
  The above is the percentage from each department which is summed up to make a Total of the entire 16% total attrition rate in the company.

     


![HR DATA ANALYSIS AND ATTRITION TREND](https://github.com/user-attachments/assets/b003b67c-dffd-4aaf-a497-43b0f16d3412)










The below table depicts the Education field with the highest attrition rate in relation to age band and gender


|Educational field|Total Employees|Attrition Count|Current employees|Attrition Rate |Gender Involvement|Age Band        |
|-----------------|---------------|---------------|-----------------|---------------|------------------|----------------|
|Human Resourses  |27             |7              |20               |26%            |4 Male 3Female    |All except 45years & above|
|Life Sciences    |606            |89             |517              |15%            |51 male & 38Female| All            |
|Marketing        |159            |35             |124              |22%            |35 Male           | All            |
|Medical          |464            |63             |401              |14%            |44 Male 19 Female | All            |
|Technical Degree |132            |32             |100              |24%            |22 Male 10 Female | All            |
|Other            |82             |11             |72               |13%            |10 Male 1 Female  |Except 55above  |



The Educational field with the highest attrition rate is human resources that is 26% with age band below 25, 25-34 and 35-44
followed by those having technical degree with 24% attrition rate; here all age band are involved.
this is as showed in the visualization below







![HR DATA ANALYSIS RATE FOR HUMAN RESOURSES](https://github.com/user-attachments/assets/a67c4216-50c9-49fd-a0ab-3049e75a659c)




The column chat was us to represent different age group with their total number or employees which slows that the age band between 35-44 have the highest level of employees
this perfect arrange of the age groups was gotten in absending order by creating a condition column as sorting the age  with ascending levels, re-arrangement.
Thus the table chat below shows the Job roles in which they most dissactisfied which is laboratory scientist followed by reaseach scientist


![HR TABLE ANALYSIS AND COMPUTATION](https://github.com/user-attachments/assets/7033258f-8f2d-4d32-b904-5dc61f422f9b)





![MAP OF NIGERIA SHOWING DIFFERENT STATES](https://github.com/user-attachments/assets/d7e22830-b6ce-45db-ace6-70d55c669363)




![INTERNATIONAL BREWERY SALES ANALYSIS](https://github.com/user-attachments/assets/a5f1b4ce-8187-4da7-b30b-a573f127b75f)

