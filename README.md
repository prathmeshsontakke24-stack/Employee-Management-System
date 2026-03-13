

# Employee Management System

## Project Overview

The **Employee Management System** is a desktop-based application developed using **Java, Swing, and MySQL** to efficiently manage employee information within an organization. The system provides a simple and user-friendly interface that allows administrators to perform operations such as adding new employees, updating employee details, removing employees, and viewing employee records.

This project demonstrates the use of **Java GUI programming, database connectivity using JDBC, and CRUD operations**. The application stores employee data in a MySQL database and allows real-time management of employee records.

---

# Objectives of the Project

The main objectives of this project are:

* To automate employee record management.
* To store and manage employee details efficiently.
* To reduce manual paperwork in employee data handling.
* To demonstrate Java GUI development using Swing.
* To implement database connectivity using JDBC.

---

# Key Features

### Add Employee

The system allows administrators to add new employees by entering information such as:

* Employee ID
* Name
* Department
* Salary
* Contact details

The data is then stored in the MySQL database.

---

### View Employee

This feature allows users to view the list of all employees stored in the database. It displays detailed employee information in a structured format.

---

### Update Employee Information

Existing employee records can be updated easily. This includes modifying details such as salary, department, or contact information.

---

### Remove Employee

The system provides functionality to remove employee records from the database when an employee leaves the organization.

---

### User-Friendly Interface

The graphical interface is built using **Java Swing**, making it easy for users to interact with the system without needing technical knowledge.

---

# Technologies Used

### Programming Language

* Java

### GUI Framework

* Java Swing

### Database

* MySQL

### Database Connectivity

* JDBC (Java Database Connectivity)

### Development Environment

* IntelliJ IDEA

### Version Control

* Git and GitHub

---

# System Architecture

The project follows a simple **three-layer architecture**:

### 1. User Interface Layer

The front-end of the application built using **Java Swing**. It allows users to interact with the system.

### 2. Application Logic Layer

Contains Java classes responsible for processing employee operations such as adding, updating, or deleting employee data.

### 3. Database Layer

MySQL database that stores all employee records and related information.

---

# Project Structure

```
Employee-Management-System
│
├── src
│   └── employee
│       └── management
│           └── system
│               ├── AddEmployee.java
│               ├── UpdateEmployee.java
│               ├── RemoveEmployee.java
│               ├── View_Employee.java
│               ├── Login.java
│               ├── Main_class.java
│               ├── Splash.java
│               └── Conn.java
│
├── icons
│
├── README.md
│
└── database.sql
```

---

# How to Run the Project

### Step 1 – Clone the Repository

```
git clone https://github.com/prathmeshsontakke24-stack/Employee-Management-System.git
```

---

### Step 2 – Open in IntelliJ IDEA

Open the project folder in **IntelliJ IDEA** or any Java IDE.

---

### Step 3 – Setup MySQL Database

Create a database in MySQL:

```
CREATE DATABASE employee_management;
```

Create the required tables for storing employee information.

---

### Step 4 – Configure Database Connection

Update the database credentials in the `Conn.java` file:

* Database URL
* Username
* Password

---

### Step 5 – Run the Application

Run the main file:

```
Main_class.java
```

The application interface will open and you can start managing employees.

---

# Future Improvements

The system can be further enhanced by adding:

* Role-based authentication (Admin/User)
* Employee attendance tracking
* Salary management
* Web-based interface using Spring Boot
* Data export to Excel or PDF
* Email notification system

---

# Learning Outcomes

Through this project, the following concepts were learned:

* Java Swing GUI development
* Database integration using JDBC
* CRUD operations in MySQL
* Object-Oriented Programming concepts
* Application architecture design
* Version control using Git and GitHub

---

# Author

**Prathamesh Sontakke**

Java Developer | Information Technology

---

