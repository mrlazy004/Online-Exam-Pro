# 📝 Online Exam Pro

A secure and user-friendly web-based examination platform built using **Spring Boot**, designed to simplify online assessments for both **students** and **administrators**.

The project is live at: https://onlineexampro.onrender.com/

---

## 🚀 Project Overview

The **Online Exam System** provides a complete solution for conducting timed online exams.  
Students can attempt exams and view results instantly, while administrators can create, manage, and analyze exams efficiently.

The system emphasizes **security**, **reliability**, and **ease of use**, making it suitable for educational institutions and training platforms.

---

## ✨ Key Features

### 👨‍🎓 For Students
- Take **timed online exams**
- Get **instant scores** after submission
- Review submitted answers
- Track performance through dashboards and analytics

### 👨‍💼 For Admins
- Create, edit, and manage exams
- Add and manage exam questions
- Manage student accounts
- View detailed exam analytics and results

### 🔐 Secure & Reliable
- Secure authentication and role-based access
- Automatic exam submission when time expires
- Persistent data storage
- Session-safe exam handling

---

## 🛠️ Tech Stack

### Backend
- **Java 17**
- **Spring Boot 3**
- **Spring MVC**
- **Spring Security**
- **Spring Data JPA (Hibernate)**

### Database
- **H2 (File-based)** – default  
- Supports **MySQL** (configurable)

### Frontend
- **HTML5**
- **CSS3**
- **JavaScript**
- **Thymeleaf**

### Tools & Build
- **Maven**
- **Git & GitHub**

---

## 📂 Project Structure
src/main/java
└── com.example.exam
├── controller
├── service
├── repository
├── model
└── OnlineExamApplication.java

src/main/resources
├── templates
│ ├── login.html
│ ├── register.html
│ ├── dashboard.html
│ └── index.html
├── static
│ ├── css
│ └── js
└── application.properties


---

## ⚙️ Configuration

### `application.properties`

```properties
spring.application.name=online-exam
server.port=${PORT:8080}

spring.datasource.url=jdbc:h2:file:./data/examdb
spring.datasource.driverClassName=org.h2.Driver
spring.datasource.username=sa
spring.datasource.password=password

spring.h2.console.enabled=true

spring.jpa.hibernate.ddl-auto=update
spring.jpa.show-sql=true
▶️ Running the Project Locally
Prerequisites

Java 17+

Maven

Steps
git clone https://github.com/your-username/onlineexampro.git
cd onlineexampro
mvn spring-boot:run


Visit:
👉 http://localhost:8080

Username: admin
Password: adminpass

The Project is live at: https://onlineexampro.onrender.com/
📌 Future Enhancements

Question categories & difficulty levels

Exam scheduling

Certificate generation

Email notifications

REST API support

JWT-based authentication

React / Angular frontend

👨‍💻 Author

Beerappa K B

GitHub: https://github.com/mrlazy004

📄 License

This project is licensed under the MIT License.
Feel free to use, modify, and distribute.

