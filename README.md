# Employee Management System – Java Console App

## 📝 Overview

This is a simple **Java console-based application** developed to manage employee data using **JDBC** and a **MySQL database**. It was created during my internship as a hands-on project to apply my Java and SQL skills in a practical, real-world scenario.

## 🧰 Tech Stack

- Java (JDK 8 or above)
- JDBC
- MySQL (RDBMS)
- MySQL Connector/J

## 📂 Features

- ✅ Add new employees
- ✅ View all employee records
- ✅ Update existing employee details
- ✅ Delete employee records
- ✅ Menu-driven console UI

## ⚙️ Setup Instructions

1. **Create the Database**
   Run the following in MySQL:

   ```sql
   CREATE DATABASE employees_db;
   USE employees_db;

   CREATE TABLE employees (
       id INT AUTO_INCREMENT PRIMARY KEY,
       name VARCHAR(100),
       position VARCHAR(100)
   );
