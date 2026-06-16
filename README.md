# 🏦 Bank ATM Simulation System

A comprehensive console-based ATM and Banking Management System developed in **Java** using **Object-Oriented Programming, File Handling, Authentication Mechanisms, Transaction Management, and Persistent Data Storage**.

This project simulates real-world ATM and banking operations with separate **Customer** and **Administrator** modules, providing secure account management, transaction processing, receipt generation, and banking administration functionalities.

---

# ✨ Features

## 👤 Customer Module

* Secure account login using Account Number and PIN
* Account auto-lock after multiple failed login attempts
* Debit (Withdraw) money from account
* Credit (Deposit) money into account
* Check current account balance
* Generate transaction receipts
* View complete customer profile
* Real-time balance updates after transactions

---

## 👨‍💼 Administrator Module

### 🔐 Secret Admin Access

A hidden administrator portal can only be accessed through a special secret account number, providing an additional layer of security.

### Admin Functionalities

* Secure administrator authentication
* Refill ATM/BANK cash reserves
* Check total ATM/BANK balance
* Unlock customer accounts
* View ATM/BANK transaction history
* Modify customer profile information
* Monitor banking operations and cash flow

---

# 💾 File Handling

The system uses text files for persistent data storage, allowing records to remain available even after the application is closed.

### Files Used

* `userInfo.txt` → Stores account number, PIN, balance, and account status
* `userProfile.txt` → Stores customer profile information
* `transactionHistory.txt` → Stores customer transaction records
* `adminLoginInfo.txt` → Stores administrator credentials
* `atmTotalMoney.txt` → Stores total ATM/BANK cash balance
* `atmAdminTransaction.txt` → Stores administrator cash refill transactions

---

# 🧾 Transaction Management

Every transaction is automatically recorded with:

* Account Number
* Transaction Type (Credit/Debit)
* Transaction Amount
* Updated Balance
* Date & Time Stamp

The system maintains complete transaction history for future reference and receipt generation.

---

# 🔒 Security Features

* Secure login authentication
* Secret Admin Access System
* Account locking after 3 failed login attempts
* Administrator-only privileged operations
* Input validation for transaction amounts
* Prevention of invalid banking operations
* Exception handling for file and server errors

---

# ✅ Validation & Error Handling

The project includes extensive validation mechanisms:

* Invalid account number detection
* Incorrect PIN handling
* Account lock protection
* Positive amount validation
* Insufficient balance checking
* ATM cash availability verification
* Invalid menu choice handling
* Missing record detection
* File access error handling
* Data update failure handling

---

# 🧠 Concepts Used

* Object-Oriented Programming (OOP)
* Classes & Methods
* File Handling
* BufferedReader & BufferedWriter
* ArrayList Collections
* Authentication Systems
* Exception Handling
* Input Validation
* Date & Time API
* Transaction Management
* Role-Based Access Control
* Console-Based User Interface

---

# 🛠 Technologies Used

* Java
* Java Collections Framework
* File Handling APIs
* LocalDateTime & DateTimeFormatter
* Exception Handling Mechanisms

---

# 🚀 How to Run

## Compile the Program

```bash
javac Question_110.java
```

## Run the Program

```bash
java Question_110
```

---

# 📋 Functionalities Included

### Customer Features

* Login Authentication
* Cash Withdrawal
* Cash Deposit
* Balance Inquiry
* Transaction Receipt Generation
* Profile Viewing
* Transaction History Recording

### Administrator Features

* Secret Admin Access
* Admin Authentication
* ATM/BANK Cash Refill
* ATM Balance Monitoring
* Customer Account Activation
* Customer Profile Modification
* ATM Transaction History Monitoring

---

# 📂 Required Files

Make sure the following files are present in the same directory before running the program:

```text
adminLoginInfo.txt
atmAdminTransaction.txt
atmTotalMoney.txt
transactionHistory.txt
userInfo.txt
userProfile.txt
```

---

# 🌟 Special Features

### 🔐 Secret Administrator Portal

Unlike traditional systems, administrator access is hidden behind a special secret account number, making it invisible to normal users.

### 🧾 Receipt Generation System

Customers can generate transaction receipts displaying transaction type, amount, balance, and timestamps in a formatted banking receipt style.

### 📊 Persistent Banking Records

All user accounts, balances, profiles, and transaction histories are stored using file handling, ensuring data persistence across program executions.

### ⏱ Timestamp-Based Transaction Tracking

Every customer and administrator transaction is recorded with precise date and time information for accurate auditing and monitoring.

---

# 👨‍💻 Developed By

## Rahul Gupta
---

# 📖 Project Overview

This project was developed to simulate the core functionalities of a real-world ATM and Banking Management System. It demonstrates practical implementation of Java programming concepts including file handling, authentication systems, transaction processing, role-based access control, exception handling, and persistent data management.

The project helped strengthen understanding of real-world banking workflows while applying Object-Oriented Programming principles and building a fully functional console-based management system.
