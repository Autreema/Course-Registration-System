Course Registration System

Java | Spring Boot | MySQL | REST APIs | Postman

📘 Overview

The Course Registration System is a backend-focused web application developed using Java and Spring Boot to manage course enrollment processes efficiently. It provides RESTful APIs for handling students, courses, and registrations, with persistent data storage using MySQL. All APIs are tested and validated using Postman, ensuring reliability and correctness.

This project demonstrates strong backend development skills, REST API design, database integration, and real-world application architecture.

🚀 Key Highlights

RESTful API-based backend system

Student and course management

Course enrollment and withdrawal

MySQL database integration using JPA/Hibernate

Clean layered architecture (Controller, Service, Repository)

API testing and validation using Postman

Exception handling and validation support

🛠 Technologies Used
Backend

Java 17 (or Java 11/8)

Spring Boot

Spring Data JPA

Hibernate

Spring Validation

Database

MySQL

API & Testing

RESTful APIs

Postman for API testing

Tools

Maven

Git & GitHub

🏗 Architecture Overview

The application follows a layered architecture:

┌────────────────────┐
│   Controller Layer │  ← REST APIs
├────────────────────┤
│   Service Layer    │  ← Business Logic
├────────────────────┤
│   Repository Layer │  ← JPA / Database Access
├────────────────────┤
│   MySQL Database   │
└────────────────────┘

📦 Features

Create, update, delete courses

Register and manage students

Enroll students in courses

View registered courses per student

Prevent duplicate registrations

Proper HTTP status codes and error handling

📦 Installation & Setup
Prerequisites

Java

Maven

MySQL

Steps
git clone https://github.com/yourusername/course-registration-system.git
cd course-registration-system


Configure application.properties:

spring.datasource.url=jdbc:mysql://localhost:3306/course_db
spring.datasource.username=root
spring.datasource.password=yourpassword
spring.jpa.hibernate.ddl-auto=update


Run the application:

mvn spring-boot:run


Access APIs at:

http://localhost:8080

🔗 API Usage (Postman)
Add Course
POST /api/courses

Register Student
POST /api/students

Enroll Course
POST /api/enroll

Get Student Courses
GET /api/students/{id}/courses

🧪 Testing

All endpoints tested using Postman

Validated request/response payloads

Checked error scenarios and edge cases

🎯 Learning Outcomes

Hands-on experience with Spring Boot REST APIs

Database design and JPA mapping

Backend application structure

API testing and debugging

Real-world CRUD operations

🔮 Future Enhancements

JWT-based authentication

Role-based access (Admin / Student)

Pagination and filtering

Frontend integration (React/Angular)

Swagger API documentation
