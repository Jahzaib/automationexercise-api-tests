# AutomationExercise.com - Postman API Testing Collection

This repository contains a Postman Collection of tested API endpoints from [AutomationExercise.com](https://automationexercise.com), built to demonstrate real-world API testing skills.

---

## Covered APIs

| Category        | Endpoint                     | Method |
|----------------|-------------------------------|--------|
| User Account    | `/createAccount`              | POST   |
| Authentication  | `/verifyLogin`                | POST   |
| User Update     | `/updateAccount`              | PUT    |
| Delete Account  | `/deleteAccount`              | DELETE |
| Get User Info   | `/getUserDetailByEmail`       | GET    |
| Product Search  | `/searchProduct`              | POST   |
| Brands List     | `/brandsList`                 | GET    |

---

## Test Coverage

- Valid and invalid input handling  
- Status code assertions (200, 400, 404, 405)  
- Postman test scripts for response validation  
- Dummy data used for login and account creation  
- Environment variable `{{base_url}}` configured

---

## How to Use

1. Clone or download this repository  
2. Import the collection file (`.json`) into Postman  
3. Set environment variable:
base_url = https://automationexercise.com/api

5. Run individual requests or the full collection using Collection Runner

---

## About This Project

This project was created for QA practice and portfolio demonstration.  
It is intended for educational purposes using publicly available APIs.  
No sensitive or private data has been used in the tests.

---

## Tags

Postman · API Testing · Software Testing · Manual Testing · QA Portfolio · AutomationExercise
