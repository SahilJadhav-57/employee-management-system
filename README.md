# Employee Management System 🧑‍💼

A desktop GUI application built with Python and Tkinter for managing employee records using MySQL.

## 🔧 Features
- Add, update, delete employee records
- View employee list in table
- Salary lookup
- Search and edit functionality
- MySQL backend connectivity

## 🛠 Technologies Used
- Python
- Tkinter
- MySQL
- PyMySQL
- tkinter.ttk (TreeView)


## 🚀 Getting Started
1. Install MySQL and create a database `python_db`.
2. Create table `newemp`:
```sql
CREATE TABLE newemp (
  name VARCHAR(50),
  mobno VARCHAR(15),
  dept VARCHAR(50),
  salary VARCHAR(10)
);

