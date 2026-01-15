# Serverless Student Data Management System

A cloud-native **serverless web application** built on AWS that allows users to store and retrieve student information using **RESTful APIs**. The system leverages **AWS Lambda, Amazon API Gateway, and DynamoDB** to achieve a fully managed, scalable, and cost-efficient architecture without server maintenance.

---

## 🚀 Features

- Add student details (Student ID, Name, Class, Age)
- Retrieve and display all student records
- Fully serverless backend architecture
- Scalable NoSQL data storage
- Secure service-to-service communication using IAM
- Real-time data interaction via REST APIs

---

## 🏗️ Architecture Overview

**Frontend**
- HTML, CSS, JavaScript
- AJAX-based API calls

**Backend (Serverless)**
- AWS Lambda (Python)
- Amazon API Gateway (REST API)
- Amazon DynamoDB (NoSQL Database)
- AWS IAM (Security & Access Control)

---

## 🛠️ Technologies Used

- **AWS Lambda**
- **Amazon API Gateway**
- **Amazon DynamoDB**
- **AWS IAM**
- **Python**
---

## 🔄 Application Flow

1. User enters student details in the web UI
2. Frontend sends data to API Gateway via REST API
3. API Gateway triggers AWS Lambda function
4. Lambda stores/retrieves data from DynamoDB
5. Response is sent back and displayed in the UI

---

## 🔐 Security

- IAM roles and policies are used to restrict Lambda access to DynamoDB
- API Gateway securely invokes Lambda functions
- No direct database exposure to the client

---

## 📈 Key Learnings

- Hands-on experience with **serverless architecture**
- Implemented **RESTful APIs** using AWS services
- Integrated frontend with backend cloud services
- Designed scalable and cost-efficient cloud applications
- Strengthened understanding of IAM and AWS security best practices

---

## 📌 Use Case

This project is suitable for:
- Cloud Engineering portfolios
- AWS / DevOps fresher projects
- Serverless application demonstrations
- Learning AWS event-driven architectures

---

## Preview

<img width="1920" height="1012" alt="Screenshot 2026-01-14 231511" src="https://github.com/user-attachments/assets/8da2741f-5827-47e1-850a-da0172906f7f" />


## 👨‍💻 Author

**Shravan Ravi Acharya**  
- GitHub: https://github.com/shravan-acharya 
