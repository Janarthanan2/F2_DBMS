# EXP NO 1: DATA DEFINITION LANGUGE COMMANDS IN RDBMS

## AIM:
To create a student database and execute DDL queries using SQL.


## DDL (Data Definition Language)
<div align="justify">
DDL or Data Definition Language actually consists of the SQL commands that can be used to define the database schema. It simply deals with descriptions of the database schema and is used to create and modify the structure of database objects in the database. DDL is a set of SQL commands used to create, modify, and delete database structures but not data. These commands are normally not used by a general user, who should be accessing the database via an application.
</div>
 
## List of DDL commands: 
<div align="left">
CREATE: This command is used to create the database or its objects (like table, index, function, views, store procedure, and triggers).
DROP: This command is used to delete objects from the database.
ALTER: This is used to alter the structure of the database.
TRUNCATE: This is used to remove all records from a table, including all spaces allocated for the records are removed.
RENAME: This is used to rename an object existing in the database.
</div>

## Query:
### 1) Create a table student with the following fieds rollno,name,age,address,phoneno.

### SQL QUERY: 
```SQL
create table student(roll_no numeric(5),name varchar(50),age numeric(2),address varchar(50),ph_no numeric(10));
```

### OUTPUT:
![1](https://github.com/Janarthanan2/F2_DBMS/assets/119393515/064789d1-5ff4-4050-8ab2-ec8dfc0a0e71)

### 2) Change the above student table by adding another attribute department

### SQL QUERY: 
```SQL
alter table student add department varchar(5);
```
### OUTPUT:
![2](https://github.com/Janarthanan2/F2_DBMS/assets/119393515/aa84a66c-04fd-4246-be9b-5052307e8ca7)


### 3) Drop the student table
 
### SQL QUERY: 
```SQL
drop table student;
```

### OUTPUT:
![3](https://github.com/Janarthanan2/F2_DBMS/assets/119393515/31039b58-4b57-4fa3-847e-59f9382f47d8)


### 4) Delete the student table using truncate keyword

### SQL QUERY: 
```SQL
truncate table student;
```

### OUTPUT:
![4](https://github.com/Janarthanan2/F2_DBMS/assets/119393515/eefd7371-60ec-4c8f-9b74-f0d932c20b1a)



### 5) Rename the student table to mystudent

### SQL QUERY: 
```SQL
alter table student rename to mystudent;
```

### OUTPUT:
![5](https://github.com/Janarthanan2/F2_DBMS/assets/119393515/b9014429-7fa4-4ff4-936f-6922e88dc250)

## RESULT:
   To create a student database and execute DDL queries using SQL is executed success
