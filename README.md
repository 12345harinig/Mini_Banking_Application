# 💰 Mini Banking Application

A console-based **Banking Application** developed using **Java** and **MySQL**, designed to simulate basic banking operations like account creation, deposits, withdrawals, and balance checking. This mini project showcases fundamental Object-Oriented Programming (OOP) principles along with database connectivity using JDBC.

---

## 🌟 Features

- 🏦 **Account Management**
  - Create new bank accounts
  - Update or retrieve account information
  - Auto-generated unique account numbers

- 💰 **Transaction Operations**
  - Deposit and withdraw money
  - Check account balance
  - View transaction history

- 🔒 **Persistent Storage**
  - All data (accounts and transactions) stored in a **MySQL** database
  - Uses **JDBC (Java Database Connectivity)** to communicate with MySQL

- 👨‍💻 **Object-Oriented Programming**
  - Uses core OOP concepts like encapsulation, inheritance, and abstraction
  - Modular structure for easy maintenance and scalability

---

## 🛠️ Technologies Used

| Tech       | Purpose                         |
|------------|----------------------------------|
| Java       | Core application logic          |
| MySQL      | Database to store account info  |
| JDBC       | Connecting Java with MySQL      |
| SQL        | Database queries and schema     |

---

## 📂 Project Structure

MiniBankingApp/ 
├── src/ │ 
├── Account.java # Account details and behavior │
├── BankOperations.java # Business logic and user operations │ 
├── DBConnection.java # JDBC connection class
│ └── Main.java # Entry point of the application
├── database/
│ └── schema.sql # SQL file for creating necessary tables
└── README.md # Project documentation


---

## 🚀 Getting Started

### ✅ Prerequisites

- Java JDK 8 or higher
- MySQL Server
- MySQL JDBC Driver (Connector/J)

### ⚙️ Setup Instructions

1. **Clone the Repository**

```bash
git clone https://github.com/12345harinig/mini-banking-app.git
cd mini-banking-app
