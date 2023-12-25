# SQL-Project
SQL Database was created using Oracle 10g, then table was created for College students records, and crud operations was performed.

CREATE TABLE Students(
StudentID int NOT NULL UNIQUE,
Name varchar(20) NOT NULL,
DOB DATE,
MobileNo number(10),
Email varchar(25),
Address varchar(20),
City varchar(10),
Course varchar(15) NOT NULL);

INSERT INTO Students(StudentID, Name, DOB, MobileNo, Email, Address, City, Course)
VALUES ('101', 'Siddharth Gupta', '26-MAY-1997', '8564857857', 'sidgupta8564@gmail.com', 'Saket New Delhi', 'Delhi', 'SQL Developer');

SELECT * FROM STUDENTS;  (To see the table students and the record inserted)
