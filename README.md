
# 🧳 Tourism Management System (TMS) in PHP

A full-featured Tourism Management System built using **PHP** and **MySQL**. It enables users to browse and book tours, while admins can manage packages, users, bookings, and more through a dedicated admin dashboard.

---

## 📌 Project Details

- **Project Name:** Tourism Management System (TMS)
- **Languages Used:** PHP, HTML, CSS, JavaScript, AJAX, jQuery
- **Database:** MySQL
- **Compatible Browsers:** Chrome, Firefox, Edge, Opera, IE8+
- **Supported Environments:** XAMPP / WAMP / MAMP / LAMP

---

## 👥 User Roles and Features

### 🧑‍💼 Admin Panel
- Login authentication
- Create, update, and delete tour packages
- Manage registered users
- Manage bookings
- View and respond to inquiries
- Manage user-generated complaints
- Static page management
- Change admin password
- Dashboard with stats

### 👤 Registered Users
- User registration and login
- Forgot password recovery
- Book tours
- Manage existing bookings
- Raise support tickets or complaints
- Change user password

### 🌐 Guest Users
- Browse website
- Send inquiries via contact form

---

## 📁 Project Structure

```
/tms
│
├── admin/              # Admin dashboard
├── user/               # User dashboard and features
├── includes/           # Configuration and DB connection
├── images/             # Uploaded images and assets
├── css/                # Stylesheets
├── js/                 # JavaScript files
├── index.php           # Homepage
└── ...
```

---

## 🚀 How to Run the Project Locally

1. **Install XAMPP / WAMP / MAMP / LAMP**

2. **Clone or Download the Repository**
   ```bash
   git clone https://github.com/kumarnaveen02/tourism-management-system.git
   ```

3. **Move Project Folder**
   - Place the folder in `htdocs` (for XAMPP) or `www` (for WAMP).

4. **Import the Database**
   - Open `phpMyAdmin`
   - Create a database (e.g., `tms`)
   - Import the provided SQL file (`tms.sql`) from the `database/` folder

5. **Start Apache and MySQL**
   - Launch them using your chosen software (XAMPP/WAMP)

6. **Open in Browser**
   ```
   http://localhost/tms
   ```

---

## 🔐 Default Login Credentials

### Admin Login
- **Username:** admin
- **Password:** admin123 *(or as set in DB)*

### Test User Login
- **Email:** user@example.com
- **Password:** user123 *(or as registered)*

---
