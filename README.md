# SpringMVCCRUDSimple



CREATE SEQUENCE serial
 increment by 1
 start 100;

drop sequence serial;

create table emp99(
id INT NOT NULL DEFAULT NEXTVAL('serial'), 
name varchar(100),
salary INT,
designation varchar(100)
);

for Tesing git and Jenkins

final test for Jenkins and gitHub With  triger webHooks

