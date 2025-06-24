# 📚 Bookstore Management System

A simple Bookstore CRUD web application built with Spring Boot, Spring MVC, and MySQL. This project allows users to add, view, update, and delete books from a database.

---

## 🚀 Features

- Add a new book with title, author, price, and category
- View a list of all books
- Update book details
- Delete a book
- Responsive frontend using Thymeleaf
- Integrated with MySQL database

---

## 🛠️ Tech Stack

- **Backend:** Java, Spring Boot, Spring MVC, Spring Data JPA
- **Frontend:** HTML, CSS, Bootstrap, Thymeleaf
- **Database:** MySQL
- **Build Tool:** Maven

---


---

## ⚙️ Setup Instructions

### Prerequisites:
- Java 17+
- Maven
- MySQL installed and running

### Steps to Run:


1. **Clone the repository**
   ```bash
   git clone https://github.com/damon005/Bookstore.git
   cd bookstore


2.  **Create the database**

Mysql:
  CREATE DATABASE bookstore_db;


 3.  **Configure DB credentials**
       Open src/main/resources/application.properties and update:

       properties: 
            spring.datasource.url=jdbc:mysql://localhost:3306/bookstore_db
            spring.datasource.username=root
            spring.datasource.password=yourpassword


 4.  **Run the application**
          mvn spring-boot:run


 5.   **Access in browser**
          http://localhost:8080/books


 ### Screenshot

 IMG - 1:  Bookstore Home
![Alt Text](https://github.com/damon005/Bookstore/blob/main/assets/Screenshot%202025-06-21%20094129.png)

 IMG - 2:  New Book Register
 ![Alt Text](https://github.com/damon005/Bookstore/blob/main/assets/Screenshot%202025-06-21%20094144.png)

 IMG - 3:  Available Books
 ![Alt Text](https://github.com/damon005/Bookstore/blob/main/assets/Screenshot%202025-06-21%20094200.png)

 IMG - 4:  My Books 
 ![Alt Text](https://github.com/damon005/Bookstore/blob/main/assets/Screenshot%202025-06-21%20094211.png)

 
   
