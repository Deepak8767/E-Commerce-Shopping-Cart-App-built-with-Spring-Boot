# E-Commerce-Shopping-Cart-App-built-with-Spring-Boot
A full-stack E-Commerce Shopping Cart app built with Spring Boot, featuring product management, user authentication, cart, and order checkout. Uses Spring MVC, JPA, and MySQL for a scalable and secure online shopping experience.

# 🛒 Shopping Cart – Spring Boot E-Commerce Application
A full-featured shopping cart web application built using Spring Boot, Spring Security, Hibernate (JPA), and MySQL.
This project allows users to browse products, add them to a cart, and place orders securely. Admins can manage products, categories, and users through a dedicated dashboard.

# 🚀 Features
# 👤 User Features
* User registration and login (secured with Spring Security & BCrypt)
* View products by category
* Add or remove items from the cart
* Place orders with address details
* View order history

# 🧑‍💼 Admin Features
* Admin login with role-based access
* Manage categories (add, update, delete)
* Manage products (CRUD operations)
* View all orders and user details

# 🧩 Tech Stack
# 🔙 Backend
* Spring Boot – Rapid application development with embedded server and auto-configuration
* Spring MVC – Clean separation of concerns using Model–View–Controller architecture
* Spring Data JPA (Hibernate) – ORM for efficient database interaction, CRUD operations, and query optimization
* RESTful APIs – Well-structured APIs for handling client–server communication

# 🔐 Security
* Spring Security – Authentication and authorization
* Role-Based Access Control (RBAC) – Separate access for Admin and Users
* BCrypt Password Encoder – Secure password hashing
* Session Management – Secure login/logout and session handling

# 🗄️ Database
* MySQL – Relational database for persistent storage
* Hibernate ORM – Entity mapping and database abstraction
* JPA Annotations – For relationships, constraints, and schema management

# 🎨 Frontend
* Thymeleaf – Server-side template engine integrated with Spring Boot
* HTML5 – Structure and semantic layout
* CSS3 – Styling and responsive design
* Bootstrap – Mobile-first UI components and layouts
* Form Validation – Client-side & server-side validation

# ⚙️ Build & Dependency Management
* Maven – Dependency management, build lifecycle, and plugin configuration

# 🛠️ Development Tools
* IDE – Eclipse / IntelliJ IDEA
* Git & GitHub – Version control and collaborative development
* Postman – API testing and validation

# 🚀 Additional Features
* Layered Architecture – Controller, Service, Repository pattern
* Exception Handling – Global exception handling using @ControllerAdvice
* Pagination & Sorting – Efficient data handling
* Logging – Application-level logging for debugging and monitoring

# 🗂️ Project Structure
<img width="700" height="696" alt="Screenshot 2026-01-09 194347" src="https://github.com/user-attachments/assets/77cb4c90-f565-4191-b9d6-328e70d97fb1" />


# ⚙️ Configuration
# Database Setup
* Create a database in MySQL:
* CREATE DATABASE shopping_cart;

# Update your src/main/resources/application.properties file:
* spring.datasource.url=jdbc:mysql://localhost:3306/shopping_cart
* spring.datasource.username=root
* spring.datasource.password=your_password
* spring.jpa.hibernate.ddl-auto=update
* spring.jpa.show-sql=true
* spring.jpa.properties.hibernate.dialect=org.hibernate.dialect.MySQL8Dialect

# ▶️ Run the Application
* Clone the repository
* git clone https://github.com/yourusername/shopping-cart.git
* cd shopping-cart

# Build the project
mvn clean install

# Run using Maven or your IDE
mvn spring-boot:run

# Access the application
http://localhost:8780/

# 🔐 Default Roles
* Role	Description
* USER	Regular customer
* ADMIN	Access to admin panel

# 🖼️ Screenshots
# Login Page
<img width="1886" height="923" alt="image" src="https://github.com/user-attachments/assets/1c0e8d96-aeae-45ea-a324-d5a5f9bdddc6" />

# User Dashboard
<img width="1890" height="907" alt="Screenshot 2026-01-10 081812" src="https://github.com/user-attachments/assets/6834c418-c6c5-4405-a8e9-85c1dcf46cb5" />
<img width="1893" height="463" alt="Screenshot 2026-01-10 081841" src="https://github.com/user-attachments/assets/01fa9606-cb6d-427a-a926-6c798fbf338c" />
<img width="1876" height="922" alt="Screenshot 2026-01-10 082746" src="https://github.com/user-attachments/assets/989b1726-14e6-4e04-b365-9bc4b95f95da" />
<img width="1887" height="921" alt="Screenshot 2026-01-10 082842" src="https://github.com/user-attachments/assets/4c888a50-528f-487e-a099-50eab6af0864" />
<img width="1894" height="923" alt="Screenshot 2026-01-10 082901" src="https://github.com/user-attachments/assets/b6789877-3a1c-4c0c-abd0-e5e52f313a58" />
<img width="1884" height="911" alt="Screenshot 2026-01-10 083013" src="https://github.com/user-attachments/assets/0123f9d0-a386-4419-b6ca-55c5a8c640b0" />



# Admin Dashboard
<img width="1885" height="926" alt="Screenshot 2026-01-10 082145" src="https://github.com/user-attachments/assets/393b26c1-caee-4f89-9699-1b1d2541937a" />
<img width="1892" height="917" alt="Screenshot 2026-01-10 082207" src="https://github.com/user-attachments/assets/4c5843f4-597c-4dc6-8f08-a47ae130c410" />
<img width="1886" height="919" alt="Screenshot 2026-01-10 082223" src="https://github.com/user-attachments/assets/6621f931-ddba-4aa0-a07b-21d8e264ea34" />
<img width="1890" height="912" alt="Screenshot 2026-01-10 082241" src="https://github.com/user-attachments/assets/137b18f6-67c9-4743-aa8f-0c2879f5bb4c" />
<img width="1893" height="897" alt="Screenshot 2026-01-10 082318" src="https://github.com/user-attachments/assets/dc3a69e8-bffa-48cd-acec-4e10a3341c27" />
<img width="1885" height="714" alt="Screenshot 2026-01-10 082457" src="https://github.com/user-attachments/assets/8674a661-4d6b-47aa-ac40-30f17b97d94d" />

# 🤝 Contributing
* Fork this repository
* Create your feature branch (git checkout -b feature/your-feature)
* Commit your changes (git commit -m 'Add new feature')
* Push to the branch (git push origin feature/your-feature)
* Open a Pull Request
