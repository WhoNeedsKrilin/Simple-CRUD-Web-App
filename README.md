Simple-CRUD-Web-App
This app used:

- Node.js and Express
- EJS for templating
- HTTP's GET, PUT, POST, DELETE to make it RESTful.
- MYSQL as database


create database crud;

use crud;

CREATE TABLE items (
id int(20) NOT NULL auto_increment,
name varchar(150) NOT NULL,
quantity int(150) NOT NULL,
amount varchar(150) NOT NULL,
PRIMARY KEY (id)
);
