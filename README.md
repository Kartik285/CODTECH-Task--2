**Name:** KARTIK
**Company:** CODTECH IT SOLUTIONS
**ID:** CT08DS6255
**Domain:** SQL
**Duration:** AUGUST 1st, 2024 to SEPTEMBER 1st, 2024
**Mentor:** Muzammil Ahmed

## Overview Of The Project

### Project : Manage the Database on Employee Management System in SQL.

![Capture 1](https://github.com/user-attachments/assets/fd055878-867f-47aa-bd0a-723307255cb1)





![Capture 2](https://github.com/user-attachments/assets/67c42f6c-b4fb-428a-839c-32c232510e51)




### OBJECTIVE

The objective of this project is to perform Explorartory SQL on an Employee Management System.

This script provides a complete setup and operational guide for managing an Employee Management System using SQL.
It covers database creation, table setup, data insertion, and various essential operations like fetching employee details, updating records, and deleting positions. The script is useful for both initial setup and ongoing management of employee data within an organization.

### This SQL script is designed to set up and manage an Employee Management System, complete with departments, job positions, employees, and salaries. Here is an overview of the key components:

## 1. Database and Tables Creation

**Database Creation:**

The employeerecords1 database is created and selected for use.

**Tables:**

Departments: Stores department information with DepartmentID, DepartmentName, and Location.
JobPositions: Stores job positions with JobPositionID, PositionTitle, and Description.
Employees: Stores employee details, linking to Departments and JobPositions.
Salaries: Stores salary records, linking to Employees.

## 2. Data Insertion

**Departments:**

Example departments like 'Engineering', 'Management', and 'IT' are added with respective locations.
Job Positions:

Example positions such as 'Software Engineer', 'HR Manager', and 'Web Developer' are added.
Employees:

Employees are added with details including FirstName, LastName, BirthDate, HireDate, DepartmentID, and JobPositionID.
Salaries:

Salary records are inserted for the employees with details of SalaryAmount and EffectiveDate.

## 3. Queries and Operations

**Fetching All Employees with Their Department and Position:**

Retrieves a list of all employees along with their department name and job position title.
Fetching Salary History for an Employee:

Retrieves salary history for a specific employee based on their EmployeeID.
Fetching All Employees in a Specific Department:

Retrieves all employees working in a specific department by DepartmentID.
Updating an Employee’s Department:

Updates an employee's department by modifying their DepartmentID.
Deleting a Job Position:

Deletes a job position only if no employees are currently assigned to it.
Fetching the Highest Salary for Each Department:

Retrieves the highest salary for each department by joining the Employees, Departments, and Salaries tables.

### TECHNOLOGY USED 

--**MariaDB** : IN this we easily store our database in relational format.
--**Auto_Increment** : In this always a unique number automatically generated.
--**Crud Operation** : In the mariadb we use crud operation for creating , for read , for update , for delete.
