# 💡 LED House — Electrical Shop Website
### Software Analysis & Design Project



## 📋 Project Overview

**LED House** is an e-commerce web application designed for a local electrical shop, enabling customers to browse, search, and purchase electrical products online. The platform streamlines order management for the shop owner, integrates with a third-party payment gateway for secure transactions, and connects with a logistics partner for order fulfilment and delivery tracking.

This repository contains all software analysis and design artefacts produced throughout the project lifecycle, including requirements, stakeholder analysis, use case diagrams, system architecture, and design documentation.

---

## 🎯 Project Objectives

- Provide customers with a 24/7 online storefront for electrical products
- Automate order processing and inventory management for the shop owner
- Integrate a secure, PCI-DSS compliant payment gateway
- Enable real-time order tracking via a logistics/delivery partner
- Deliver a responsive, mobile-friendly user interface

---

## 👥 Stakeholders

| Stakeholder | Role | Influence |
|---|---|---|
| Shop Owner / Administrator | Manages catalogue, orders & reporting | High |
| End Customer | Browses and purchases products online | Medium |
| Delivery / Logistics Partner | Fulfils and tracks customer orders | Medium |
| IT Development Team | Builds and maintains the platform | High |
| Payment System Provider | Processes transactions securely | Medium |

> Full stakeholder analysis is available in stakeholders_table.docx

---



## 🔍 System Overview

### Core Modules

- **Product Catalogue** — Browse and search electrical goods by category, brand, and price
- **User Accounts** — Customer registration, login, and order history
- **Shopping Cart & Checkout** — Add to cart, apply promotions, and complete purchase
- **Payment Integration** — Secure payment processing via a third-party gateway (e.g. Stripe)
- **Order Management** — Admin dashboard for processing and tracking orders
- **Delivery Integration** — Automated fulfilment data exchange with logistics partner
- **Inventory Management** — Real-time stock tracking to prevent overselling

### Key Quality Attributes

| Attribute | Requirement |
| Security | PCI-DSS compliant payment handling; encrypted user data |
| Availability | 99.9% uptime target; resilient to traffic spikes |
| Performance | Page load under 3 seconds on standard connections |
| Usability | Fully responsive design for desktop and mobile |
| Scalability | Architecture supports growth in product catalogue and users |

---

## 📐 Design Methodology

This project follows a structured **Software Analysis & Design** approach, including:

- **Requirements Elicitation** —Stakeholder interviews, use case analysis
- **Functional Requirements** — Documented user stories and system functions
- **Non-Functional Requirements** — Performance, security, and usability constraints
- **UML Modelling** — Use case, class, sequence, and activity diagrams
- **System Architecture** — Layered architecture with clear separation of concerns
- **UI/UX Design** — Wireframes and prototype mockups before implementation


*LED House - "Where every home finds its light."*
