Firstly If any user want to run this project The user have to create Database name called 'Clients' in Mysql Then user have to create Table name called 'mystore' in 
Microsoft SQL Server Management


SQL Queries to create the clients table and to insert rows: 
CREATE TABLE clients (
    id INT NOT NULL PRIMARY KEY IDENTITY,
    name VARCHAR (100) NOT NULL,
    email VARCHAR (150) NOT NULL UNIQUE,
    phone VARCHAR(20) NULL,
    address VARCHAR(100) NULL,
    created_at DATETIME NOT NULL DEFAULT CURRENT_TIMESTAMP
);

INSERT INTO clients (name, email, phone, address)
VALUES
('D Madakari Nayaka', 'madhakari1999@gmail.com', '9364764733', 'India');

