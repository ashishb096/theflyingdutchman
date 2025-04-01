# 🍽️ The Flying Dutchman - Food Ordering System

![HTML](https://img.shields.io/badge/HTML-5-orange)
![CSS](https://img.shields.io/badge/CSS-3-blue)
![JavaScript](https://img.shields.io/badge/JavaScript-ES6-yellow)
![PHP](https://img.shields.io/badge/PHP-Backend-blue)
![MySQL](https://img.shields.io/badge/MySQL-Database-orange)

## 📌 Overview
The **Flying Dutchman** is a full-stack **Food Ordering System** built as a **major project** for the **B.C.A. Degree**. This project includes a dynamic restaurant website where users can browse the menu, place orders, and track their delivery. The system is designed to be user-friendly, secure, and efficient for both customers and restaurant staff.

📂 **GitHub Repository**: [The Flying Dutchman](https://github.com/ashishb096/theflyingdutchman)

---
## 🛠 Tech Stack
- **Frontend**: HTML, CSS, JavaScript (Bootstrap for responsiveness)
- **Backend**: PHP
- **Database**: MySQL
- **Hosting**: Apache Server (XAMPP / LAMP)

---
## 🍕 Features
✅ **User-Friendly Interface** - Easy navigation with a modern UI  
✅ **Menu Browsing** - View dishes with images, descriptions, and prices  
✅ **Online Ordering** - Add items to cart and place an order  
✅ **Order Tracking** - View order status updates  
✅ **Admin Dashboard** - Manage orders, menu items, and customers  
✅ **User Authentication** - Secure login/signup for customers and admins  
✅ **Payment Integration** - (Planned) Online payment support  

---
## 🏗 Setup Instructions
### Prerequisites
Ensure you have the following installed:
- XAMPP / LAMP (for Apache, PHP, MySQL)
- PHP 7+
- MySQL Database
- Git

### Steps to Run Locally
```sh
# Clone the repository
git clone https://github.com/ashishb096/theflyingdutchman.git
cd theflyingdutchman

# Move project files to XAMPP htdocs directory (for Windows)
move * C:\xampp\htdocs\theflyingdutchman

# Start XAMPP and Apache/MySQL
# Open the project in the browser
http://localhost/theflyingdutchman
```

### Database Setup
1. Open **phpMyAdmin** (`http://localhost/phpmyadmin`)
2. Create a new database: `theflyingdutchman_db`
3. Import the provided `database.sql` file from the repository
4. Update database credentials in `config.php`

---
## 📌 Website Home Page Preview
```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>The Flying Dutchman</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <h1>Welcome to The Flying Dutchman</h1>
        <p>Delicious meals delivered to your doorstep</p>
        <a href="menu.html" class="btn">View Menu</a>
    </header>
</body>
</html>
```

---
## 📬 Contact
For queries, reach out via:
- **GitHub**: [@ashishb096](https://github.com/ashishb096)
- **Email**: [bisht2001ashish@gmail.com] (mailto:bisht2001ashish@gmail.com)

---
### 🔥 Show Some Love
If you like this project, don’t forget to ⭐ the repository!
