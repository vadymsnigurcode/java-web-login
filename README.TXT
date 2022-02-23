Web login application using java servlets

https://www.youtube.com/watch?v=zdWfyBXO2iU

Create database script:

CREATE DATABASE youtube;
USE youtube;
create table users (
	id int auto_increment,
	uname varchar(50),
	upwd varchar(50),
	uemail varchar(50),
	umobile varchar(20),
   PRIMARY KEY (id));