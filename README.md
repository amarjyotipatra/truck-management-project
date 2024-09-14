In this project, we have created a CRUD operations and connect our project to truckMgt database using sql connector in JDBC.
You can create truckMgt database using mysql workbench and create a table called truck. 
You can use below commands to create database and set default port to 3306 to connect locally.
```
create database truckMgt;
use truckMgt;
create table truck(
id int primary key auto_increment,
  name varchar(30),
  model varchar(30),
  capacity int,
  driver_name varchar(50)
);

select * from truck;
```
