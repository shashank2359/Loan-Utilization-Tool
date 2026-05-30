# Loan Utilization Tracking System

![Node.js](https://img.shields.io/badge/Node.js-Backend-green)
![React](https://img.shields.io/badge/React-Frontend-blue)
![MongoDB](https://img.shields.io/badge/MongoDB-Database-brightgreen)
![JWT](https://img.shields.io/badge/Auth-JWT-orange)

## 📌 Overview
The Loan Utilization Tracking System is a full-stack web application designed to manage loan applications and track their approval process. It provides role-based access where users can apply for loans and administrators can review, approve, or reject applications.

The system ensures secure authentication, structured data handling, and efficient loan management through a RESTful API.

---

## 🚀 Features

### 👤 User (Beneficiary)
- User authentication using JWT
- Apply for loans with amount and purpose
- Secure access to protected routes

### 🛠️ Admin
- View all loan applications
- Approve or reject loan requests
- Role-based access control

---

## 🏗️ Tech Stack

### Backend
- Node.js
- Express.js
- MongoDB (Atlas)
- JWT Authentication

### Frontend
- React.js
- Axios
- Basic CSS

---

## 🔗 Project Repositories

- 🔙 Backend:  
  https://github.com/shashank2359/Loan-Utilization-Tracking-via-Mobile-backend

- 🎨 Frontend:  
  https://github.com/shashank2359/Loan-Utilization-Tracking-via-Mobile-frontend

---

## ⚙️ How It Works

1. User logs in using credentials
2. JWT token is generated and stored
3. User applies for a loan
4. Loan is stored with "pending" status
5. Admin logs in and views all applications
6. Admin approves or rejects the loan
7. Status is updated in the database

---

## 🔐 Security Features
- JWT-based authentication
- Protected API routes
- Role-based authorization (Admin/User)

---

## 📈 Future Enhancements
- User dashboard to view loan status
- Email notifications for loan updates
- Pagination and filtering for admin panel
- UI improvements using Tailwind CSS

---

## 🧾 Conclusion
This project demonstrates a complete full-stack implementation with authentication, role-based access, and CRUD operations. It reflects real-world application architecture and serves as a strong foundation for scalable financial systems.

---

## 📁 Project Structure

This project consists of two separate repositories:

- Backend (API server)
- Frontend (React client)

Both are linked above and work together to form the complete system.
