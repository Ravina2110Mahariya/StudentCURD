# # Student CRUD API - Spring Boot

This is a Student Management System using Spring Boot with MySQL.

## 🔧 Technologies Used
- Java 17
- Spring Boot
- Spring Data JPA
- MySQL
- Postman (API Testing)

## 📦 Features
- Register new students (POST)
- View all students (GET)
- Update student data (PUT)
- Delete student (DELETE)

## 📂 Project Structure
- `controller/` – REST Controllers
- `service/` – Business Logic
- `repository/` – DB Interactions
- `model/` – Student Entity

## 💾 MySQL Configuration (in `application.properties`)
```properties
spring.datasource.url=jdbc:mysql://localhost:3306/studentdb
spring.datasource.username=root
spring.datasource.password=2110@
spring.jpa.hibernate.ddl-auto=update
