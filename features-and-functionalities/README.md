# Airbnb Clone Backend Features and Functionalities

This document provides a detailed overview of the backend requirements for the **Airbnb Clone** project. It includes all the features and functionalities required to make the application functional, scalable, and secure.

## 📌 Objective
To visually represent the backend requirements of the Airbnb Clone using a feature diagram. This includes:

- User Authentication
- Property Management
- Booking System
- Payment Integration
- Notifications
- Admin Controls
- Technical and Non-Functional Requirements

## 🛠️ Features Covered in the Diagram

### 🔑 Core Functionalities
- **User Management**
  - Sign up as Guest or Host
  - Login via Email/Password, OAuth (Google, Facebook)
  - JWT Authentication & Role-Based Access Control (RBAC)
  - Profile photo & info updates

- **Property Listings Management**
  - Add, Edit, Delete property listings
  - Include title, location, price, description, amenities, availability

- **Search and Filtering**
  - Search by location, price, guest count, and amenities
  - Pagination support

- **Booking Management**
  - Create and cancel bookings
  - Booking status (pending, confirmed, cancelled, completed)
  - Prevent double bookings

- **Payment Integration**
  - Secure payments with Stripe or PayPal
  - Host payouts
  - Multi-currency support

- **Reviews and Ratings**
  - Guests leave reviews linked to bookings
  - Hosts can reply to reviews

- **Notifications**
  - Email and in-app notifications for bookings, payments, etc.

- **Admin Dashboard**
  - Monitor/manage users, listings, bookings, and payments

### ⚙️ Technical Requirements
- Relational DB (PostgreSQL/MySQL)
- RESTful APIs (GraphQL optional)
- File storage for images (local for now, e.g., AWS S3 later)
- Email service (SendGrid/Mailgun)
- JWT + RBAC auth
- Global error handling and logging

### 🚀 Non-Functional Requirements
- Scalable architecture with load balancers
- Secure data storage (passwords, payments)
- Rate limiting and firewalls
- Redis caching
- Testing with `pytest` and automated API tests

---

## 📎 Diagram

The feature diagram has been exported as a PNG file and included below:

![Airbnb Backend Features Diagram](./airbnb-backend-features.png)

---

## 📂 Directory Structure


