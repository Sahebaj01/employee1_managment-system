Employee Management System using Python and MySQL
--------------------------------------------------

Project Description:
--------------------
I have created an Employee Management System using Python and MySQL. This project is developed as a part of my internship to demonstrate the use of Python for GUI development and MySQL for database handling.

This system allows basic employee management operations including:
- Adding a new employee
- Viewing all employees
- Updating employee information
- Deleting an employee
- Searching for employees

Technologies Used:
-------------------
- Python
- Tkinter (for GUI)
- MySQL (as the backend database)
- mysql-connector-python (for connecting Python with MySQL)

Features:
----------
1. Add Employee:
   - Enter employee details like name, age, gender, contact, email, etc.
   - Save it to the MySQL database.

2. View Employees:
   - Display all employee records in a table format using the GUI.

3. Update Employee:
   - Select an employee and update their information.

4. Delete Employee:
   - Remove an employee record from the database.

5. Search Employee:
   - Search for specific employees by ID, name, or other fields.

How to Run:
------------
1. Make sure MySQL server is running.
2. Run the `setup.sql` file to create the database and table.
3. Update your MySQL username and password in the SQL connection file (`db.py` or similar).
4. Run the Python GUI file (`main.py` or `ems.py`).
5. Use the GUI to perform operations like Add, Delete, Search, and Update.

Folder Structure:
------------------
- create_table.sql       : SQL script to create the database and employee table.
- db_config.py            : Python file for connecting to the MySQL database.
- emplyee_ops.py       : all operation of add Delete etc.
- main.py              : main gui file
- README.txt       : Project description and instructions (this file).

