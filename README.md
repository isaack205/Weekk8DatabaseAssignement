# Bookstore Database Project

## Description
This project implements a relational database schema for a bookstore management system. It includes tables for managing books, authors, publishers, customers, orders, and more. The schema is designed to handle many-to-many relationships, enforce data integrity through foreign keys, and support role-based access control for different types of users.

## How to Run/Setup the Project
1. Open your MySQL client or any database management tool (e.g., MySQL Workbench).
2. Import the `book_database.sql` file into your MySQL server:
   ```sh
   mysql -u [username] -p < book_database.sql