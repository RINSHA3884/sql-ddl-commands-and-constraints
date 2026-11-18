# SQL EMPLOYEE DATABASE MANAGEMENT SYSTEM

## 1. Project Overview

This assignment focuses on creating and managing an Employee Database using MySQL. The main objective is to understand database creation, table management, data modification, and the implementation of constraints to maintain data accuracy and consistency.

The project consists of three main tables: Departments, Location, and Employees. These tables are connected using primary keys and foreign keys to establish relationships between employee records, departments, and locations.

## 2. Database and Table Creation

Created a database named **EMPLOYEE** and three tables:

- **DEPARTMENTS:** Stores department identification and department names.
- **LOCATION:** Stores location identification and location names.
- **EMPLOYEES:** Stores employee details such as employee ID, employee name, gender, age, hire date, designation, department ID, location ID, and salary.

Appropriate data types such as INT, VARCHAR, ENUM, DATE, and DECIMAL were used to define the columns.

## 3. SQL Operations Performed

### A. CREATE – Database and Table Creation

Used the CREATE DATABASE and CREATE TABLE statements to create the employee database and its three tables.

### B. ALTER – Table Structure Modification

Used ALTER TABLE to modify existing table structures. The following operations were performed:

- Added a new EMAIL column to the Employees table.
- Modified the data type of the DESIGNATION column.
- Dropped the AGE column.
- Renamed HIRE_DATE to DATE_OF_JOINING.

### C. RENAME – Table Renaming

Renamed the existing tables:

- DEPARTMENTS to DEPARTMENTS_INFO.
- LOCATION to LOCATIONS.

### D. TRUNCATE – Removing Table Records

Used TRUNCATE TABLE to remove all records from the Employees table while retaining its structure.

### E. DROP – Removing Tables and Databases

Used DROP TABLE to remove the Employees table and DROP DATABASE to delete the Employee database.

## 4. Implementation of Constraints

Constraints were implemented to maintain data integrity and prevent invalid entries.

The following constraints were used:

- **PRIMARY KEY:** Ensures that each department, location, and employee has a unique identifier.
- **UNIQUE:** Prevents duplicate department names and location names.
- **NOT NULL:** Ensures that mandatory fields such as department names, employee names, and location names cannot be left empty.
- **ENUM:** Restricts the gender field to only two accepted values: M and F.
- **CHECK:** Ensures that employee age is 18 or above.
- **DEFAULT:** Automatically assigns the current date to the HIRE_DATE field if no date is specified.
- **AUTO_INCREMENT:** Automatically generates sequential identifiers for new location records.
- **FOREIGN KEY:** Establishes relationships between the Employees table and the Departments and Location tables.

## 5. SQL Commands and Functions Used

The following SQL commands and features were practised throughout the assignment:

| SQL Command / Feature | Purpose |
|---|---|
| CREATE DATABASE | Creates a new database |
| CREATE TABLE | Creates database tables |
| USE | Selects a database |
| ALTER TABLE | Modifies table structure |
| ADD | Adds a new column or constraint |
| MODIFY | Changes a column's data type or definition |
| DROP COLUMN | Removes a column |
| RENAME COLUMN | Changes a column name |
| RENAME TABLE | Changes a table name |
| TRUNCATE TABLE | Deletes all records from a table |
| DROP TABLE | Deletes a table |
| DROP DATABASE | Deletes a database |
| PRIMARY KEY | Uniquely identifies records |
| FOREIGN KEY | Connects related tables |
| UNIQUE | Prevents duplicate values |
| NOT NULL | Prevents NULL values |
| CHECK | Enforces a specified condition |
| DEFAULT | Assigns a default value |
| AUTO_INCREMENT | Generates sequential IDs |
| DESC | Displays table structure |
| SHOW TABLES | Displays tables in a database |

## 6. Tools Used

- MySQL
- MySQL Workbench
- SQL (Structured Query Language)

## 7. Learning Outcomes

Through this assignment, I gained practical experience in:

1. Creating and managing databases and tables.
2. Understanding different SQL data types.
3. Modifying existing table structures using ALTER commands.
4. Understanding and implementing primary keys and foreign keys.
5. Applying constraints to maintain data integrity.
6. Establishing relationships between multiple tables.
7. Renaming, truncating, and dropping database objects.
8. Understanding the importance of database structure and consistency.

## 8. Conclusion

This assignment provided practical knowledge of SQL database management using MySQL. I learned how to create databases and tables, modify their structures, establish relationships, and apply different constraints to maintain data accuracy and integrity.

Overall, this project helped strengthen my foundational SQL skills and improved my understanding of relational database management systems.# sql-ddl-commands-and-constraints
