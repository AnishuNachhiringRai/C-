CREATE database data 
Use Db1
go

--create table Student(
--id int not null primary key identity(1,1),
--name nvarchar(255) not null,
--address nvarchar(255) not null,
--contact nvarchar(25) not null
--)

Alter table Student add college nvarchar(255) NULL 

insert into Student (name,address,contact,college) values 
('Anishu Rai','Siva Chowk','9810179096','Kist'),
('Nelysa Shrestha','Samakhusi','9860777527','Ace'),
('Anishu Shrestha','chabhil','9810177096','kings'),
('Nelysa Rai','boudha','9860771122','kmc')
SELECT *from student;
DELETE FROM student WHERE id=4;
DELETE FROM student WHERE id=5;
SELECT * FROM student;
Select * from student where id>3
UPDATE Student set name='alisha rai'where id=6;
create table Student(
id int not null primary key identity(1,1),




