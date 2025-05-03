# 📬 Postman Assignment No. 5 – API & Postman

This repository contains the complete solution for **Assignment No. 5** using [Postman](https://www.postman.com/) .The goal is to demonstrate practical usage of all HTTP methods and Postman testing features.

---

## 📁 Contents

- 🔹 `Assignment_5_Complete_Postman_Collection.json`  
  → Contains all five API requests using `GET`, `POST`, `PUT`, `PATCH`, and `DELETE`, along with scripts, tests, assertions, and variables.

- 🔹 `TestEnv.postman_environment.json`  
  → Environment file that includes the `base_url` used by all requests.

---

## 🛠️ Features Implemented

- ✅ Used **all HTTP methods** (`GET`, `POST`, `PUT`, `PATCH`, `DELETE`)
- ✅ Defined `base_url` using Postman **Environment Variables**
- ✅ Created **random data** in `Pre-request Script`
- ✅ Parsed and logged **JSON response** using `console.log()`
- ✅ Used **Chai Assertion Library** to validate:
  - Status code
  - Response body values
- ✅ Wrote a **deliberately failing test**
- ✅ Set and cleared variables dynamically between `Pre-request` and `Tests` tabs
- ✅ Passed data (like `user_id`) from one request to another using **collection variables**

---

## 🧪 How to Run This Project

1. **Clone or Download** this repository.
2. Open **Postman**.
3. **Import the Collection**:
   - `Assignment_5_Complete_Postman_Collection.json`
4. **Import the Environment**:
   - `TestEnv.postman_environment.json`
5. Select `TestEnv` in the top-right environment selector.
6. Open each request one by one and click **Send**, or use **Collection Runner** to run all at once.

---

## 📌 Author

**Mahnoor**  
Software Engineering Student, Jinnah University for Women  
Postman & API Testing Assignment – 2025

---

## 📃 License

This project is for academic use only. Do not redistribute without permission.

