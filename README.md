# 🏦 Banking Management System

A Java-based Banking Management System that allows users to create and manage bank accounts and perform basic banking transactions. The application uses **Java, JDBC, and MySQL** for application logic and database connectivity.

## 📌 About the Project

This project is designed to simulate basic banking operations through a Java application connected to a MySQL database.

The system provides functionality for user registration and login, account creation, balance management, debit and credit transactions, and transferring money between accounts.

## ✨ Features

* 👤 User Registration
* 🔐 User Login
* 🏦 Bank Account Creation
* 💰 Credit Money
* 💸 Debit Money
* 🔄 Transfer Money Between Accounts
* 💵 Balance Inquiry
* 🗄️ MySQL Database Integration
* 🔗 JDBC Connectivity

## 🛠️ Technologies Used

* **Java**
* **JDBC (Java Database Connectivity)**
* **MySQL**
* **IntelliJ IDEA**
* **Git & GitHub**

## 📂 Project Structure

```text
Banking-Management-System/
│
├── src/
│   └── BankingManagementSystem/
│       └── Java source files
│
├── Database Schema.png
├── .gitignore
├── Banking Management System.iml
└── README.md
```

## 🗄️ Database

The application uses **MySQL** as its database and connects to it using **JDBC**.

The database stores information required for user accounts and banking transactions.

A database schema diagram is included in the repository:

**`Database Schema.png`**

## ▶️ How to Run

### Prerequisites

Make sure you have the following installed:

* Java JDK
* IntelliJ IDEA
* MySQL Server
* MySQL Workbench
* MySQL JDBC Driver

### 1. Clone the Repository

```bash
git clone https://github.com/sAnk200697/Banking-Management-System.git
```

### 2. Open in IntelliJ IDEA

Open the cloned project in IntelliJ IDEA.

### 3. Configure MySQL

Create the required database in MySQL and configure the database connection details in the Java code according to your local MySQL setup.

### 4. Configure JDBC Driver

Make sure the MySQL Connector/J driver is available in the project.

### 5. Run the Application

Run the main Java class from IntelliJ IDEA.

## 🔄 Basic Workflow

```text
User Registration
       ↓
     Login
       ↓
Account Creation
       ↓
 ┌─────┼──────────────┐
 ↓     ↓              ↓
Credit Debit      Balance Check
       ↓
Money Transfer
```

## 🎯 Concepts Practiced

This project helped in practicing:

* Core Java
* Object-Oriented Programming
* Classes and Objects
* Methods and Constructors
* Exception Handling
* JDBC
* SQL
* MySQL Database Connectivity
* CRUD Operations
* Git & GitHub

## 🚀 Future Improvements

Some possible improvements for the project include:

* Transaction history
* Improved input validation
* Better exception handling
* Password security improvements
* Java Swing/JavaFX graphical interface
* More detailed account management
* Deployment as a web-based banking application

## 👨‍💻 Author

*Sankalp mishra**

GitHub: `https://github.com/sAnk200697`

## 📄 Disclaimer

This project is created for **educational purposes** to demonstrate Java, JDBC, MySQL, and basic banking-system concepts. It is not intended for handling real financial transactions.
