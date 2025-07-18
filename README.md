# Bank-Management-System
# Bank Management System 🏦

## 🔧 Tech Stack
Python | MySQL | Object-Oriented Programming | CLI

## 🚀 Overview
Bank Management System is a command-line based application developed using Python and MySQL. It allows users to perform essential banking operations such as creating accounts, depositing and withdrawing funds, and viewing account information — all while storing data securely in a MySQL database.

This project helped me strengthen my backend development skills and deepen my understanding of databases, file structure, and logic handling.

## 🎯 Features
- Create new bank accounts
- Deposit and withdraw money
- Check balance and account details
- Modify or delete account records
- Backend MySQL integration for persistent data storage
- Clean and interactive command-line interface

## 🗃️ Database Schema

```sql
CREATE TABLE accounts (
  account_id INT PRIMARY KEY AUTO_INCREMENT,
  name VARCHAR(255),
  email VARCHAR(255),
  balance FLOAT
);

