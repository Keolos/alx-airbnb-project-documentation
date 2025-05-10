# 📄 Backend Feature Requirements – Airbnb Clone

This document outlines the technical and functional requirements for selected backend features of the Airbnb Clone project. Each feature includes details on API endpoints, request/response formats, validation rules, and performance expectations.

---

## 🧑‍💼 1. User Authentication

### 🔐 Functional Requirements
- Allow users to register (guests or hosts).
- Allow users to log in with email/password.
- Issue a JWT upon successful login.
- Secure password storage (hashed with bcrypt).
- Optional: OAuth login (e.g., Google).

### 🔌 API Endpoints

#### ➤ Register
- **POST** `/api/auth/register`
```json
Request:
{
  "first_name": "Alice",
  "last_name": "Smith",
  "email": "alice@example.com",
  "password": "SecurePass123",
  "role": "host"
}
