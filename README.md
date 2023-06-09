# SQL Challenge

![image](https://user-images.githubusercontent.com/126301312/235184768-099093f5-38ef-4032-9377-8ef12855bb89.png)

## Background

It’s been two weeks since you were hired as a new data engineer at Pewlett Hackard (a fictional company). Your first major task is to do a research project about people whom the company employed during the 1980s and 1990s. All that remains of the employee database from that period are six CSV files.

For this project, you’ll design the tables to hold the data from the CSV files, import the CSV files into a SQL database, and then answer questions about the data. That is, you’ll perform data modeling, data engineering, and data analysis, respectively.

## Files

### [Data Folder](https://github.com/MidnightAlex6/sql-challenge/tree/main/Data)

 Listed are the files used for this assignment

 * [departments.csv](https://github.com/MidnightAlex6/sql-challenge/blob/main/Data/departments.csv)
 * [dept_emp.csv](https://github.com/MidnightAlex6/sql-challenge/blob/main/Data/dept_emp.csv)
 * [dept_manager.csv](https://github.com/MidnightAlex6/sql-challenge/blob/main/Data/dept_manager.csv)
 * [employees.csv](https://github.com/MidnightAlex6/sql-challenge/blob/main/Data/employees.csv)
 * [salaries.csv](https://github.com/MidnightAlex6/sql-challenge/blob/main/Data/salaries.csv)
 * [titles.csv](https://github.com/MidnightAlex6/sql-challenge/blob/main/Data/titles.csv)
 
### [Employee_SQL Folder](https://github.com/MidnightAlex6/sql-challenge/tree/main/Employee_SQL)

 * [Queries.sql](https://github.com/MidnightAlex6/sql-challenge/blob/main/Employee_SQL/Queries.sql) - contains all my querys for the Data Analysis portion of the assignment
 * [Table_Schema.sql](https://github.com/MidnightAlex6/sql-challenge/blob/main/Employee_SQL/Table_Schema.sql) - contains the exported postgreSQL of my entity relationship diagram

### [ERD Folder](https://github.com/MidnightAlex6/sql-challenge/tree/main/ERD)

 * [ERD_image.png](https://github.com/MidnightAlex6/sql-challenge/blob/main/ERD/ERD_image.png) - an image of my entity relationship diagram for this assignment
 * [ERD.txt](https://github.com/MidnightAlex6/sql-challenge/blob/main/ERD/ERD.txt) - file containing my ERD text

### [Resources Folder](https://github.com/MidnightAlex6/sql-challenge/tree/main/Resources)

 * [SQL_image.png](https://github.com/MidnightAlex6/sql-challenge/blob/main/Resources/SQL_image.png) - image for my ReadME file

## Instructions

This Challenge is divided into three parts: data modeling, data engineering, and data analysis.

## Data Modeling

Inspect the CSV files, and then sketch an Entity Relationship Diagram of the tables. To create the sketch, feel free to use a tool like [QuickDBD](https://app.quickdatabasediagrams.com/#/d/pXfEQb).

## Data Engineering


1. Use the provided information to create a table schema for each of the six CSV files. Be sure to do the following:


  * Remember to specify the data types, primary keys, foreign keys, and other constraints.


  * For the primary keys, verify that the column is unique. Otherwise, create a composite key, which takes two primary keys to uniquely     identify a row.


  * Be sure to create the tables in the correct order to handle the foreign keys.




2. Import each CSV file into its corresponding SQL table.

## Data Analysis

1. List the employee number, last name, first name, sex, and salary of each employee.


2. List the first name, last name, and hire date for the employees who were hired in 1986.


3. List the manager of each department along with their department number, department name, employee number, last name, and first name.


4. List the department number for each employee along with that employee’s employee number, last name, first name, and department name.


5. List first name, last name, and sex of each employee whose first name is Hercules and whose last name begins with the letter B.


6. List each employee in the Sales department, including their employee number, last name, and first name.


7. List each employee in the Sales and Development departments, including their employee number, last name, first name, and department name.


8. List the frequency counts, in descending order, of all the employee last names (that is, how many employees share each last name).
