# LITA-_CLASS_Documentation

## Employeement Table Analysis

### Project Overview
this data analysis project talks about employee table where staffid, firstname, secondname, age, state of origin, date of birth, hiredate, salary and mode of payment of each staff of orgnisation to enable us gather enough information of each staff inoder to make reasonable decision.

### Data Sources
The primary sources of data used here is internation breweries sale.csv and this is an open sources data was sent to me by my facilitator ( Mr Ade).

### Tools Used
- Microsoft excel (downnload here)(https://www.microsoft.com)
  1. for data cleaning
  2. for analysis
  3. for data visualization
- sql- sturcture query language for querying of data.
- github for creating of portfolio.
- powerBI for storing data.

- ### Data Cleaning Preparations
- in the initial phrase of the data cleaning and preparation, we perform the following action
  1. Data loading and inspection
  2. Handing missing variables
  3. Data cleaning and formatting.

 ### Exploratory Data Analysis
 EDA involved the exploring of  data to answer some questions about the data such as.
 
1• what is the overall staff strenght.

2• which of the staff is senior staff.

3• which of the staff received hightest salary.

4• mode of salary payment to each staff
        
  ### Data Analysis
   this is where we include some basic lines of code of queries or even some of the DAX expressions used during my analysis

   --- Sql---
   
   create employee table(
   staffid varchar (10) not null
   firstname varchar (255),
   secondname varchar (255),
   gender varchar (10),
   date_of_birth date,
   hiredate datetime,
   primary key (staffid)
   )
   
   insert into table employee (staffid, firstname, secondname, gender, date_of-birth, hitedate).
   
    SELECT * FROM EMPLOYEE
      
        
