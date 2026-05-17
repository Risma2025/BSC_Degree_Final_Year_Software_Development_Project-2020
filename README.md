# BSC_Degree_Final_Year_Software_Development_Project-2020
# Craft Hub: An Intermediary B2C E-Commerce website for local traditional crafts

## Project Info

- **Software Development Project Title:** Craft Hub: An Intermediary B2C E-Commerce Website for Local Traditional Crafts  
- **Author:** Fathima Risma Abdhul Fareedh  
- **Degree Program:** B.Sc. Business Information Systems (Special)  
- **University:** University of Sri Jayewardenepura, Sri Lanka  
- **Year:** 2020

---

## Executive Summary 
A full-stack B2C e-commerce platform developed to support traditional craft artisans and micro-enterprises in Sri Lanka by providing a centralized digital marketplace to attract local and international customers.

The system addresses the limitations of manual and social-media-based business operations (Facebook pages, phone orders, and paper-based records) by offering a secure, role-based web platform for product management, customer orders, supplier onboarding, and administrative control.


---

## 📌 Project Objective

Many local craft businesses rely heavily on manual operations and informal selling channels such as Facebook pages, phone calls, and handwritten records. This creates inefficiencies in order management, customer communication, and business scalability.

Craft Hub was developed to solve this problem by introducing a centralized e-commerce ecosystem where:

- Customers can browse and purchase products online
- Suppliers (craft makers) can manage products and orders
- Administrators can control users, suppliers, and product categories

This improves operational efficiency, reduces manual work, and supports digital transformation for small-scale businesses.

---

## 🚀 Core Features

### 👤 Customer Module

- Customer registration and login
- Product browsing and category filtering
- Shopping cart management
- Checkout and order placement
- Password change
- Customer profile management

### 🏪 Supplier Module

- Supplier registration and login
- Supplier account verification by admin
- Product CRUD operations
- Order management
- Supplier profile management
- Password change

### 🛡️ Admin Module

- Admin login
- Customer account management
- Supplier account activation/deactivation
- Product category management
- System monitoring and administrative control

---

## 💻 Tech Stack

### Backend

- PHP 7.3.12
- MySQL 8.0.18

### Frontend

- HTML5
- CSS3
- Bootstrap 4
- JavaScript (ES6)
- jQuery
- AJAX

### Development Environment

- Visual Studio Code
- WAMP Server
- Apache Server 2.4.41
- Windows 10

---

## 🗄️ Database Design

The system uses a relational MySQL database designed with normalized tables and structured entity relationships.

### Main Tables

- `users`
- `product`
- `cart`
- `category`
- `order`

### Key Design Principles

- Primary and Foreign Key relationships
- Role-Based Access Control (RBAC)
- Data validation constraints
- Optimized CRUD operations
- Secure session-based authentication

---

## 🔒 Security Implementation

The system includes several security-focused controls:

- Role-Based Access Control (RBAC)
- Session-based authentication using `$_SESSION`
- Access restriction for admin pages
- Supplier verification workflow before access approval
- Input validation for registration and CRUD operations
- Protected customer profile visibility

These controls were implemented to improve data confidentiality, integrity, and access management.

---

## 🧪 Testing & Validation

The project was tested using both functional and non-functional testing methods.

### Functional Testing

- Unit Testing
- Integration Testing
- System Testing
- Acceptance Testing

### Non-Functional Testing

- Performance Testing
- Security Testing
- Usability Testing
- Compatibility Testing

### Tested Scenarios

A total of 24 test cases were validated successfully, including:

- Login validation
- Registration workflows
- Product management
- Category management
- Cart operations
- Order placement
- Password changes
- Supplier activation

---

## ⚠️ Current Limitations

- Online payment gateway is not implemented
- Customers cannot cancel placed orders

---

## 🔮 Future Enhancements

Planned improvements include:

- Online payment integration (card payments)
- Customer order cancellation within a limited time
- Delivery tracking system
- Enhanced reporting dashboard
- Better supplier analytics
- Improved UI/UX responsiveness

---

## 📚 Academic Context

This project was developed following a structured Software Development Life Cycle (SDLC), including:

- Requirement Analysis
- System Design
- Database Engineering
- Interface Development
- Testing and Evaluation
- Performance Review

The project demonstrates practical implementation of Business Information Systems concepts through a real-world software solution.

---

## 📄 License

This project was developed for academic purposes as a university final year project.

---
