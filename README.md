# HostelSync – Smart Hostel Management & Monitoring Platform

HostelSync is a modern full-stack hostel management platform built using the MERN Stack (MongoDB, Express.js, React.js, and Node.js). The system streamlines hostel operations by providing a centralized digital solution for administrators, wardens, students, and parents.

The platform eliminates traditional paper-based processes and enables efficient management of room allocation, attendance tracking, complaints, leave requests, fee records, notifications, and mess services through dedicated role-based dashboards.

Designed with scalability, security, and usability in mind, HostelSync leverages JWT-based authentication, role-based access control, cloud deployment, and responsive user interfaces to deliver a seamless hostel management experience.

## 🌐 Live Demo

https://hostel-sync-beige.vercel.app

## 🚀 Key Features

### Authentication & Security
- JWT-based Authentication
- Password Hashing using bcryptjs
- Role-Based Access Control
- Protected Routes and Secure APIs

### User Roles
- Administrator Portal
- Warden Portal
- Student Portal
- Parent Portal

### Hostel Management Modules
- Student Management
- Room Allocation & Occupancy Tracking
- Attendance Management
- Complaint Management
- Leave Request Management
- Fee Monitoring & Payment Tracking
- Mess Menu Management
- Notification System

### Dashboard & Analytics
- Real-time Hostel Statistics
- Occupancy Monitoring
- Attendance Tracking
- Complaint Status Overview
- Leave Request Monitoring
- Fee Collection Summary

### Cloud Deployment
- Frontend deployed on Vercel
- Backend deployed on Render
- Database hosted on MongoDB Atlas

---

## 🏗️ System Architecture

```text
┌─────────────────────────────┐
│        React Frontend       │
│      Vite + React Router    │
└──────────────┬──────────────┘
               │
               │ Axios API Calls
               ▼
┌─────────────────────────────┐
│      Express.js Backend     │
│     JWT Authentication      │
│    Role-Based Middleware    │
└──────────────┬──────────────┘
               │
               │ Mongoose ODM
               ▼
┌─────────────────────────────┐
│        MongoDB Atlas        │
│       Cloud Database        │
└─────────────────────────────┘
```

## 💻 Technology Stack

| Layer | Technology |
|---------|------------|
| Frontend | React.js, Vite, React Router, Axios |
| Backend | Node.js, Express.js |
| Database | MongoDB, Mongoose ODM |
| Authentication | JWT, bcryptjs |
| Deployment | Vercel, Render, MongoDB Atlas |
| Tools | GitHub, Postman, VS Code |

## 🎯 Project Objectives

- Digitize hostel administration processes
- Improve communication between students and hostel authorities
- Reduce manual paperwork and errors
- Provide real-time hostel monitoring
- Enable secure role-based access for all stakeholders
- Centralize hostel operations into a single platform

## 🔮 Future Enhancements

- Real-Time Updates using Socket.IO
- Mobile Application using React Native
- QR-Based Hostel Entry System
- Face Recognition Attendance
- Email & SMS Notifications
- Visitor Approval Workflow
- AI-Powered Analytics Dashboard
- PDF & Excel Report Generation

## 📂 GitHub Repository

https://github.com/Chirag-102/hostel-sync
