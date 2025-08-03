# Online-voting-system-deploy
🗳️ Online Voting System

This is a simple web-based **Online Voting System** built using:
- HTML5 & CSS3 (Frontend)
- PHP (Backend)
- MySQL (Database)

Users can:
- Register as a Voter or Group
- Login securely
- Upload a profile image
- Cast votes (voter-side functionality to be expanded)
-------------------------------------------------------------------------

📁 Folder Structure

project-root/
├── api/
│ ├── connection.php
│ ├── login.php
│ └── register.php
├── css/
│ └── stylesheet.css
├── routes/
│ └── register.html
├── uploads/
├── index.html
└── README.md
🚀 Getting Started
----------------------------------------------------------------------------
✅ Requirements
- [XAMPP](https://www.apachefriends.org/index.html) or any PHP server
- MySQL Server (comes with XAMPP)
---------------------------------------------------------------------------
⚙️ Setup Instructions

1. Move the entire project folder into:
   C:/xampp/htdocs/
2. Start **Apache** and **MySQL** from the **XAMPP Control Panel**.
3. Open `http://localhost/phpmyadmin` and create a database named:
4. Run the following SQL in phpMyAdmin to create the `user` table:
 sql
CREATE TABLE user (
    id INT AUTO_INCREMENT PRIMARY KEY,
    name VARCHAR(100),
    mobile VARCHAR(15),
    password VARCHAR(255),
    address VARCHAR(255),
    photo VARCHAR(100),
    role INT,
    status INT,
    votes INT

);
5. Open the project in your brower
http://localhost/your-folder-name/
-------------------------------------------------------------------------
📌 Features
🔐 Secure Login for Voter & Group

📝 Registration with file upload

🗂️ Role-based user selection (Voter / Group)

🎨 Basic styling using external CSS

#Screenshot
<img width="1920" height="1080" alt="Screenshot_20250802_161243" src="https://github.com/user-attachments/assets/6c202bf4-a734-4aff-80ea-59a09bce7fcf" />

<img width="1920" height="1080" alt="Screenshot_20250803_085311" src="https://github.com/user-attachments/assets/55e37d0a-b5f3-45ab-8332-51069e49cbe5" />

<img width="1920" height="1080" alt="Screenshot_20250803_085323" src="https://github.com/user-attachments/assets/e7400667-1a17-4785-a79b-462973fe1eda" />

<img width="1920" height="1080" alt="Screenshot_20250803_085340" src="https://github.com/user-attachments/assets/983ba9c9-6d31-40ef-af82-25c50222a2cb" />

<img width="1920" height="1080" alt="Screenshot_20250803_085353" src="https://github.com/user-attachments/assets/97ccccdd-ae0d-4c38-8c37-fd3af802652c" />

<img width="1920" height="1080" alt="Screenshot_20250803_085404" src="https://github.com/user-attachments/assets/f9137208-2977-4191-a3da-93481dd40195" />

<img width="1920" height="1080" alt="Screenshot_20250803_085415" src="https://github.com/user-attachments/assets/2c779fa8-f3b3-48b3-ab90-7ab224403ca5" />
