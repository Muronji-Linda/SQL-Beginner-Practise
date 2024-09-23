# SQL Beginner Practice: Embarking on a Data Journey! 🚀

Welcome to my SQL adventure! I'm excited to share my journey into the world of data science and analytics, focusing on SQL for data analysis. I recently tackled an engaging assignment from Shalinii’s beginner guide, and it was a fantastic experience! 

🔗 **Check out the assignment here:** [Shalinii's Guide](https://x.com/maybeshalinii/status/1827292296825749795?t=VroEtWLoVs1J7csnziOWfA&s=08)

## Project Overview

### 1. Create a Table
I kicked things off by creating a database called `project_database` and a table named `students`. Here’s the structure:
- **Student_id**: INTEGER, auto-incremented, primary key
- **First_name**: CHARACTER, 50 characters max
- **Last_name**: CHARACTER, 50 characters max
- **Birth_date**: DATE
- **Enrollment_date**: DATE

### 2. Alter the Table
I added an **email** column, character type limited to 100 characters, using the `ALTER TABLE` function.

### 3. Insert Data
I inserted three rows into the `students` table using the `INSERT INTO` statement.

### 4. Update Data
Updated the email address for the student with `student_id = 1` using the `UPDATE` statement.

### 5. Delete Data
Removed a row from the table using the `DELETE FROM` command.

### 6. Commit Changes
I added a row to the table and committed the changes to save them.

### 7. Rollback
Utilized the `ROLLBACK` function to undo committed changes when necessary.

### 8. Create and Use a Savepoint
Created a savepoint to manage complex transactions, allowing selective rollbacks.

### 9. Create a User and Grant Privileges
I created a user (`user_1`) and granted them access to the table using SQL privileges.

### 10. Revoke Privileges
Used the `REVOKE` command to remove the user’s access.

### 11. Count Rows
Utilized the `COUNT` function to determine the total number of rows in the table.

### 12. Average Calculation
In a new database, `nfl_data`, I used the `AVG` function to find the average wins in the `standings` table.

### 13. Maximum Calculation
Employed the `MAX` function to identify the maximum losses in the `standings` table.

### 14. Inner Join
Learned to use `INNER JOIN` to combine rows from two or more tables based on related columns, retrieving only matching records.

### 15. Left Join
Explored `LEFT JOIN` to get all records from the left table and matched records from the right, filling in `NULL` for unmatched entries.

### 16. Cross Join
Used `CROSS JOIN` to create a Cartesian product, combining every row from one table with every row from another.

### 17. Right Join
Implemented `RIGHT JOIN` to ensure all records from the right table are included, with `NULL` values for non-matching records from the left.

---

If you're also diving into SQL or have tips and resources for budding data analysts, I’d love to connect and learn together. Here’s to new beginnings and data-driven adventures! 📊💡

---

Feel free to explore the code and concepts in this repository, and let's embark on this data journey together! 🌟
