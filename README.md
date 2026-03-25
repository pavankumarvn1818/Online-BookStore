# 📚 Online Bookstore – MERN Stack Application

## 📌 Overview

**OnlineBookstore** is a full-stack **MERN-based web application** designed to provide a seamless online book purchasing experience. The platform supports **role-based access (User & Admin)**, enabling efficient book management and a smooth user journey from browsing to order placement.

The project demonstrates end-to-end implementation of **frontend, backend, and database integration**, along with modern UI design using Tailwind CSS.

---

## 🚀 Live Demo

🔗 https://book-frontend-iota.vercel.app/

---

## 📂 Repository

🔗 https://github.com/pavankumarvn1818/Online-BookStore.git

---

## 🧠 Key Features

### 👤 User Functionality

* 🔐 User authentication (Register / Login)
* 📖 Browse and view book details
* ❤️ Add books to favorites
* 🛒 Add books to cart
* 📦 Place orders
* 🏠 Update delivery address

---

### 🛠️ Admin Functionality

* ➕ Add new books
* ✏️ Update book details
* ❌ Delete books
* 📚 Manage overall inventory

---

## 🧱 Tech Stack

### Frontend

* **React.js** – Component-based UI
* **Redux** – State management
* **JavaScript (ES6+)** – Application logic
* **Tailwind CSS** – Modern styling

### Backend

* **Node.js** – Runtime environment
* **Express.js** – API framework

### Database

* **MongoDB** – NoSQL database

---

## 🏗️ Project Structure

```bash id="f8xq2v"
Online-BookStore/
│── client/              # React frontend
│── server/              # Node.js + Express backend
│── models/              # MongoDB schemas
│── routes/              # API routes
│── controllers/         # Business logic
│── middleware/          # Authentication & validation
│── config/              # Database configuration
```

---

## ⚙️ Core Architecture

### 1. Authentication System

* Secure user registration and login
* Role-based access (User / Admin)
* Token-based authentication

---

### 2. Book Management System

* Admin-controlled CRUD operations
* Dynamic rendering of books on frontend
* Centralized inventory handling

---

### 3. Cart & Order System

* Add/remove items from cart
* Favorites (wishlist) functionality
* Order placement workflow
* Address management for delivery

---

### 4. State Management

* Global state handled via **Redux**
* Efficient data flow between components

---

## ▶️ Installation & Setup

### 1. Clone Repository

```bash id="l1f6xv"
git clone https://github.com/pavankumarvn1818/Online-BookStore.git
cd Online-BookStore
```

---

### 2. Setup Backend

```bash id="cc0b6b"
cd server
npm install
node app.js or nodemon app.js
```

---

### 3. Setup Frontend

```bash id="f5b2kq"
cd client
npm install
npm start
```

---

### 4. Environment Variables

Create a `.env` file inside the server directory:

```env id="cz0f2u"
PORT=5000
MONGO_URI=your_mongodb_connection
JWT_SECRET=your_secret_key
```

---

## 🎥 Usage

### User Flow

* Register / Login
* Browse books
* Add to cart or favorites
* Place order
* Manage delivery address

### Admin Flow

* Login as admin
* Add, update, or delete books
* Manage inventory

---

## 📈 Learning Outcomes

This project demonstrates:

* Full-stack **MERN application development**
* Redux-based state management
* REST API design and integration
* Authentication and authorization systems
* Scalable backend architecture
* Real-world e-commerce workflow implementation

---

## 🚀 Deployment

* **Frontend** deployed on Vercel
* Backend can be deployed on platforms like Render / Railway

---

## 🔮 Future Enhancements

* ⭐ Book ratings and reviews
* 💳 Payment gateway integration
* 📦 Order tracking system
* 🔍 Advanced search and filtering
* 📱 Improved mobile responsiveness

---

## 🤝 Contribution

Contributions are welcome. Fork the repository and submit pull requests for improvements.

---

## 👤 Author

**Pavan Kumar**

---

## ⭐ Summary

**OnlineBookstore** is a scalable MERN-based e-commerce application focused on book purchasing and management.

It highlights strong capabilities in:

* Full-stack development
* State management with Redux
* Backend API design
* Role-based system architecture

Making it a solid project for **modern web development portfolios**.

---

