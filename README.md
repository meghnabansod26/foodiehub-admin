# 🍔 FoodieHub – Admin Panel (Frontend)

## 🚀 Project Overview

FoodieHub Admin Panel is a React-based web application designed for managing the Food Delivery platform.  

This application allows administrators to manage food items, orders, users, and image uploads through a secure and user-friendly interface.

The admin panel communicates with the Spring Boot backend APIs and uses JWT-based authentication for secure access.


## 🛠️ Tech Stack

- React.js
- React Router
- Axios
- Context API
- CSS / Bootstrap
- JWT Authentication
- AWS S3 (Image Upload Integration)


## 🔐 Authentication & Authorization

- Secure Admin Login
- JWT-based authentication
- Role-based access control (ADMIN)
- Protected routes for admin-only features


## 📦 Admin Functionalities

### 🥗 Product Management
- Add new food items
- Update existing items
- Delete food items
- Upload product images to AWS S3

### 📦 Order Management
- View all user orders
- Update order status
- Track payment details

### 👥 User Management
- View registered users
- Monitor user activity


## 🔗 Backend Integration

This admin panel connects to the Spring Boot backend for:

- Authentication
- Product CRUD operations
- Order management
- Image storage via AWS S3
- Payment verification


## 🏗️ Application Flow

Admin → React Admin Panel  
        ↓  
Spring Boot REST APIs  
        ↓  
MongoDB Database  
        ↓  
AWS S3 (Image Storage)


## ▶️ Run Locally

1. Clone the repository  
2. Install dependencies:

