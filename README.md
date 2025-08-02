
# Spring Security - User Registration System

This project implements a secure **User Registration and Login System** using **Spring Boot**, **Spring Security**, **Hibernate (JPA)**, and **MySQL**. It features role-based authentication and integrates form-based login with encrypted password storage.

---

## 🔐 Features

- User registration with validation
- Secure password encryption using **BCrypt**
- Role-based access control (User, Admin, Manager)
- Login and logout functionality
- MySQL database integration
- DAO and Service layer separation using **Spring Data JPA**
- Thymeleaf templates for frontend

---

## ⚙️ Technologies Used

- Java 8+
- Spring Boot
- Spring Security
- Spring Data JPA (Hibernate)
- Thymeleaf
- MySQL
- Maven

---

## 🚀 Getting Started

### 1. Clone the Project

```bash
git clone https://github.com/your-username/spring-security-user-registration.git
cd spring-security-user-registration

### 2. Set Up MySQL Database

* Create a database named `web_customer_tracker`.
* Update the DB credentials in `src/main/resources/application.properties`:

```properties
spring.datasource.url=jdbc:mysql://localhost:3306/web_customer_tracker?useSSL=false&serverTimezone=UTC
spring.datasource.username=your_mysql_username
spring.datasource.password=your_mysql_password
```

---

### 3. Run the Application

```bash
./mvnw spring-boot:run
```

Or run it through your IDE.

---

## 📂 Project Structure

```plaintext
src/
├── main/
│   ├── java/
│   │   └── com/example/demo/
│   │       ├── config/           # Spring Security configuration
│   │       ├── controller/       # MVC controllers
│   │       ├── dao/              # JPA repositories
│   │       ├── entity/           # JPA entities
│   │       ├── service/          # Business logic layer
│   │       └── DemoApplication.java
│   └── resources/
│       ├── templates/            # Thymeleaf views
│       └── application.properties
```

---

## 👥 Default Users (for testing)

The app may initialize with some default users:

* **Username:** `john` / **Password:** `test123` → Role: `EMPLOYEE`
* **Username:** `mary` / **Password:** `test123` → Role: `MANAGER`
* **Username:** `susan` / **Password:** `test123` → Role: `ADMIN`

You can also register new users through the `/register` page.

---


---

## 📜 License

This project is open-source and free to use for personal and educational purposes.

```

---

Let me know if you want to:
- Add your name or GitHub handle as the author
- Include badges or deploy instructions
- Rename the package from `com.luv2code` to your own (I can help batch-rename all files)

```
