# Employee Management System

A Spring Boot-based web application to manage employee records with role-based authentication, CRUD functionality, and a clean UI.

## 🛠️ Tech Stack

- Java 17
- Spring Boot 3.2.5
- Spring MVC + Spring Security
- Hibernate + JPA
- MySQL
- Thymeleaf
- Bootstrap 5
- Git & GitHub

## 📦 Features

- Login/Logout authentication (Spring Security)
- Add, update, delete, and list employees
- Custom login page
- Secure access to pages
- Responsive UI using Bootstrap
- Styled pages with custom CSS

## ⚙️ How to Run

1. **Clone the repo:**
   ```bash
   git clone https://github.com/samu22112005/employee-management-system.git
   cd employee-management-system

spring.datasource.url=jdbc:mysql://localhost:3306/your_db_name
spring.datasource.username=your_mysql_username
spring.datasource.password=your_mysql_password
spring.jpa.hibernate.ddl-auto=update

📁 Folder Structure
src/
 └── main/
     ├── java/
     │   └── com.ems/
     │       ├── config/
     │       ├── controller/
     │       ├── model/
     │       ├── repository/
     │       └── service/
     └── resources/
         ├── static/
         │   └── css/
         └── templates/

🔐 Default Login (for demo)
Update with your real user logic
Username: samu
Password: Samu2005@

You should place this file in your root folder:  
📁 `C:\Users\Downloads\employee-management-system\README.md`
