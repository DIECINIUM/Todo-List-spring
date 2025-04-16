# 📝 Todo List Web Application

A simple and functional Todo list web application built with **Spring Boot** and **MySQL**, utilizing **Spring Data JPA** for data persistence.

## 🚀 Features

- Add, update, and manage your tasks
- Spring Boot backend with MySQL database
- Automatically creates the necessary table schema on startup

## 🛠️ Technologies Used

- Java 
- Spring Boot
- Spring Data JPA
- MySQL
- Maven

## 🗄️ Database Configuration

1. Create a new database in your MySQL instance.
2. Update the `application.properties` file in `src/main/resources` with your MySQL database details:

```properties
spring.datasource.url=jdbc:mysql://localhost:3306/your_database_name
spring.datasource.username=your_username
spring.datasource.password=your_password
spring.jpa.hibernate.ddl-auto=update
