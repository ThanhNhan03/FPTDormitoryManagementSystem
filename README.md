# 🏢 FPT Dormitory Management System

A complete dormitory management web application built for FPT University's student accommodation system. This project streamlines room assignments, student tracking, service billing, and user management with a clean and scalable architecture.

---

## 📌 Table of Contents

- [Overview](#overview)
- [Features](#features)
- [Tech Stack](#tech-stack)
- [Getting Started](#getting-started)
- [Project Structure](#project-structure)
- [Screenshots](#screenshots)
- [Contributing](#contributing)
- [License](#license)

---

## 📖 Overview

**FPTDormitoryManagementSystem** is a full-stack application developed to help dormitory administrators manage student housing operations. The system includes functionalities for student registration, room allocation, billing, and admin dashboards. It offers a responsive interface and RESTful API endpoints.

---

## ✨ Features

- 🔐 User Authentication & Authorization (Admin/Staff/Student)
- 👤 Student Management (Create, Update, Delete, View)
- 🏠 Room Management (Add, Assign, Track)
- 💸 Billing and Payment Tracking
- 📊 Dashboard for statistics and summaries
- 🌐 RESTful APIs for backend integration
- 📱 Responsive Frontend UI (SPA)

---

## 🧰 Tech Stack

### Backend:
- **.NET 8 / .NET Core**
- **Entity Framework Core**
- **ASP.NET Core Web API**

### Frontend:
- **React / TypeScript**
- **Material UI**

### Database:
- **SQL Server** (can be switched to MySQL/PostgreSQL with minor changes)

---

## 🚀 Getting Started

### Prerequisites

- [.NET 8 SDK](https://dotnet.microsoft.com/en-us/download)
- [Node.js & npm](https://nodejs.org/)
- [SQL Server](https://www.microsoft.com/en-us/sql-server)
- [Visual Studio or VS Code](https://code.visualstudio.com/)

---

### Backend Setup

```bash
cd DMS_API
dotnet restore
dotnet ef database update
dotnet run
