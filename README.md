# 🎓 Student Management System – Frontend

A simple and user-friendly **Student Management System frontend** developed using **HTML, CSS, and JavaScript**.

This project provides a web-based interface for managing student information through separate pages for authentication, dashboard access, adding students, viewing student details, editing student records, and deleting students.

---

## 📌 Project Overview

The **Student Management System – Frontend** is the client-side application of a student management project.

It provides an easy-to-use interface for administrators to perform common student management operations.

The frontend is designed to communicate with a backend application for processing and storing student data.

---

## ✨ Features

### 🔐 Login

* Administrator login page
* Simple authentication interface
* User-friendly login form

### 📊 Dashboard

* Central system dashboard
* Navigation to student management functions
* Simple and organized user interface

### ➕ Add Student

* Add new student records
* Student information input form
* Form-based data submission

### 👁️ View Student

* View student information
* Display student records
* Retrieve student details

### ✏️ Edit Student

* Update existing student information
* Edit student details through a dedicated interface

### 🗑️ Delete Student

* Delete student records
* Dedicated deletion interface

---

## 🖥️ Application Pages

```text
Login
  │
  ▼
Dashboard
  │
  ├── Add Student
  │
  ├── View Student
  │
  ├── Edit Student
  │
  └── Delete Student
```

---

## 🛠️ Technologies Used

| Technology     | Purpose                   |
| -------------- | ------------------------- |
| 🌐 HTML5       | Web page structure        |
| 🎨 CSS3        | User interface styling    |
| ⚡ JavaScript   | Frontend functionality    |
| ☕ Java Backend | Backend/API communication |
| 🐙 Git         | Version control           |
| GitHub         | Source code management    |

---

## 📂 Project Structure

```text
student-management-front-end/
│
├── login.html
├── dashboard.html
├── add-student.html
├── view-student.html
├── edit-student.html
├── delete-student.html
├── style.css
│
└── README.md
```

The repository currently contains these seven frontend files.

---

## 🔄 Student Management Flow

```text
                 ┌──────────────┐
                 │    LOGIN     │
                 └──────┬───────┘
                        │
                        ▼
                 ┌──────────────┐
                 │  DASHBOARD   │
                 └──────┬───────┘
                        │
          ┌─────────────┼─────────────┐
          │             │             │
          ▼             ▼             ▼
       ADD           VIEW          EDIT
     STUDENT        STUDENT       STUDENT
          │             │             │
          └─────────────┼─────────────┘
                        │
                        ▼
                     DELETE
                    STUDENT
```

---

## 🎯 CRUD Operations

The frontend provides interfaces for the four main student-management operations:

| Operation  | Function                 |
| ---------- | ------------------------ |
| ➕ Create   | Add a new student        |
| 📋 Read    | View student information |
| ✏️ Update  | Edit student information |
| 🗑️ Delete | Remove a student         |

---

## 🔌 Backend Integration

This frontend is designed to work together with a backend application that handles student data and business logic.

```text
┌───────────────────────┐
│       FRONTEND        │
│                       │
│ HTML / CSS / JS       │
└───────────┬───────────┘
            │
            │ HTTP Requests
            ▼
┌───────────────────────┐
│        BACKEND        │
│                       │
│ Java / API            │
└───────────┬───────────┘
            │
            ▼
┌───────────────────────┐
│       DATABASE        │
└───────────────────────┘
```

---

## 🚀 Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/hirushannimsarapathirana-prog/student-management-front-end.git
```

### 2. Open the Project

Open the project folder using:

* Visual Studio Code
* IntelliJ IDEA
* Any modern web development editor

### 3. Run the Frontend

Because this is a static HTML/CSS/JavaScript frontend, you can open:

```text
login.html
```

directly in a browser.

For development, using **VS Code Live Server** is recommended.

---

## 🧪 Testing

The frontend can be tested by checking each application flow:

### Login

```text
Open Login
     ↓
Enter Credentials
     ↓
Login
     ↓
Dashboard
```

### Student Management

```text
Add Student
     ↓
View Student
     ↓
Edit Student
     ↓
Delete Student
```

---

## 🎨 UI Design

The application uses custom CSS to provide:

* Clean layouts
* Forms
* Buttons
* Navigation
* Student management pages
* Consistent styling across pages

The repository currently includes a shared `style.css` file for the interface styling.

---

## 🎓 Learning Objectives

This project was developed to gain practical experience with:

* HTML5
* CSS3
* JavaScript
* Web page design
* Form handling
* CRUD-based application interfaces
* Frontend/backend communication
* Basic web application architecture
* Git and GitHub

---

## 🔮 Future Improvements

Possible future improvements include:

* 📱 Responsive mobile design
* 🔐 Improved authentication
* 👤 User roles and permissions
* 🔎 Student search
* 📊 Dashboard statistics
* 📄 Pagination
* ✅ Advanced form validation
* 🎨 Improved modern UI
* 🌙 Dark mode
* 📸 Student profile images
* 🔔 Notifications
* 🧪 Frontend automated testing

---

## 👨‍💻 Author

### Hirushan Nimsara Pathirana

Software Development / Computer Science Student

GitHub:

https://github.com/hirushannimsarapathirana-prog

---

## 📄 License

This project was developed for **educational and learning purposes**.

---

## ⭐ Repository

If you find this project useful, feel free to ⭐ the repository.

**GitHub Repository:**

https://github.com/hirushannimsarapathirana-prog/student-management-front-end
