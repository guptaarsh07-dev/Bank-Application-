🏦 Java Bank Management System

A Java-based Bank Application demonstrating Object-Oriented Programming (OOP) concepts with a clean and interactive Swing GUI, integrated with a MySQL database for secure and persistent data storage.

📌 Overview

This project simulates core banking operations through a modular Java application built using strong OOP principles such as encapsulation, inheritance, abstraction, and polymorphism. The user interface is developed using Java Swing, providing an easy-to-use dashboard for managing customer accounts and performing transactions.
The backend connects to MySQL, ensuring real-time data persistence for accounts and transactions.

✨ Features

🧩 OOP-based architecture (encapsulation, inheritance, polymorphism, abstraction)

🖥 Swing GUI for all user interactions

🗄 MySQL database integration for storing accounts and transaction details

💳 Create new bank accounts

💰 Deposit and withdraw money

📄 View account details and transaction history

🔐 Input validation and error handling

🧱 Modular and extendable codebase

🧠 Tech Stack

Java (JDK 8 or above)

Swing (GUI)

MySQL / SQL Connector

JDBC

📂 Project Structure
├── src/
│   ├── BankManagement.java        # Main application file
│   ├── models/                    # Account classes, user classes
│   ├── gui/                       # Swing UI components
│   ├── database/                  # DB connection utilities
│   └── services/                  # Transaction and service logic
├── sql/                           # SQL schema (optional)
└── README.md

⚙️ Installation & Setup
1. Clone the repository
git clone <your-repo-url>
cd bank-management-system

2. Configure the MySQL database

Create a database (e.g., bankdb) and import your tables manually or through your own SQL script.

3. Add MySQL Connector JAR

Download the MySQL JDBC driver and add it to your project classpath.

4. Update DB credentials

Modify connection details in your Java code:

String url = "jdbc:mysql://localhost:3306/bankdb";
String user = "root";
String password = "yourPassword";

5. Run the application

Compile and run:

javac BankManagement.java
java BankManagement

📊 Future Enhancements

Login system with admin & user roles

Support for fund transfers

PDF statement exports

GUI redesign using JavaFX

Online banking dashboard (web version)
