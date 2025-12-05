



---

# 📢 DARPAN – News Website

DARPAN is a dynamic and user-friendly news publishing system built using **PHP, MySQL, HTML/CSS, and Bootstrap**.
This project allows admins to manage categories, users, and news posts through a secure admin dashboard, while users can browse categorized news, search content, and read full articles.

---

## 📌 Table of Contents

1. About the Project
2. Objectives
3. Features
4. Tech Stack
5. System Architecture
6. Installation Guide
7. Database Structure
8. Screenshots
9. Future Scope
10. Author

---

## 📝 About the Project

Darpan is a modern web-based news platform designed to deliver timely, accurate, and categorized news updates to users.
It provides an intuitive browsing experience for readers and a robust management system for administrators.
The system is developed following **Agile methodology**, ensuring scalability, usability, and flexibility.

---

## 🎯 Objectives

The primary goals of this website include:

* Deliver accurate and timely news updates
* Offer a clean, user-friendly interface
* Ensure credibility and accuracy through structured data handling
* Support multimedia content (images, descriptions, categories)
* Facilitate easy content management via the admin panel
* Enable user & category management for admins
* Maintain responsive design for all devices

---

## ⭐ Features

### 👤 Admin Panel

* Admin authentication
* Add / Edit / Delete:

  * News posts
  * Categories
  * Users (Editors)
* Manage website settings (logo, footer text)
* Pagination for posts, categories, and users
* Image upload for posts and logo

---

### 🌐 User Side (Client)

* View recent news
* Browse by category
* Browse news by specific author
* Read full articles
* Responsive UI
* Real-time updates
* Auto-generated navigation menu from categories

---

## 🛠 Tech Stack

### **Frontend**

* HTML
* CSS
* Bootstrap

### **Backend**

* PHP
* MySQL

### **Version Control**

* Git
* GitHub

### **Software Requirements**

* VS Code
* 4GB+ RAM, i3 processor or higher

---

## ⚙️ Installation Guide

Follow these steps to run the project locally:

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/your-username/darpan-news-website.git
```

### 2️⃣ Move Project to Localhost

Place the folder inside:

```
C:/xampp/htdocs/
```

### 3️⃣ Configure the Database

* Open **phpMyAdmin**
* Create a new database:

```
news-site
```

* Import the SQL file: **news-site.sql**

### 4️⃣ Configure `config.php`

```php
<?php
$hostname = "http://localhost/news-site";
$conn = mysqli_connect("localhost","root","","news-site")
or die("Connection failed : " . mysqli_connect_error());
?>
```

### 5️⃣ Run the Project

Open browser:

User site:

```
http://localhost/news-site
```

Admin login:

```
http://localhost/news-site/admin
```

---

## 📸 Screenshots

### 📰 News Website View

<img width="760" height="597" src="https://github.com/user-attachments/assets/ef01cc11-a5c0-4f6a-ab72-c65fbf9edc11" />

### 🔐 Admin Panel

<img width="791" height="321" src="https://github.com/user-attachments/assets/ed20d35c-7122-490e-a223-9ebe40bec811" />

### ➕ Add User (Editor)

<img width="791" height="638" src="https://github.com/user-attachments/assets/3c08200d-d7fb-4a6d-9181-8ddd45251900" />

### ⚙️ Website Settings

<img width="762" height="619" src="https://github.com/user-attachments/assets/4349d0dc-c754-4283-a62f-583e75ac57a4" />

### 📝 Adding New Post (News)

<img width="791" height="727" src="https://github.com/user-attachments/assets/4d827c1d-70ce-4a7c-9e0d-4b7151f4def0" />

### 🔎 Search Bar

<img width="522" height="382" src="https://github.com/user-attachments/assets/84ab6075-23a8-4e54-a7b2-c9cc33cdb5b2" />

### ➕ Add News Category

<img width="791" height="289" src="https://github.com/user-attachments/assets/74eba4e5-a7dd-44ad-841c-3629054ed3c8" />

### 📖 Read More

<img width="770" height="713" src="https://github.com/user-attachments/assets/b11bab0d-00c9-49ac-9fc5-09cc684b5808" />

---

## 🚀 Future Scope

* Add user comments on posts
* Add newsletter/email subscription
* Add video news support
* Move to MVC Framework (Laravel / CodeIgniter)
* Add dark/light mode
* Add trending news algorithm

---

## 👨‍💻 Author

**Raj Amarjeet Chauhan**

---

