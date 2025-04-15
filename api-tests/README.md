# API Testing Collection

This branch includes manual API tests for public services:

## 🔹 1. Regres.in

Collection: `regres_api_tests.postman_collection.json`

**What covered with tests:**
- Tests via `GET`, `POST`, `PATCH`, `PUT`, `DELETE`
- Positive cases (successful responses)
- Negative cases:
  - Non existing methods
  - Validity of email/password
  - Entering of arrays, objects, null, SQL injections 

## 🔹 2. Dummy API (Products)

Collection: `dummy_api_tests.postman_collection.json`

**What covered with tests:**
- CRUD operations with products
- Incorrect data types
- Non existing ID
- Status codes testing

## ⚙️ How to use

1. Install [Postman](https://www.postman.com/) Install 
2. Import collection via **Import** button
3. Select the test case and click on the **Send** button

---

## 🚀 Author

Andrii Chornii — QA Engineer  
