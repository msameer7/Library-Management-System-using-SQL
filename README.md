# Library-Management-System-using-SQL

Project Title: Library Management System
Database Name: library_db
Author: Muhammad Sameer

## Project Overview
This project is a simple Library Management System built using SQL. It includes creating tables, adding and managing data, and running different types of SQL queries. The goal is to show how SQL can be used for managing and analyzing library data.

## 🎯 Project Goals
Set up the library_db database

![Uploading library_erd.png…]()


Create tables for:

Branches

Employees

Members

Books

Issued Status

Return Status

Perform CRUD operations (Create, Read, Update, Delete)

Use CTAS (Create Table As Select)

Run advanced SQL queries for reports and analysis

## 📁 Project Breakdown
### 1. Database and Table Creation
Created the library_db database

Made tables for different parts of the library system

Set up relationships between tables

### 2. CRUD Operations
Create: Added new book entries

Read: Selected and viewed data from tables

Update: Changed data (e.g. employee details)

Delete: Removed a member or issued record

## ✅ Example Tasks
Task 1: Add a new book:
'978-1-60129-456-2', 'To Kill a Mockingbird', 'Classic', 6.00, 'yes', 'Harper Lee', 'J.B. Lippincott & Co.'

Task 2: Update a member’s address

Task 3: Delete issued status record with ID IS121

Task 4: Show all books issued by employee E101

Task 5: List members who issued more than one book

### 3. CTAS (Create Table As Select)
Task 6: Create a summary table showing each book and total number of times it was issued

### 4. Data Analysis & SQL Reports
Example Queries
Task 7: Get all books from a specific category

Task 8: Find total rental income by category

Task 9: List members who joined in the last 180 days

Task 10: List employees with their branch manager and branch info

Task 11: Create a table of books with rental price above a limit

Task 12: Show list of books that have not been returned

Task 13: Find members with overdue books (30+ days late)

Task 14: Update book status to "yes" when returned

Task 15: Branch performance report (books issued, returned, revenue)

Task 16: CTAS - Create active_members table (issued book in last 2 months)

Task 17: Find top 3 employees who processed the most issues

Task 18: Identify members who issued damaged books more than twice

### 5. Stored Procedure
Task 19: Created a procedure to check and update book status when issued

Input: book_id

If available → update status to 'no'

If not → show message that book is not available

### 6. CTAS with Fine Calculation
Task 20: Create a new table to show overdue books and fines

Fine: $0.50 per overdue day

Shows member ID, number of overdue books, total fine, and total books issued

## 📊 Reports & Insights
Overview of how many books were issued and returned

Analysis of book categories and rental income

Employee performance and member activity reports

## ✅ Conclusion
This project shows how to use SQL to manage a library system. It includes creating a database, adding data, updating and deleting records, and writing queries for reports and analysis. It’s a good example of using SQL for real-world database work.

