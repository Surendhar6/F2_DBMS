# EXP NO 1: DATA DEFINITION LANGUGE COMMANDS IN RDBMS
### Date : 08/08/2023
## AIM:
To create a student database and execute DDL queries using SQL.


## DDL (Data Definition Language)
<div align="justify">
DDL or Data Definition Language actually consists of the SQL commands that can be used to define the database schema. It simply deals with descriptions of the database schema and is used to create and modify the structure of database objects in the database. DDL is a set of SQL commands used to create, modify, and delete database structures but not data. These commands are normally not used by a general user, who should be accessing the database via an application.
</div>
 
## List of DDL commands: 
<div align="justify">
CREATE: This command is used to create the database or its objects (like table, index, function, views, store procedure, and triggers).
DROP: This command is used to delete objects from the database.
ALTER: This is used to alter the structure of the database.
TRUNCATE: This is used to remove all records from a table, including all spaces allocated for the records are removed.
RENAME: This is used to rename an object existing in the database.
</div>

## Query:
### 1) Create a table student with the following fieds rollno,name,age,address,phoneno.

### SQL QUERY: 
```
create table student (RollNo NUMBER,Name char(20),Age NUMBER,Address char(20),PhoneNo NUMBER);
```

### OUTPUT:
![1 1](https://github.com/Surendhar6/F2_DBMS/assets/118352907/12f2210a-dedc-49e8-9b6c-59ed4ff2389f)

### 2) Change the above student table by adding another attribute department

### SQL QUERY: 
```
alter table student add Dept char(10);
```
### OUTPUT:
![1 2](https://github.com/Surendhar6/F2_DBMS/assets/118352907/132ff360-682d-44d1-86c1-5f2efae66a09)

### 3) Drop the student table
 
### SQL QUERY: 
```
drop table student;
```
### OUTPUT:
![1 3](https://github.com/Surendhar6/F2_DBMS/assets/118352907/20293866-b7cd-44a4-99be-b11fddb3b3c7)

### 4) Delete the student table using truncate keyword

### SQL QUERY: 
```
TRUNCATE TABLE student;
```

### OUTPUT:
![1 4](https://github.com/Surendhar6/F2_DBMS/assets/118352907/c445978f-295e-48f1-aa11-4a80dd979272)

### 5) Rename the student table to mystudent

### SQL QUERY: 
```
 RENAME student to my_student;
```

### OUTPUT:
![1 5](https://github.com/Surendhar6/F2_DBMS/assets/118352907/f7a08d1c-c769-49bf-aa51-4a1838135a1e)

### Result:
Thus the DDL queries using SQL to create a student database has been executed and verified successfully.
