
# 🧳 Tourism Management System (TMS) 

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
## 📸 App Preview - Tourism Management System (TMS)

### Admin Dashboard
![Screenshot 2025-07-08 140247](https://github.com/user-attachments/assets/5fc4efa8-7ee9-4585-b2d3-b0eee603d903)


### Package Management
![Screenshot 2025-07-08 140518](https://github.com/user-attachments/assets/343d7563-7901-4342-9c89-d06e11b7a97d)

### Manage Booking 
![Screenshot 2025-07-08 141155](https://github.com/user-attachments/assets/4dcf7323-6e4b-40dd-8322-fd199a84e892)


### User Booking Page and Package List
![Screenshot 2025-07-08 140843](https://github.com/user-attachments/assets/661aef00-5fcb-41aa-a42d-1aff54e03c78)

### Tour History
![Screenshot 2025-07-08 141028](https://github.com/user-attachments/assets/8f894517-ac75-42ff-8cc6-bfd1ac64f6bc)



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
- **URL:**  http://localhost/tms/admin
- **Username:** admin
- **Password:** Test@123 *(or as set in DB)*

###  User Login
- **URL:**  http://localhost/tms/
- **Email:** test@gmail.com
- **Password:** Test@123 *(or as registered)*

**Note:** These credentials are for local testing/demo purposes only.



---
