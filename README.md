# 📸 Ayloul Booking System

A full-stack **Photography Session Booking System** designed to simplify the process of browsing photography services, booking sessions, and managing reservations through a modern and responsive web application.

## 🚀 About the Project

**Ayloul Booking System** is a web-based platform developed to provide an easy and organized way for customers to explore photography services and book photography sessions online.

The system also provides an administrative dashboard for managing bookings, users, services, and financial information.

The project was developed as a **Full-Stack Web Application**, focusing on backend development, database management, authentication, authorization, responsive UI, and practical business workflows.

---

## ✨ Features

### 👤 User Features

* User registration and login
* Secure authentication
* Browse available photography services
* View service details
* Select preferred booking dates
* Create and manage bookings
* View booking status
* Responsive design for desktop and mobile devices
* Multi-language support

### 🛠️ Admin Features

* Admin dashboard
* Manage users
* Manage photography services
* Manage bookings
* View booking information
* Booking status management
* Financial reports
* Administrative authorization and role management

### 🔐 Authentication & Authorization

* ASP.NET Core Identity
* Role-based authorization
* User and administrator access control
* Protected administrative pages

---

## 🧰 Technologies Used

### Backend

* C#
* ASP.NET Core
* ASP.NET Core MVC
* Entity Framework Core
* ASP.NET Core Identity
* API

### Frontend

* HTML5
* CSS3
* JavaScript
* Bootstrap
* Responsive Web Design

### Database

* Microsoft SQL Server
* Entity Framework Core
* Code First / Migrations

### Development Tools

* Visual Studio
* Git
* GitHub

---

## 🏗️ System Architecture

The project follows a structured MVC architecture:

```text
Ayloul Booking System
│
├── Controllers
│   ├── AccountController
│   ├── BookingController
│   ├── HomeController
│   └── Admin Controllers
│
├── Models
│   ├── User
│   ├── Booking
│   ├── Service
│   └── Other Domain Models
│
├── Views
│   ├── Home
│   ├── Booking
│   ├── Account
│   └── Admin
│
├── Data
│   ├── ApplicationDbContext
│   └── Database Configuration
│
├── Areas
│   └── Admin
|   └── User
│
├── wwwroot
│   ├── css
│   ├── js
│   ├── images
│   └── libraries
│
└── Migrations
```

---

## 📅 Booking Workflow

The main booking process works as follows:

```text
User
  ↓
Browse Photography Services
  ↓
Select Service
  ↓
Choose Booking Details
  ↓
Submit Booking
  ↓
Booking Stored in Database
  ↓
Admin Reviews Booking
  ↓
Booking Status Updated
```

---

## 👨‍💼 Admin Dashboard

The administrative dashboard provides management functionality for the system, including:

* 📊 Dashboard overview
* 👥 User management
* 📸 Photography service management
* 📅 Booking management
* 💰 Financial reporting
* 🔐 Role-based access control

---

## 🌐 Responsive Design

The application is designed to work across different screen sizes:

* 💻 Desktop
* 📱 Mobile
* 📟 Tablet

The UI adapts to different screen resolutions to provide a consistent user experience.

---

## 🌍 Localization

The system supports multiple languages using localization features, allowing the interface to be displayed according to the selected language.

---

## 🗄️ Database

The application uses **Microsoft SQL Server** with **Entity Framework Core** for database operations.

Main database entities include:

* Users
* Roles
* Bookings
* Photography Services
* Booking Details
* Financial Data

Entity Framework Core migrations are used to manage database schema changes.

---

## ⚙️ Installation & Setup

### 1. Clone the Repository

```bash
git clone https://github.com/mohammadnofal8900/Full-Stack-Developer-Ayloul-System-.git
```

### 2. Open the Project

Open the solution in:

```text
Visual Studio
```

### 3. Configure the Database

Update the connection string in:

```text
appsettings.json
```

Example:

```json
{
  "ConnectionStrings": {
    "DefaultConnection": "Server=YOUR_SERVER;Database=AyloulDb;Trusted_Connection=True;TrustServerCertificate=True;"
  }
}
```

### 4. Apply Database Migrations

Run:

```bash
Update-Database
```

Or using the .NET CLI:

```bash
dotnet ef database update
```

### 5. Run the Application

Run the project from Visual Studio or use:

```bash
dotnet run
```

---

## 🔑 User Roles

The system uses role-based authorization.

| Role        | Access                                       |
| ----------- | -------------------------------------------- |
| User        | Browse services and create/manage bookings   |
| Admin       | Manage users, bookings, services and reports |
| Super Admin | Full administrative access                   |

---

## 📸 Screenshots

Add screenshots of the main pages here:

```text
/screenshots
├── home-page.png
├── booking-page.png
├── login-page.png
├── admin-dashboard.png
├── booking-management.png
└── financial-report.png
```

Example:

### 🏠 Home Page

![Home Page](screenshots/home-page.png)

### 📅 Booking Page

![Booking Page](screenshots/booking-page.png)

### 📊 Admin Dashboard

![Admin Dashboard](screenshots/admin-dashboard.png)

---

## 🎯 Project Goals

The main goals of the project were to:

* Build a complete full-stack web application
* Implement a real-world booking workflow
* Practice ASP.NET Core MVC development
* Implement authentication and authorization
* Work with relational databases
* Build an administrative dashboard
* Implement responsive UI
* Apply clean and structured application architecture
* Gain practical experience with Entity Framework Core

---

## 🧑‍💻 Developer

**Mohammad Nofal**

Software Engineer | Full-Stack Developer

### 🔗 Profiles

* **GitHub:** https://github.com/mohammadnofal8900
* **LinkedIn:** https://www.linkedin.com/in/mohammad-nofal-7208412a1

---

## 📄 License

This project was developed for educational and portfolio purposes.
