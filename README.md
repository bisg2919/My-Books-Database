# My-Books-Database
Python GUI project using Tkinter and MySQL to create a books database and perform CRUD (Create, Read, Update and Delete) operations


In MySQL Database:
 > TO Create DB:
                  CREATE DATABASE IF NOT EXISTS mybooks; 
                  
 > To Create Table:
                  CREATE TABLE IF NOT EXISTS mybooks.books(id INTEGER NOT NULL AUTO_INCREMENT PRIMARY KEY,title VARCHAR(255), author VARCHAR(255), isbn INTEGER)
 
 > To view all items:
                   SELECT * FROM mybooks.books;
