# 🛒 E-Commerce Platform

## 📝 Overview
This is a full-stack e-commerce platform designed for seamless online shopping experiences. It leverages **Spring Boot** for backend development, **React** for the frontend, **MySQL** for database management, **JWT** for secure authentication, and **Stripe** for payment processing.

---

## 💻 Features
- **🔐 User Management**: Secure authentication and authorization using JWT.
- **💼 Product Management**: Add, update, and delete products with images and categories.
- **🛒 Shopping Cart**: Dynamic cart management for adding or removing items.
- **🛋️ Order Management**: Track order history and manage order status.
- **💳 Payment Integration**: Secure payment processing using Stripe API.
- **💡 Admin Dashboard**: Tools for managing products, users, and orders.
- **🔄 Responsive UI**: Built with React for a modern, user-friendly interface.

---

## 💡 Technologies Used
- **Frontend**: React, HTML, CSS, Bootstrap
- **Backend**: Spring Boot, Java
- **Database**: MySQL
- **Authentication**: JSON Web Tokens (JWT)
- **Payment Gateway**: Stripe API
- **Version Control**: Git

---

## 🔄 Installation
### 🔗 Prerequisites
- Java 11 or later
- Node.js and npm
- MySQL Database
- Stripe Account for API keys

### 🛠️ Steps
1. **Clone the repository:**
   ```bash
   git clone https://github.com/yourusername/ecommerce-platform.git
   cd ecommerce-platform
   ```

2. **Backend Setup:**
   - Navigate to the backend directory:
     ```bash
     cd backend
     ```
   - Update `application.properties` with your database credentials:
     ```properties
     spring.datasource.url=jdbc:mysql://localhost:3306/ecommerce
     spring.datasource.username=root
     spring.datasource.password=password
     stripe.api.key=your-stripe-secret-key
     jwt.secret=your-jwt-secret-key
     ```
   - Build and run the backend:
     ```bash
     mvn clean install
     mvn spring-boot:run
     ```

3. **Frontend Setup:**
   - Navigate to the frontend directory:
     ```bash
     cd frontend
     ```
   - Install dependencies:
     ```bash
     npm install
     ```
   - Start the React development server:
     ```bash
     npm start
     ```

---

## 👨‍💻 API Endpoints
| Method | Endpoint                  | Description                              |
|--------|---------------------------|------------------------------------------|
| POST   | /api/auth/register        | Register a new user                      |
| POST   | /api/auth/login           | Login and get JWT token                  |
| GET    | /api/products             | Fetch all products                       |
| POST   | /api/orders               | Create a new order                       |
| POST   | /api/payments/checkout    | Process payments using Stripe            |

---

## 👥 Contributions
Contributions are welcome! To contribute:
1. Fork the repository.
2. Create a feature branch (`git checkout -b feature/your-feature-name`).
3. Commit your changes (`git commit -m 'Add feature'`).
4. Push to the branch (`git push origin feature/your-feature-name`).
5. Create a Pull Request.

---

## 🔒 License
This project is licensed under the [MIT License](LICENSE).


