# 🍽️ Restaurant Management System — QA Testing Project

## 📌 About the Project

This project is a QA testing portfolio project based on real-world scenarios from the hotel and restaurant industry.

The main goal is to test a restaurant order management system designed to support communication between waiters, kitchen staff, and other restaurant operations.

The project focuses on identifying functional issues, data inconsistencies, communication failures, and edge cases that could affect the quality and efficiency of restaurant service.

The idea was inspired by my own experience working as a waitress in hotels and restaurants, allowing me to approach the testing process from both a **QA perspective and a real user perspective**.

---

## 🎯 Project Objectives

The main objectives are to:

* Analyze functional and business requirements
* Design and execute test cases
* Test REST APIs using Postman
* Validate HTTP status codes and response bodies
* Perform positive and negative testing
* Apply Equivalence Partitioning and Boundary Value Analysis
* Identify and document defects
* Validate data using SQL
* Perform exploratory testing
* Document the testing process and results

---

## 🧪 Testing Scope

The following functionalities are covered:

### Orders

* Create a new order
* View an existing order
* Update an order
* Remove an order
* Add or remove items
* Change item quantities
* Add special instructions
* Update order status

### Tables

* View table availability
* Assign an order to a table
* Validate occupied and available tables

### Products

* Retrieve available products
* Retrieve product details
* Validate invalid or unavailable products

### Special Requirements

* Allergies and dietary restrictions
* Special preparation instructions
* Order modifications
* Duplicate order prevention

---

## 🔌 API Testing

API testing is performed using **Postman**.

The tests cover:

* GET
* POST
* PUT
* DELETE
* HTTP status codes
* JSON response validation
* Required fields
* Invalid data
* Boundary values
* Error handling
* Business rules
* Automated assertions
* Environment variables
* Request chaining

Example workflow:

```text
Login
  ↓
Get Table
  ↓
Create Order
  ↓
Get Order
  ↓
Update Order
  ↓
Send Order to Kitchen
  ↓
Update Order Status
  ↓
Close Order
```

---

## 🧠 Test Design Techniques

The following techniques are applied throughout the project:

* Equivalence Partitioning
* Boundary Value Analysis
* Decision Tables
* Positive Testing
* Negative Testing
* Functional Testing
* Exploratory Testing
* Regression Testing

---

## 🐞 Bug Reporting

Identified defects are documented using a structured bug report containing:

* Bug ID
* Summary
* Environment
* Preconditions
* Steps to reproduce
* Expected result
* Actual result
* Severity
* Priority
* Attachments/evidence

Jira is used for defect tracking and management.

---

## 🗄️ Database Testing

SQL queries are used to verify that information submitted through the application/API is correctly stored and updated in the database.

Examples include:

* Verifying created orders
* Checking order status
* Validating table assignments
* Checking product information
* Identifying duplicated records

---

## 🛠️ Tools & Technologies

* **Postman** — API testing
* **Jira** — Bug tracking
* **SQL / PostgreSQL** — Database validation
* **Swagger / OpenAPI** — API documentation
* **Git & GitHub** — Version control and project documentation

---

## 📁 Project Structure

```text
restaurant-management-qa/
│
├── README.md
│
├── requirements/
│   └── requirements.md
│
├── test-cases/
│   └── test-cases.xlsx
│
├── checklists/
│   └── checklist.md
│
├── api-testing/
│   └── postman_collection.json
│
├── sql/
│   └── queries.sql
│
├── bug-reports/
│   └── bug-reports.md
│
└── test-report/
    └── test-report.md
```

---

## 📊 Test Results

The final test report includes:

* Number of test cases executed
* Passed/failed tests
* Defects found
* Severity distribution
* API test results
* Known limitations
* Final testing conclusions

---

## 💡 Why This Project?

My professional experience in hotel and restaurant environments helped me identify real-world scenarios that can create operational problems during a busy service.

Examples include:

* Incorrect order quantities
* Changes to orders after submission
* Missing allergy information
* Duplicate orders
* Incorrect table assignments
* Inconsistent order status
* Communication failures between restaurant staff

This project combines my **professional experience in hospitality with my developing skills in Quality Assurance**, allowing me to approach software testing from the perspective of an actual end user.

---

## 👩‍💻 About Me

I am currently developing my skills as a **Junior QA Analyst**, with a focus on manual testing, API testing, and software quality.

Currently studying:

* Test Case Design
* API Testing
* Postman
* Jira
* SQL
* PostgreSQL
* REST APIs
* Swagger/OpenAPI
* Git & GitHub

This project is part of my QA portfolio and represents my ongoing learning and practical application of software testing concepts.
