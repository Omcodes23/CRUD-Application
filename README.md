# 🗒️ PHP Notes App (CRUD)

A simple Note Management Web App using **PHP**, **MySQL**, **Bootstrap**, and **DataTables** — add, edit, delete, and view notes.

## ⚙️ Features
- Add, edit, and delete notes  
- Responsive UI (Bootstrap 5)  
- Search/sort/pagination (DataTables)  
- MySQL backend  

## 🧩 Requirements
- PHP ≥ 7.4  
- MySQL ≥ 5.7  
- XAMPP / WAMP / LAMP  

## 🗃️ Database Setup
```sql
CREATE DATABASE notes;
USE notes;
CREATE TABLE notes (
  sno INT(6) NOT NULL AUTO_INCREMENT PRIMARY KEY,
  title VARCHAR(255) NOT NULL,
  description TEXT,
  tstamp DATETIME DEFAULT CURRENT_TIMESTAMP
);
