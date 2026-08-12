# SQA-Day-5-HisabDo
## 📌 Project Overview
This project is created as part of the Day 5 SQA Internship task.
The purpose of this project is to perform practical REST API testing using Postman. The testing covers functional testing, negative testing, validation testing, boundary testing, response validation, and bug identification.
## 🌐 API Under Test
**API Name:** JSONPlaceholder
**Resource:** Posts API
**Base URL:**  
https://jsonplaceholder.org
## 🛠️ Tools Used
- Postman
- Microsoft Excel / Google Sheets
- GitHub
## 🔹 HTTP Methods Tested
The following HTTP methods were tested:
- GET
- POST
- PUT
- PATCH
- DELETE
## 🧪 Testing Scope
### Functional Testing
The following operations were tested:
- Get all posts
- Get a single post
- Create a new post
- Update a post using PUT
- Partially update a post using PATCH
- Delete a post
### Validation Testing
The following validation scenarios were tested:
- Invalid ID
- Non-numeric ID
- Zero ID
- Negative ID
- Invalid endpoint
- Missing required fields
- Empty values
- Invalid data types
- Duplicate data
- Invalid resource IDs
### Boundary Testing
Boundary and validation testing included:
- ID = 0
- ID = -1
- ID = 1
- ID = 100
- ID = 999
- Empty title
- Empty body
- Invalid userId data type
## 📊 Test Documentation
The complete test documentation is available in the Excel file.
The documentation contains:
### Test Cases
Each test case includes:
- Test Case ID
- Test Type
- API / Endpoint
- Method
- Request / Test Data
- Expected Result
- Actual Result
- Status
### Boundary & Validation Testing
Boundary and validation cases are documented separately with their expected and actual results.
### Bug Report
Issues identified during testing are documented with:
- Bug ID
- Related Test Case
- Endpoint
- Method
- Bug Title
- Expected Result
- Actual Result
- Severity
- Status
## 🤖 Postman Test Validation
Postman was used to execute API requests and validate their responses.
The testing included verification of:
- HTTP status codes
- Response body
- Required response fields
- Response data types
- Response behavior
- Response time
## 📁 Project Structure
```text
SQA-Day-5-HisabDo/
│
├── Postman/
│   └── JSONPlaceholder-REST-API-QA-Suite.json
│
├── Documentation/
│   └── Day-5-API-Test-Documentation.xlsx
│
└── README.md
