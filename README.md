# Student Registration Form

A simple **Student Registration System** built using **HTML5, CSS3, and MySQL**.
This project allows users to register student details, store them in a database, and retrieve the records using a **SELECT query**.

---

## 📌 Features

* HTML5 Student Registration Form
* CSS3 styling for clean user interface
* Stores student data in **MySQL database**
* Retrieves stored data using **SELECT query**
* Modular project structure with separate files

---

## 🧰 Technologies Used

* **HTML5** – Structure of the registration form
* **CSS3** – Styling and layout
* **MySQL** – Database to store student records
* **PHP** – Backend processing and database connection
* **XAMPP/WAMP** – Local development server

---

## 📂 Project Structure

```id="7ny0dz"
student-registration/
│
├── index.html        # Student registration form
├── style.css         # Form styling
├── db.php            # Database connection
├── insert.php        # Insert student data into database
├── view.php          # Retrieve and display student records
└── database.sql      # SQL file to create database and table
```

---

## 🗄 Database Setup

Run the following SQL in **phpMyAdmin** or MySQL Workbench:

```sql id="l15cyq"
CREATE DATABASE studentdb;

USE studentdb;

CREATE TABLE students (
    id INT AUTO_INCREMENT PRIMARY KEY,
    name VARCHAR(100),
    email VARCHAR(100),
    dob DATE,
    department VARCHAR(50),
    phone VARCHAR(15)
);
```

---

## ▶️ How to Run the Project

1. Install **XAMPP or WAMP**
2. Start **Apache** and **MySQL**
3. Copy the project folder into:

```id="cl7hqs"
htdocs/student-registration
```

4. Import the **database.sql** file into **phpMyAdmin**
5. Open your browser and visit:

```id="z1hlmt"
http://localhost/student-registration
```

---

## 📸 Application Workflow

1. User fills out the **Student Registration Form**
2. Form data is submitted to the backend
3. Data is stored in the **MySQL database**
4. Student records are retrieved using a **SELECT query**
5. Data is displayed in a table format

---

## 🚀 Future Enhancements

* Add **Edit and Delete (CRUD operations)**
* Implement **Search functionality**
* Improve UI using **Bootstrap**
* Add **JavaScript validation**
* Create **Admin dashboard**

---

## 👨‍💻 Author

** KIRAN AKKALURI**

---

## 📜 License

This project is created for **educational purposes**.
