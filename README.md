# 💰 Banking Application - Microservices Architecture

This is a secure, modular, and scalable **Banking Management System** built using **Spring Boot** and **Microservices**. The application provides core banking functionalities such as:

- ✅ User registration & authentication
- 💳 Account management (deposit, withdraw, transfer)
- 📄 Transaction history
- 📧 Email notifications
- 📊 Daily transaction reports

---

## 🛠️ Tech Stack

| Layer       | Technology         |
|-------------|--------------------|
| Backend     | Java, Spring Boot  |
| Architecture| Microservices, MVC |
| Database    | MySQL              |
| Testing     | JUnit, Mockito *(Optional)* |
| Others      | Maven, Spring Security, JavaMailSender, ModelMapper |

---

## 🔧 Modules

- **User Service** – Handles user registration, login, and validation
- **Account Service** – Manages account creation and balances
- **Transaction Service** – Handles deposit, withdraw, and transfer
- **Notification Service** – Sends email alerts using Thymeleaf templates

---

## 🧪 Features

- 🔐 JWT-based authentication
- 🧹 Clean code following **SOLID**, **DRY**, **KISS** principles
- 📈 Scalable design suitable for handling large traffic
- 🔁 Asynchronous email notifications
- 📂 DTO, Entity, Repository, Service, Controller layer separation

---

## 📝 How to Run

1. **Clone the repo**
```bash
git clone https://github.com/your-username/banking-app.git
cd banking-app
