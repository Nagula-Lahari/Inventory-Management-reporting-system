# 📦 Inventory Monitoring & Reporting System

A full-stack **Inventory Monitoring & Reporting System** built using **Spring Boot, MySQL, and REST APIs**.  
This application helps businesses efficiently manage inventory, track stock levels, and generate reports.

---

## 🚀 Features

- 🔐 User Authentication (Login/Register)
- 📦 Product Management (Add, Update, Delete, View)
- 📊 Inventory Tracking (Stock Monitoring)
- 📈 Reporting System (Inventory Reports & Analytics)
- 🔍 Search & Filter Products
- ⚡ REST API Integration
- 🗄️ Database Management with MySQL

---

## 🛠️ Tech Stack

### Backend
- Java 17
- Spring Boot
- Spring Data JPA
- Hibernate

### Database
- MySQL

### Tools & IDE
- IntelliJ IDEA
- Maven
- Postman (API Testing)

---

## 📂 Project Structure

```plaintext
inventory
├── src
│   ├── main
│   │   ├── java
│   │   │   └── com
│   │   │       └── example
│   │   │           └── inventory
│   │   │               ├── controller
│   │   │               ├── entity
│   │   │               ├── repository
│   │   │               └── service
│   │   └── resources
│   │       └── application.properties
├── pom.xml
```

---

## ⚙️ Installation & Setup

### ✅ Prerequisites

- Java 17 installed
- MySQL installed
- Maven installed
- IntelliJ IDEA / VS Code

---

## 🔽 Clone the Repository

```bash
git clone https://github.com/Nagula-Lahari/Inventory-Management-reporting-system.git
cd Inventory-Management-reporting-system
```

---

## 🛠️ Database Setup

```sql
CREATE DATABASE inventory_db;
```

---

## ⚙️ Configure application.properties

```properties
spring.datasource.url=jdbc:mysql://localhost:3306/inventory_db
spring.datasource.username=root
spring.datasource.password=yourpassword

spring.jpa.hibernate.ddl-auto=update
spring.jpa.show-sql=true
```

---

## ▶️ Run the Application

```bash
mvn spring-boot:run
```

---

## 🌐 Access the Application

```bash
http://localhost:8080
```

---

## 📊 API Endpoints

| Method | Endpoint | Description |
|--------|---------|-------------|
| GET    | /products       | Get all products |
| GET    | /products/{id}  | Get product by ID |
| POST   | /products       | Add new product |
| PUT    | /products/{id}  | Update product |
| DELETE | /products/{id}  | Delete product |



## 🧪 Testing

- Use Postman to test APIs  
- Perform CRUD operations  
- Verify database updates  

---

## 🤝 Contributing

1. Fork the repository  
2. Create your feature branch  
3. Commit your changes  
4. Push to your branch  
5. Open a Pull Request  

---

## 📜 License

This project is licensed under the MIT License.

---

## ⭐ Support

If you like this project, give it a ⭐ on GitHub!
