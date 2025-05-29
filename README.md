# Corporate-Data-Management-System

# Project Summary:

This project involves creating and managing a basic Employee and Department 
Management System using SQL. The project aims to help students understand how to design 
databases, insert records, and manage relationships between tables. Students will create two 
tables—Employees and Departments—populate them with data, and execute various INSERT 
queries based on real-world scenarios. Through this project, students will learn how to efficiently 
handle data and simulate operations in an organizational setup.

# Instructions:

1. Database Setup
o Create a database called CompanyDB.
o Design and create the following two tables with the specified columns:
Departments Table:
▪ DepartmentID (Primary Key, Auto Increment)
▪ DepartmentName (VARCHAR, Not NULL)
▪ Location (VARCHAR)
▪ HeadOfDepartment (VARCHAR)
▪ AnnualBudget (DECIMAL)
Employees Table:
▪ EmployeeID (Primary Key, Auto Increment)
▪ FirstName (VARCHAR, Not NULL)
▪ LastName (VARCHAR)
▪ DepartmentID (Foreign Key referencing Departments)
▪ Salary (DECIMAL, Not NULL)
▪ DateOfJoining (DATE)
▪ Email (VARCHAR, UNIQUE, Not NULL)
2. Populate Data
o Insert 10 records into the Departments table.
o Insert 40 records into the Employees table.
3. Execute Situational INSERT Queries
o Based on the 10 given scenarios, execute the provided INSERT queries to 
simulate real-world operations such as hiring employees, creating new 
departments, and managing departmental assignments.
o Ensure proper formatting of data (e.g., dates in YYYY-MM-DD format, emails 
unique).
4. Project Submission Requirements:
o SQL script containing table creation statements.
o SQL script for inserting all records into both tables.
o Executed INSERT queries for the 10 scenarios.
o Exported database structure and data (e.g., .sql or .csv file).
5. Evaluation Criteria:
o Correctness of database design.
o Proper execution of the given situational INSERT queries.
o Accuracy of relationships between Employees and Departments.
o Formatting and cleanliness of SQL code.

# Expected Outcome:

By completing this project, students will:
• Gain hands-on experience with SQL database design and management.
• Understand how to use INSERT queries for real-world business operations.
• Learn to manage relationships between tables using Primary Keys and Foreign Keys.
• Enhance their ability to write clean and efficient SQL queries.
• Build confidence in handling data within an organizational context
