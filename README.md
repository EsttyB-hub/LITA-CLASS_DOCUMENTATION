![Uploading incubator hub logo.jpg…]() # EXCEL, SQL & POWER BI DOCUMENTATION

## PROJECT REPORT

## INTRODUCTION TO EXCEL FUNCTIONS
Functions in Excel are numerous. On Excel workbook, Formula bar shows the functions in excel where we have Financial function, condition function, text function, data type, vlookup, statistical, engineering, cube function, information function, compability, web functions etc. It is important to know that every functions must start with Equality sign (=). Numbers in between bracket () is called Argument or parameters which can be either mandatory (must be supplied else it will return Null value) or Optional (can be ignored).

- FINANCIAL FUNCTIONS
This is where we worked out the Grand total (SUM), Average total (AVERAGE), Highest Salary(MAX), Lowest Salary (MIN) and Total Number of staff (COUNT or COUNTA).
 
  ![Screenshot (22)](https://github.com/user-attachments/assets/8f5cf76b-71aa-42e5-a633-45613d9ce1ff)

- Conditional Functions
This is where we make use of *IF* function where we calculated based on certain criteria. IF function is used to check condition and return on different Values. Also, it is used to perform logical comparison. Conditional functions include IF, IFS, SWITCH, AND, OR, XOR.
  
- It has 3 arguments:
  1. Logical test
  2. Value if true
  3. Value if false
     
![Screenshot (23)](https://github.com/user-attachments/assets/17098625-5c55-4c9e-a7f1-240560876529)

![Screenshot (31)](https://github.com/user-attachments/assets/38b6ecf3-349c-4f69-9321-702f2cf5ef23)


  - Text Functions
  - This is where we worked on Text extraction and Text Cleaning.
    
![Screenshot (28)](https://github.com/user-attachments/assets/bbdf4866-a0fa-459b-b5fe-3bcc7e7f53a7)

This is where we joined first name with email.
  
![Screenshot (24)](https://github.com/user-attachments/assets/2c1df86f-aa9e-451b-be1e-0105906fe88c)

This is where we eliminated unnecessary space from names, change names to Upper case, change names to lower case, and names properly entered and trimmed.
  
![Screenshot (25)](https://github.com/user-attachments/assets/67a66df8-e51f-4dbb-852d-a5f71c6c565d)

This is where we joined first name with surname.
  
![Screenshot (26)](https://github.com/user-attachments/assets/aa951a0b-4745-4b73-96f1-7f451d780299)

This is where we separated first name and surname from the email address.
  
![Screenshot (27)](https://github.com/user-attachments/assets/b5d2d9cb-2135-466b-b56d-de7afcd3fc16)


- Vlookup
It has 4 arguments
  1. Look Up Value (what is available in both tables you want to work on).
  2. Table Array ( the table that has what you are looking for).
  3. Column-Index-Number (the position of the column you want to return on the table array).
  4. Range-Look up (An exact match or an approximate match).
- Using Salary table

![Screenshot (29)](https://github.com/user-attachments/assets/12a4697d-d3bf-4d3e-b715-12c8c8495e98)

![Screenshot (30)](https://github.com/user-attachments/assets/9bca8dbd-93af-49f7-9040-a1dbe21e7d70)

### PIVOT TABLE
- It is a data summarized table. It is used to create report in excel.
- It has four boxes, which are:
  1. Filters
  2. Column
  3. Rows
  4. Values (which can be sum up)
 
  
## INTRODUCTION TO SQL
It is called Structured Query Language. 
It is used for storing, retrieving and managing data in relational database management system (RDBMS). It enables a user to relate databases and tables. It is a standard language for RDBMS. All the RDBMS like MySQL, PostgreSQL, Oracle, MS Access and SQL Server use SQL as their satndard database languuage.

- SQL follows the following rules: 
➢ Structure query language is not case sensitive. Generally, keywords of SQL are written in uppercase. 
➢ Statements of SQL are dependent on text lines. We can use a single SQL statement on one or multiple text line. 
➢ Using the SQL statements, you can perform most of the actions in a database. 
➢ SQL depends on tuple relational calculus and relational algebra.

### SQL Commands
 - SQL commands are instructions. It is used to communicate with the database.
 - It is also used to perform specific tasks, functions, and queries of data.
 - SQL can perform various tasks like create a table, add data to tables, drop the table, modify the table, set permission 
for users.
 
 Types of SQL Commands 
There are five types of SQL commands: 
- DDL: Data Definition Language
-  DML: Data Manipulation Language
-  DCL: Data Control Language
- TCL: Transaction Control Language
- DQL: Data Query Language


### Data Definition Language (DDL) 
DDL changes the structure of the table like creating a table, deleting a table, altering a table, etc. All the command of DDL are auto-committed that means it permanently save all the changes in the database

- Create: It is used to create a new table in the database.
- Drop: It is used to delete both the structure and record stored in the table.
- Alter: It is used to alter the structure of the database.
- Truncate: It is used to delete all the rows from the table and free the space containing the table. 

### Data Manipulation Language (DML)
DML commands are used to modify the database. It is responsible for all form of CHANGES in the database. The command of DML is not auto-committed that means it can't permanently save all the changes in the database. They can be rollback.
 Here are some commands that come under DML: 
- Insert: The INSERT statement is a SQL query. It is used to insert data into the row of a table.
-  Update: This command is used to update or modify the value of a column in the table.
-  Delete: The delete statement is used to delete existing records in a table

### Data Control Language (DCL)
 DCL commands are used to GRANT and TAKE BACK authority from any database user.
 Here are some commands that come under DCL: 
 - Grant: It is used to give user access privileges to a database.
 - Revoke: It is used to take back permissions from the user.
   
 ### Data Query Language (DQL)
 DQL is used to fetch the data from the database. It uses only one command.
 - Select: This is the same as the projection operation of relational algebra.
 It is used to select the attribute based on the condition described by WHERE clause

### Transaction Control Language (TCL)
 TCL commands are used to manage transactions in the database. These are used to manage the changes made DML 
Statement (INSERT, DELETE and UPDATE only). It also allows statements to be grouped into logical transactions
 Here are some commands that come under TCL:
- Commit command is used to permanently  save any transaction.
- Rollback: This command restores the database to last committed state. Rollback command is used to undo transactions that have not already been saved to the database. 
- Savepoint: It is used to roll the transaction back to a certain point without rolling back the entire transaction. Savepoint command is used to temporarily save a transaction so that you can rollback to that point whenever necessary.

### SQL Keys

Primary Key: A special type of key that uniquely identifies each record in a table. Each table can have only one primary key.

Foreign Key:A field in one table that uniquely identifies a row of another table, creating a relationship between the two tables.

Surrogate Key: A surrogate key is a unique identifier for each record in a table, typically created by the database itself.

Composite Key: Composite key (also known as compound key concatenated key) is a group of two or more columns that identifies each row of a table uniquely.

Candidate Key: Candidate key is a key of a table which can be selected as primary key. A table can have multiple candidate keys, out of which one can be selected as a primary key. 

Alternate key: Alternate key is a candidate key, currently not selected as a primary key of the table.

### SQL Aggregate Functions
 SQL aggregate functions are powerful tools used to perform calculations on a set of values, returning a single value that summarizes the data. They are commonly used in conjunction with the GROUP BY clause to group the data by one or more columns before applying the aggregate function.
They include, Count, Sum, Average, MIN, and MAX.

### SQL Joins
SQL JOIN means "to combine two or more tables". In SQL, JOIN clause is used to combine the records from two or more tables in a database.
They include, Inner Join, Right Join, Left Join and Full Join.

### SQL Set Operations
SQL set operations allow you to combine the results of two or more SELECT queries. These operations treat the result sets of each query as mathematical sets, enabling you to perform set operations like union, intersection, and difference on them. SQL provides the following set operations which are Union, Union All and Intersect.

### SQL Views
 An SQL View is a virtual table that is created based on the result set of a SQL query. Unlike a regular table, a view does not store data itself; instead, it dynamically retrieves data from one or more underlying tables whenever the view is queried.

### SQL CASE WHEN Statements
 The CASE WHEN statement in SQL is a conditional expression that allows you to create different outputs based on certain conditions. It is similar to the IF-THEN-ELSE logic in programming languages. CASE can be used in SELECT, UPDATE, INSERT, and ORDER BY clauses, making it very versatile.

### Writing queries on SQL 

After a successful installation of the SQL App, Open the App, Click on New query and firstly create your database to warehouse all your queries. Also, Pay attention to masterdp because that is a default database, so always change it to the database created where your queries will be saved. It is also important to save the queries written before closing the App.


## Power BI

