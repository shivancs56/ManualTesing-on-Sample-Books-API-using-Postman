# 🚀 Manual API Testing Project: Simple Books API

## 📌 Project Overview
This repository contains the comprehensive manual testing documentation for the **Simple Books API**. The project demonstrates the end-to-end testing lifecycle, starting from initial API exploration to advanced validation using **Postman**.

The goal was to ensure the API's reliability, security (Auth), and correct functional behavior through systematic manual test execution.

## 🛠️ Tech Stack & Tools
- **Testing Tool:** Postman
- **API Type:** REST (Representational State Transfer)
- **Documentation:** Microsoft Word (Step-by-step Report)
- **Concepts:** Environment Variables, Bearer Tokens, CRUD Operations

## 📁 Project Contents
- **[Manual Testing Report](./Manual-Testing/ManualTestingUsingPostman(Sample%20Books%20Api).docx):** A detailed Word document containing 30+ screenshots, test scenarios, and execution results.
- **Postman Collection:** Validation of status codes, response headers, and JSON payloads.

## 🧪 Testing Scenarios Covered
### 1. Fundamental Validation
- **Health Check:** Verified the `/status` endpoint for uptime.
- **Catalog Exploration:** Validated GET requests for full and filtered book lists.

### 2. Security & Authentication
- **Bearer Token Implementation:** Successfully registered a client and managed the `accessToken` for secure requests.

### 3. Business Logic (Order Management)
- **Create Order:** Verified POST requests for placing new book orders.
- **Retrieve Order:** Verified GET requests for order history and single order details.
- **Update Order:** Verified PATCH requests for modifying customer details.
- **Delete Order:** Verified DELETE requests for order cancellation.

## ⚙️ Advanced Features Implemented
- **Dynamic Variables:** Used Postman Environments to handle `baseUrl` and `accessToken` dynamically.
- **Data Extraction:** Automated the flow by capturing data from responses (like `orderId`) and passing it to subsequent requests.
- **JavaScript Assertions:** Implemented basic scripts in the Postman 'Tests' tab to validate status codes (200, 201, etc.) and response times.

---
### 👨‍💻 How to Review this Project
1. Navigate to the `Manual-Testing` folder.
2. Download and open the **ManualTestingUsingPostman(Sample Books Api).docx** file.
3. Review the screenshots and documented test cases for each API endpoint.
