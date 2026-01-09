# 📮 Postman API Testing Notes

This repository contains my personal notes on **Postman and API Testing**, created for learning, revision, and exam preparation.  
It covers basic API concepts, Simple Book API practice, and test automation using Postman.

---

## 📌 Topics Covered

### ✅ Postman Basics
- What is Postman
- HTTP Methods: GET, POST, PUT, PATCH, DELETE
- Request vs Response structure
- Status Codes (2xx, 4xx, 5xx)

### ✅ Simple Book API Practice
- GET /status — Check API status
- GET /books — List all books (with filters)
- GET /books/:bookId — Get single book
- POST /api-clients — Register API client (Authentication)
- POST /orders — Submit order
- GET /orders — View all orders
- GET /orders/:orderId — View single order
- PATCH /orders/:orderId — Update order
- DELETE /orders/:orderId — Delete order

---

## 🔐 Authentication

- Access token is generated using `POST /api-clients`
- Token is valid for **7 days**
- Required for all order-related APIs
- Token is sent in request headers for authorization

---

## 🧪 Test Automation in Postman

- Writing JavaScript in the **Tests tab**
- Checking status codes using `pm.test()`
- Parsing JSON responses
- Using `pm.expect()` for assertions
- Saving values in global variables (like orderId)
- Using Collection Runner for workflow automation

---

## 🎯 Purpose of This Repo

- For **self-study and revision**
- Helpful for **API testing beginners**
- Useful for **college practicals and viva**

---

## 🛠 Tools Used

- Postman
- Simple Book API (Demo REST API)
- Git & GitHub

---

## ✨ Author

**Aastha Jha**  
FY Computer Engineering Student  
Learning Web Development, APIs, and Data Science

---

⭐ If you are learning API testing, feel free to use these notes!
