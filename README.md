# Product Management System

📌 Project Overview  

Product Management System is a Java Spring Boot web application developed to manage product records efficiently.  
The system helps manage product details, inventory records, and product operations using Spring Boot and MySQL database connectivity.

---

# ✨ Key Features

✔ Add New Products  
✔ Update Product Details  
✔ Delete Product Records  
✔ View Product Information  
✔ User-Friendly Interface  
✔ Database Connectivity using Spring Data JPA  
✔ Efficient Product Data Management  
✔ MVC Architecture Implementation  

---

# 🧠 Why Product Management System?

Traditional product management systems are:

- Time-consuming  
- Difficult to maintain  
- Error-prone  

This project solves these issues by:

- Automating product management  
- Providing efficient CRUD operations  
- Improving inventory data handling  

---

# 🏗️ Project Folder Architecture

```text
product.management/
│
├── .mvn/
│   └── wrapper/
│
├── src/
│   ├── main/
│   │   ├── java/project/product/management/
│   │   │   ├── controller/
│   │   │   ├── dto/
│   │   │   ├── entity/
│   │   │   ├── repository/
│   │   │   ├── service/
│   │   │   └── Application.java
│   │   │
│   │   └── resources/
│   │       ├── static/
│   │       └── application.properties
│   │
│   └── test/java/project/product/management/
│
├── .gitattributes
├── .gitignore
├── mvnw
├── mvnw.cmd
└── pom.xml
```

---

# ⚙️ System Working Flow

User Request  
        ↓  
Spring Boot Controller  
        ↓  
Service Layer Processing  
        ↓  
Repository Layer (JPA)  
        ↓  
MySQL Database  
        ↓  
Product Operations  
        ↓  
Response Displayed to User  

---

# 🧩 Core Modules Explained

## Controller Module
Handles HTTP requests and application routing.

## DTO Module
Transfers data between layers securely and efficiently.

## Entity Module
Defines product database models.

## Repository Module
Performs database operations using Spring Data JPA.

## Service Module
Contains business logic and product management functionalities.

---

# 📚 Technologies Used

| Category | Technologies |
|----------|--------------|
| Backend | Java, Spring Boot |
| Frontend | HTML, CSS |
| Database | MySQL |
| ORM | Spring Data JPA |
| Build Tool | Maven |
| Server | Apache Tomcat |

---

# 🚀 Real-World Use Cases

- Product Inventory Management  
- Store Product Systems  
- Learning Spring Boot CRUD Operations  
- Backend Development Practice  

---

# ⚠️ Limitations

- Basic authentication only  
- Local database setup required  
- Not deployed on cloud  

---

# 🧪 How to Run the Project

## Step 1: Clone Repository

```bash
git clone https://github.com/Suman1-panda/product_management.git
```

---

## Step 2: Open Project

Open the project in:

- IntelliJ IDEA  
- Eclipse STS  

---

## Step 3: Configure Database

Open:

```text
src/main/resources/application.properties
```

Add your MySQL configuration:

```properties
spring.datasource.url=jdbc:mysql://localhost:3306/product_db3
spring.datasource.username=root
spring.datasource.password=root
spring.jpa.hibernate.ddl-auto=update
server.port=8082
```

---

## Step 4: Install Maven Dependencies

```bash
mvn clean install
```

---

## Step 5: Run Spring Boot Application

Run:

```bash
mvn spring-boot:run
```

OR run:

```text
Application.java
```

from your IDE.

---

## Step 6: Open in Browser

```text
http://localhost:8082
```

---

# ✅ Application Ready

---

# 🎓 Learning Outcomes

This project demonstrates:

- Spring Boot Development  
- MVC Architecture  
- CRUD Operations  
- Spring Data JPA  
- Database Connectivity  
- Backend Development  

---

# 👤 Author

Suman Panda  
🎓 MCA Graduate  
💻 Java Full Stack Developer
