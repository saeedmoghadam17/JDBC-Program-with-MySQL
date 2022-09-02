# Java-Console-Program-connection-to-MySQL-Database
Java console program that views, inserts, and updates staff information stored in a MySQL database, as shown in the following figure. 

create table Staff (

  id char(9) not null,
  
  lastName varchar(15),
  
  firstName varchar(15),
  
  mi char(1),
  
  address varchar(20),
  
  city varchar(20),
  
  state char(2),
  
  telephone char(10),
  
  email varchar(40),
  
  primary key (id)
);

Console application takes arguments through the command line for view the entries, insert an entry, and update staff information of an entry.
