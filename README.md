
📢 DARPAN – News Website
A dynamic and user-friendly news publishing system built using PHP, MySQL, HTML/CSS, and Bootstrap. This project allows admins to manage categories, users, and news posts through a secure admin dashboard, while users can browse categorized news, search content, and read full articles.

📌 Table of Contents
1)About the Project
2)Objectives
3)Features
4)Tech Stack
5)System Architecture
6)Installation Guide
7)Database Structure
8)Screenshots
9)Future Scope

Author
📝 About the Project
Darpan is a modern web-based news platform designed to deliver timely, accurate, and categorized news updates to users.
It provides an intuitive browsing experience for readers and a robust management system for administrators. 
The system is developed following Agile methodology to ensure scalability, usability, and flexibility.


🎯 Objectives
The primary goals of this website include:

-Delivering accurate and timely news updates
-Offering a clean, user-friendly interface
-Ensuring credibility & accuracy through structured data handling
-Supporting multimedia content (images, descriptions, categories)
-Facilitating easy content management via an admin panel
-Allowing user and category management for admins
-Maintaining responsive design for all devices


⭐ Features
👤 Admin Panel
Admin authentication system

Add / Edit / Delete:
News posts
Categories


👉🏼Users(Developer user site)-news editors
Manage website settings (logo, footer text)

Pagination for posts, categories, and users
Image upload for posts and logos




🌐 User Side(client)
-View recent news
-Browse by category
-Browse news by specific author
-Read full articles
-Responsive UI
-Real-time updates
-Navigation menu auto-generated from categories


🛠 Tech Stack
Frontend
HTML
CSS
Bootstrap

Backend
PHP
MySQL

Version Control
Git & GitHub


Software Requirements
VS Code
4GB+ RAM, i3 processor (or higher)


res.

⚙️ Installation Guide
Follow these steps to run the project locally:

1️⃣ Clone the Repository
git clone https://github.com/your-username/darpan-news-website.git


2️⃣ Move Project to Localhost
Place the folder inside:
C:/xampp/htdocs/


3️⃣ Configure the Database
Open phpMyAdmin
Create a new database:
news-site
Import the SQL file (news-site.sql)


4️⃣ Configure config.php
<?php
$hostname = "http://localhost/news-site";
$conn = mysqli_connect("localhost","root","","news-site")
or die("Connection failed : " . mysqli_connect_error());
?>


5️⃣ Run the Project
Open browser:

http://localhost/news-site
Admin login page:

http://localhost/news-site/admin






🚀 Future Scope
-Add user comments on posts
-Add newsletter/email subscription
-Add video news support
-Move to MVC Framework (Laravel / CodeIgniter)
-Add dark/light theme
-Add trending news algorithm


👨‍💻 Author
Raj Amarjeet Chauhan
