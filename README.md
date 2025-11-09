# E-Commerce-Shopping-Cart-App-built-with-Spring-Boot
A full-stack E-Commerce Shopping Cart app built with Spring Boot, featuring product management, user authentication, cart, and order checkout. Uses Spring MVC, JPA, and MySQL for a scalable and secure online shopping experience.

# 🛒 Shopping Cart – Spring Boot E-Commerce Application
A full-featured shopping cart web application built using Spring Boot, Spring Security, Hibernate (JPA), and MySQL.
This project allows users to browse products, add them to a cart, and place orders securely. Admins can manage products, categories, and users through a dedicated dashboard.

# 🚀 Features
# 👤 User Features
User registration and login (secured with Spring Security & BCrypt)
View products by category
Add or remove items from the cart
Place orders with address details
View order history

# 🧑‍💼 Admin Features
Admin login with role-based access
Manage categories (add, update, delete)
Manage products (CRUD operations)
View all orders and user details

# 🧩 Tech Stack
Layer	Technology
Backend	Spring Boot, Spring MVC
Security	Spring Security (Authentication & Authorization)
Database	MySQL + Spring Data JPA (Hibernate)
Frontend	JSP, HTML, CSS, Bootstrap
Build Tool	Maven
IDE	Eclipse / IntelliJ IDEA

# 🗂️ Project Structure
shping_cart/
 ├── src/
 │   ├── main/
 │   │   ├── java/com/ecom/
 │   │   │   ├── controller/       # Controllers for Admin, User, and Home
 │   │   │   ├── model/            # Entity classes (Product, Cart, Category, etc.)
 │   │   │   ├── repository/       # JPA Repositories
 │   │   │   ├── service/          # Business logic layer
 │   │   │   └── config/           # Spring Security configuration
 │   │   └── resources/
 │   │       ├── static/           # CSS, JS, images
 │   │       ├── templates/        # JSP/HTML templates
 │   │       └── application.properties
 │   └── test/
 │       └── java/com/ecom/        # Unit tests
 ├── pom.xml                       # Maven dependencies
 └── README.md

# ⚙️ Configuration
# Database Setup
Create a database in MySQL:
CREATE DATABASE shopping_cart;

# Update your src/main/resources/application.properties file:
spring.datasource.url=jdbc:mysql://localhost:3306/shopping_cart
spring.datasource.username=root
spring.datasource.password=your_password
spring.jpa.hibernate.ddl-auto=update
spring.jpa.show-sql=true
spring.jpa.properties.hibernate.dialect=org.hibernate.dialect.MySQL8Dialect

# ▶️ Run the Application
Clone the repository
git clone https://github.com/yourusername/shopping-cart.git
cd shopping-cart

# Build the project
mvn clean install

# Run using Maven or your IDE
mvn spring-boot:run

# Access the application
http://localhost:8780/

# 🔐 Default Roles
Role	Description
USER	Regular customer
ADMIN	Access to admin panel

# 🖼️ Screenshots
Login Page
User Dashboard
Admin Dashboard
Cart and Checkout Page

# 🤝 Contributing
Fork this repository
Create your feature branch (git checkout -b feature/your-feature)
Commit your changes (git commit -m 'Add new feature')
Push to the branch (git push origin feature/your-feature)
Open a Pull Request
