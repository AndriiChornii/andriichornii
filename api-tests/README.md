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

## 🔹 2. Dummy API (Products, Auth)

Collection: `dummy_api_tests.postman_collection.json`

**What covered with tests:**
- Authentification via credentials and token
- Token and credentials tests (positive and negative)
- CRUD operations with products
- Incorrect data types
- Non existing ID
- Status codes testing

## ⚙️ How to use

1. Install [![Postman](https://img.shields.io/badge/Postman-F5F5F5?style=for-the-badge&logo=Postman)](https://www.postman.com/)
2. Import collection via **Import** button
3. Select the test case and click on the **Send** button

---

## 🚀 Author

# Any case, if you don't wanna install and run all of the cases, you can just check how my cases looks like here: 
This is Dummy JSON collection
![Dummy JSON](https://github.com/AndriiChornii/andriichornii/blob/main/assets/DummyJSON%20API%20tests.png)

This is reqres.in collection
![reqres.in](https://github.com/AndriiChornii/andriichornii/blob/main/assets/reqres.in%20API%20tests.png)



