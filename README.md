
# 🛒 E-Commerce API Testing using Postman

## 📌 Project Overview
This project demonstrates REST API testing of an E-Commerce application using Postman and Fake Store API.  
It covers CRUD operations, authentication flow, and API validation using test scripts.

---

## 🚀 Features Tested
- GET all products
- GET single product
- POST new product
- PUT update product
- DELETE product
- Login API (Authentication)
- Token handling (Bearer Token)
- Environment variables
- Collection Runner execution
- Basic negative testing

---

## 🛠 Tools Used
- Postman
- Fake Store API
- REST APIs
- JavaScript (Postman test scripts)
- JSON

---

## 🌍 API Used
https://fakestoreapi.com

---

## 🔐 Authentication Flow
- Login API used to generate token
- Token stored in environment variable
- Token used in Authorization header (Bearer Token)

---

## 📂 Project Structure
Ecommerce-API-Testing/
├── README.md
├── Ecommerce.postman_collection.json
├── screenshots/

---

## 🧪 Sample Test Script
```javascript
pm.test("Status code is 200", function () {
    pm.response.to.have.status(200);
});
