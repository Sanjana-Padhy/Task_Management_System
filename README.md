📌 Task Management System

A dynamic and secure web-based Task Management System developed using Java, JSP, Servlets, JDBC, MySQL, HTML, CSS, JavaScript, and JavaMail API.
The application helps users efficiently organize, manage, and track tasks with category-based management, authentication, and real-time task updates.


🚀 Features

✅ User Registration & Login System
✅ Session-based Authentication
✅ Category-wise Task Management

* Today Tasks
* Planned Tasks
* Personal Tasks
* Work Tasks
* Shopping Tasks

✅ Add, Edit, Delete, Complete & Undo Tasks
✅ Real-time Dashboard Task Counts
✅ OTP-based Forgot Password using JavaMail API
✅ Profile Update & Profile Picture Upload
✅ User-specific Data Isolation
✅ Responsive and Interactive UI


🛠️ Technologies Used

 💻 Frontend

* HTML
* CSS
* JavaScript
* JSP


 ⚙️ Backend

* Java
* Servlets
* JDBC


 🗄️ Database

* MySQL


 📧 Additional Technologies

* JavaMail API
* Session Management


# 🧱 Project Architecture

The project follows a basic MVC architecture:

* **View Layer** → JSP Pages
* **Controller Layer** → Servlets
* **Model Layer** → MySQL Database


 📂 Main Modules

* User Authentication
* Dashboard Management
* Task CRUD Operations
* Forgot Password (OTP Verification)
* Profile Management
* Undo Task Functionality


 🔐 Security Features

* Session-based Access Control
* Password Validation
* User-specific Task Filtering
* Secure Database Queries using PreparedStatement



 📊 Database Tables

 users

Stores user details:

* id
* name
* email
* password
* profile_pic

 tasks

Stores task details:

* id
* username
* task
* category
* status



 ⚡ How to Run the Project

1. Clone the repository
2. Import project into Eclipse
3. Configure Apache Tomcat Server
4. Create MySQL database:

```sql
CREATE DATABASE taskmanager;
```

5. Configure database credentials in `DBConnection.java`
6. Run the project on Tomcat server



 📧 OTP Email Setup

To enable Forgot Password feature:

1. Enable 2-Step Verification in Gmail
2. Generate App Password
3. Add email & app password in JavaMail configuration



 👨‍💻 Developed By

Sanjana Padhy
