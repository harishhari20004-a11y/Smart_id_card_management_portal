# Cloud-Based Smart Student ID Card Management System

## 📌 Project Overview

The Cloud-Based Smart Student ID Card Management System is a web application developed to simplify and automate the student ID card management process. The system allows students to register, apply for new ID cards, report lost ID cards, and track the status of their requests online. Staff members can verify requests, while administrators manage approvals and system operations.

The project is deployed on Amazon Web Services (AWS) using cloud technologies for better scalability, security, and availability.

---

## 🚀 Features

### Student Module
- Student Registration
- Student Login
- Apply for New ID Card
- Report Lost ID Card
- Track Request Status

### Staff Module
- Staff Login
- View Student Requests
- Verify Student Requests
- Forward Requests to Admin

### Admin Module
- Admin Login
- Create Staff Accounts
- View All Requests
- Approve/Reject Requests
- Manage Users

---

## ☁️ AWS Cloud Services Used

- Amazon EC2
- Amazon RDS (MySQL)
- Amazon S3
- Amazon CloudWatch
- Amazon VPC
- AWS Security Groups

---

## 🛠️ Technologies Used

### Frontend
- HTML
- CSS
- JSP

### Backend
- Java
- Servlets
- JDBC

### Database
- MySQL
- Amazon RDS

### Web Server
- Apache Tomcat

### IDE
- Eclipse IDE

### Operating System
- Ubuntu Server (AWS EC2)

---

## 🏗️ System Architecture

```
Users
   │
   ▼
Web Browser
   │
   ▼
Apache Tomcat (EC2)
   │
   ▼
Java Servlets & JSP
   │
   ▼
Amazon RDS (MySQL)
   │
   ├────────► Amazon S3 (Photo Storage)
   │
   └────────► Amazon CloudWatch (Monitoring)
```

---

## 📂 Database Tables

- users
- id_requests
- lost_id_requests

---

## ⚙️ Project Workflow

1. Student registers into the system.
2. Student logs in.
3. Student applies for a new ID card or reports a lost ID card.
4. Staff verifies the request.
5. Admin approves or rejects the request.
6. Student tracks the application status.
7. All records are stored securely in Amazon RDS.

---

## 🌐 Deployment

The application is deployed on:

- Amazon EC2
- Apache Tomcat
- Amazon RDS
- Amazon S3

---


---

## 📖 Future Enhancements

- Email Notifications
- QR Code Based Student ID Cards
- Mobile Application
- Face Recognition
- SMS Notifications
- Multi-College Support

---

## 👨‍💻 Author

**Harish Ganisetty**

Master of Computer Applications (MCA)

---

## 📄 License

This project was developed for academic purposes as part of the MCA curriculum.
