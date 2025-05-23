 # 📝 Exam Portal - Online Examination System

A full-stack web application built using **Java Spring Boot** and **Angular** to manage and conduct secure online exams with real-time results and time scheduling.

## 🚀 Key Modules

- 🧪 **Online Exam Module**: Schedule and conduct online exams for students.
- ❓ **Quiz Module**: Manage short quizzes with auto-evaluation.
- 📊 **Result Module**: Real-time result generation and tracking.
- ⏰ **Date & Time Module**: Time-bound exams with countdown timer.

## 🛠️ Tech Stack

- **Backend:** Java, Spring Boot, Spring Security, Hibernate
- **Frontend:** Angular
- **Database:** MySQL / PostgreSQL
- **Authentication:** JWT, Role-based access

## 👥 User Roles

- **Admin**: Manage users, exams, quiz settings
- **Examiner**: Create questions, assign exams
- **Student**: Appear in exams, view results

## 📷 Screenshots

_Add relevant UI screenshots here (Login, Dashboard, Exam Page, Results, etc.)_

## ⚙️ Installation Guide

```bash
# Backend Setup
cd backend
mvn clean install
java -jar target/exam-portal.jar

# Frontend Setup
cd frontend
npm install
ng serve
