# 🧹 CleanMitra - Smart Waste Management System

CleanMitra is a Java-based Smart Waste Management System designed to improve waste collection and complaint management in urban areas. The application provides separate dashboards for Users, Drivers, and Administrators to streamline the waste management process.

## 📌 Overview

CleanMitra enables citizens to report waste-related issues, administrators to assign tasks, and drivers to update collection status. The system helps municipalities improve efficiency, reduce response time, and maintain cleaner surroundings.

---

## 🚀 Features

### 👤 User Module
- User Registration & Login
- Report waste issues
- Upload complaint images
- Track complaint status
- View complaint history
- Receive notifications

### 👨‍💼 Admin Module
- Secure Admin Login
- View all complaints
- Assign complaints to drivers
- Manage users and drivers
- Monitor complaint status
- Generate reports

### 🚛 Driver Module
- Driver Login
- View assigned tasks
- Update work status
- Upload proof of waste collection
- Mark complaints as completed

---

## 💻 Tech Stack

- **Programming Language:** Java
- **GUI Framework:** JavaFX
- **Database:** MongoDB
- **Database Tool:** MongoDB Compass
- **IDE:** IntelliJ IDEA / Eclipse
- **Version Control:** Git & GitHub

---

## 🏗️ System Architecture

```
User
   │
   ▼
JavaFX Desktop Application
   │
   ▼
Business Logic (Java)
   │
   ▼
MongoDB Database
```

---

## 📂 Project Structure

```
CleanMitra/
│
├── src/
│   ├── controllers/
│   ├── models/
│   ├── database/
│   ├── services/
│   ├── utils/
│   └── Main.java
│
├── resources/
│   ├── images/
│   ├── styles/
│   └── fxml/
│
├── README.md
└── pom.xml (if Maven)
```

---

## ⚙️ Installation

### Prerequisites

- Java JDK 17 or above
- JavaFX SDK
- MongoDB Community Server
- MongoDB Compass
- IntelliJ IDEA or Eclipse

### Steps

1. Clone the repository

```bash
git clone https://github.com/yourusername/CleanMitra.git
```

2. Open the project in IntelliJ IDEA or Eclipse.

3. Start MongoDB.

4. Configure MongoDB connection.

5. Run `Main.java`.

---

## 📊 Workflow

1. User submits a waste complaint.
2. Complaint is stored in MongoDB.
3. Admin reviews the complaint.
4. Admin assigns the task to a driver.
5. Driver collects the waste.
6. Driver uploads completion proof.
7. Complaint status changes to Completed.

---

## 🎯 Key Functionalities

- Secure Login System
- Role-Based Access Control
- Complaint Management
- Driver Task Allocation
- Waste Collection Tracking
- Image Upload Support
- Status Monitoring
- MongoDB Integration

---

## 🔒 Future Enhancements

- Flutter Mobile Application
- GPS Tracking for Drivers
- Email & SMS Notifications
- AI Chatbot for Complaint Assistance
- QR Code-based Waste Bin Tracking
- Analytics Dashboard
- Real-time Location Tracking
- Cloud Deployment

---

## 📈 Project Outcomes

- Improved complaint management process
- Reduced manual tracking
- Faster task assignment
- Better communication between users, drivers, and administrators
- Centralized waste management system

---

## 👨‍💻 Developed By

**K. Hema Charan Reddy**

B.Tech Computer Science Engineering

KL University Hyderabad

GitHub: https://github.com/HEMACHARANREDDY

LinkedIn: https://www.linkedin.com/in/hema-charan-reddy/

---

## 📄 License

This project is developed for educational and research purposes.
