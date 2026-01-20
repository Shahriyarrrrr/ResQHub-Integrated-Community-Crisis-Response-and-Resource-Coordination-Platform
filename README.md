# ResQHub 🚑  
### Emergency Response & Donation Management System

ResQHub is a full-stack, role-based emergency response and donation management platform designed to coordinate crisis requests, volunteers, and financial contributions in a secure and scalable manner.  
The system provides a centralized administrative dashboard, real-time request monitoring, and structured donation tracking to support disaster relief operations.

---

## 📌 Key Features

### 🔐 Authentication & Authorization
- Secure login system with password hashing
- Role-based access control (Admin, Volunteer, Citizen)
- Session-based authentication
- Account status management (Active / Suspended)

### 👤 User Management (Admin)
- View all registered users
- Activate or suspend user accounts
- Role visibility and status badges
- Activity logging for administrative actions

### 🚨 Emergency Request Management
- Citizens can submit emergency requests
- Admins can monitor and override request status
- Volunteers receive assigned requests
- Status lifecycle handling (Pending, Resolved, Cancelled)

### 🤝 Volunteer Coordination
- Volunteer assignment to emergency requests
- Active assignment tracking
- Availability validation for volunteers
- Assignment status updates

### 💰 Donation Management
- Donation creation with currency support
- Donation listing and tracking
- Region-based and currency-based summaries
- Admin donation overview dashboard

### 📊 Admin Dashboard
- Total users count
- Active emergency requests
- Total donations
- Transaction overview
- Clean, professional UI with real-time data

### 🔔 Notifications & Activity Logs
- System-wide broadcast notifications
- User-specific notifications
- Activity logging for critical system events

---

## 🛠️ Technology Stack

| Layer | Technology |
|------|------------|
| Frontend | HTML5, CSS3, Vanilla JavaScript |
| Backend | PHP (MVC Architecture) |
| Database | MySQL |
| Server | Apache (XAMPP / LAMP) |
| Security | Password Hashing, Session Management |

---

## 🧱 System Architecture

# ResQHub 🚑  
### Emergency Response & Donation Management System

ResQHub is a full-stack, role-based emergency response and donation management platform designed to coordinate crisis requests, volunteers, and financial contributions in a secure and scalable manner.  
The system provides a centralized administrative dashboard, real-time request monitoring, and structured donation tracking to support disaster relief operations.

---


## 🛠️ Technology Stack

| Layer | Technology |
|------|------------|
| Frontend | HTML5, CSS3, Vanilla JavaScript |
| Backend | PHP (MVC Architecture) |
| Database | MySQL |
| Server | Apache (XAMPP / LAMP) |
| Security | Password Hashing, Session Management |

---

## 🧱 System Architecture

Client (Browser)
↓
JavaScript (Fetch API)
↓
index.php (Front Controller)
↓
Controller Layer
↓
Model Layer
↓
MySQL Database


---


- Centralized routing via `index.php`
- Clean separation of concerns (MVC)
- API-style JSON responses
- Reusable model classes

---

## 🗂️ Project Structure

ResQHub/
│
├── Controller/
│ ├── AuthController.php
│ ├── AdminController.php
│ ├── VolunteerController.php
│ └── CitizenController.php
│
├── Model/
│ ├── Database.php
│ ├── UserModel.php
│ ├── EmergencyRequestModel.php
│ ├── AssignmentModel.php
│ ├── DonationModel.php
│ ├── PaymentModel.php
│ ├── CurrencyModel.php
│ └── NotificationModel.php
│
├── View/
│ ├── admin/
│ ├── volunteer/
│ ├── citizen/
│ └── auth/
│
├── index.php
└── README.md


---


---

## ⚙️ Installation & Setup

### 1️⃣ Prerequisites
- PHP 8+
- MySQL 5.7+
- Apache Server (XAMPP recommended)
- Web browser (Chrome / Firefox)

### 2️⃣ Clone Repository
```bash
git clone https://github.com/your-username/ResQHub.git


✍️ Author

Shahriyar Simoon
Computer Science & Engineering
Aspiring Data Science Manager | Cybersecurity Enthusiast
