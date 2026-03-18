# 💡 LED House — Electrical Shop  
### *"Where every home finds its light."*

> **Software Analysis & Design Project** | Web-based E-Commerce System for a Local Electrical Shop

---

## 📋 Project Overview

**LED House** is a web-based e-commerce system designed for a small local electrical shop, enabling customers to browse, search, and purchase electrical products online.

This project focuses on the **analysis and design** of the system, including requirements specification, stakeholder identification, use case modelling, and system architecture. The goal is not to develop a fully functional application, but to design a structured solution that supports the shop's daily operations.

The system supports product management, customer orders, and multiple payment methods, combining international and local payment practices — reflecting common practices in Albania.

Additionally, the system includes basic sales analytics features to support business decision-making and profitability tracking.

---

## 🎯 Project Objectives

- Provide customers with an online platform to explore and purchase products  
- Support the shop owner in managing products and customer orders  
- Enable secure and flexible online payments  
- Improve efficiency in handling sales and product information  
- Design a simple and user-friendly interface  

---

## 💳 Payment System Design

To ensure flexibility and usability, the system implements a **hybrid payment approach**, integrating both international and local payment methods:

- PayPal – supports secure and trusted international transactions  
- 2Checkout (Verifone) – enables credit/debit card payments via hosted checkout  
- **Cash on Delivery (COD)** – allows local customers to pay upon delivery  

This combination reflects real-world e-commerce practices in Albania, where both digital and cash-based payments are widely used.

---

## ⚙️ Functional Requirements

### 🛍️ Product Management
- Add, update, and delete products  
- Display product details (name, price, description, availability)  
- Support product search and filtering  

### 👤 Customer Management
- User registration and authentication  
- View and manage customer orders  

### 🧾 Order Management
- Add products to shopping cart  
- Place orders  
- Store order details in the database  

### 💳 Payment Processing
- Select preferred payment method:
  - PayPal  
  - Credit/Debit Card (via 2Checkout)  
  - Cash on Delivery (COD)  
- Secure redirection to external payment providers  
- Confirmation of successful transactions  
- Support order placement without online payment (COD)  

---

## 📊 Sales Analytics & Business Strategies

To support business decision-making, the system includes features for tracking sales performance and enabling basic business strategies.

### 📈 Sales Tracking

- Monitor the number of times each product is purchased  
- Track total sales revenue over a selected period  
- Identify best-selling and low-performing products  

### 💰 Profit Calculation

The system allows the shop owner to analyze profitability by storing:

- **Purchase Price** (cost of acquiring the product)  
- **Selling Price** (price offered to customers)  

Based on this, the system can calculate:

- Profit per product  
- Total profit over time  
- Profit margins  

### 🧠 Business Insights

- Identify which products generate the highest profit  
- Adjust pricing strategies based on performance  
- Optimize inventory by focusing on high-demand items  

### 🏷️ Sales & Promotions

- Apply discounts to selected products  
- Create promotional campaigns (e.g., seasonal sales)  
- Highlight special offers on the homepage  

### 📊 Reporting Features

- Generate simple sales reports  
- View order history and transaction summaries  
- Analyze trends in customer purchasing behavior  

---

### ✅ Example Use Case: Analyze Profit

**Actor:** Shop Owner  

**Flow:**
1. Owner logs into the system  
2. Navigates to the sales dashboard  
3. Selects a product  
4. System displays:
   - Total units sold  
   - Purchase cost  
   - Selling price  
   - Calculated profit  
5. Owner uses this information to make pricing or stocking decisions

## 👥 Stakeholders

| Stakeholder | Role / Responsibility | Influence | Importance |
|---|---|:---:|:---:|
| 🏪 Shop Owner / Admin | Manages products, prices, and orders; controls system usage | 🔴 High | 🔴 High |
| 🧑‍💼 Store Employee | Assists in updating products and handling orders | 🟡 Medium | 🟡 Medium |
| 🛒 End Customer | Browses products and places orders | 🟡 Medium | 🔴 High |
| 🏦 Bank / Payment Provider | Processes online payments and external payment services | 🟡 Medium | 🔴 High |
| 💻 Development Team | Performs system analysis and design | 🔴 High | 🔴 High |

---

## 🔍 System Overview

### Key Features

| Feature | Description |
|---|---|
| 📦 Product Catalogue | Display products by category, price, and description |
| 🔎 Search & Filtering | Help users quickly find products |
| 👤 User Interaction | Customer interaction for browsing and ordering |
| 🛒 Shopping Cart & Checkout | Add products and complete purchases |
| 💳 Payment Integration | Payments via PayPal, 2Checkout, or COD |
| 📋 Order Management | Owner views and manages incoming orders |

---

## ⚙️ Key Quality Attributes

| Attribute | Requirement |
|---|---|
| 🔒 Security | Secure handling of user data and payments via external providers |
| 🖥️ Usability | Simple and intuitive interface suitable for all users |
| ⚡ Performance | Fast loading pages under normal usage conditions |
| 🌐 Availability | System accessible to users when needed |
| 🔧 Maintainability | Easy to update products and system content |

---

## 📐 Design Methodology

This project follows a structured **Software Analysis & Design** approach:

| Phase | Description |
|---|---|
| 📝 Requirements Elicitation | Identifying system needs based on the shop context |
| ✅ Functional Requirements | Defining system features and user interactions |
| 📊 Non-Functional Requirements | Defining performance, usability, and security needs |
| 📐 UML Modelling | Use case diagrams, activity diagrams, and system structure |
| 🏗️ System Architecture | Designing a clear and simple system structure |
| 🎨 UI/UX Design | Creating basic interface layouts and user flow |

---
