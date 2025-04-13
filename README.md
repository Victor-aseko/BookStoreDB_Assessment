# BookStoreDB_Assessment

# Bookstore Database Project

Overview

This project simulates a real-world Bookstore management system using **MySQL**. It includes a relational database design that stores information about books, authors, customers, orders, and more.

Tools Used
-MySQL: For database creation and management
-Draw.io: For visualizing the Entity-Relationship Diagram (ERD)

Objectives
- Design and implement a normalized database
- Create and populate multiple related tables
- Apply user roles and permissions for secure access
- Query and analyze bookstore data efficiently

Database Schema
Key tables include:
- `book`, `author`, `book_author`
- `customer`, `customer_address`, `address`, `country`
- `cust_order`, `order_line`, `order_status`, `order_history`
- `publisher`, `book_language`, `shipping_method`

> See `ERD.png` for the full diagram.

Setup Instructions

1. Create the Database
```sql
CREATE DATABASE bookstore_db;
USE bookstore_db;

