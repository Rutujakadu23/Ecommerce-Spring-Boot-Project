# 🛒 E-commerce Application - Spring Boot Project

A full-featured E-commerce backend application built using **Spring Boot**, designed to handle user roles (Admin, Supplier, Buyer), product management, cart, wishlist, orders, and more.

---

## 📌 Features

### 👤 Role-Based User Management
- **Admin**:
  - Manage users
  - Manage products and categories
- **Supplier**:
  - Add/update/delete products
  - View and manage orders placed by buyers
- **Buyer**:
  - Browse/search products
  - Add to cart/wishlist
  - Place orders

### 📦 Product & Category Management
- CRUD operations for categories and products
- Product image upload and display
- Search by product name/description
- Mark out-of-stock items

### 🛍️ Shopping Cart & Wishlist
- Add/remove items from cart or wishlist
- Place order from cart
- Calculate total amount during checkout

### 📑 Orders
- Create, retrieve, update, delete orders
- View order history
- Supplier can update order delivery status

---

## 🧰 Tech Stack

| Layer           | Technology                     |
|----------------|---------------------------------|
| Backend         | Spring Boot (Java 17)          |
| Database        | MySQL                          |
| ORM             | Spring Data JPA (Hibernate)    |
| Security        | Spring Security / Custom Auth  |
| API Docs        | Swagger (optional)             |
| Build Tool      | Maven                          |
| REST Client     | Postman / Angular / React      |
| File Storage    | Local file system for images   |

---

## 📁 Project Structure

