A **robust and intelligent attendance management system** that authenticates individuals using **facial recognition powered by deep learning**.  
This project automates attendance tracking for **classrooms, workplaces, and events**, providing accuracy, security, and convenience.

---

## 📋 Features

- 🔐 **Role-based access** for administrators and lecturers  
- 🧭 **Intuitive interface** to manage courses, units, venues, and attendance records  
- 📸 **Multi-image capture** for improved facial recognition accuracy  
- 🎓 **Perfect for college projects** in AI, computer vision, or web development  

---

## 🗂️ Project Structure

```plaintext
Face-Recognition-Attendance-System/
├── database/
│   ├── attendance-db.sql         # SQL file to initialize the database
│   └── database_connection.php   # Database connection script
├── models/
│   └── face-api-models.js        # Face API models (JavaScript)
├── resources/
│   ├── assets/
│   │   ├── css/                  # Stylesheets
│   │   └── javascript/           # Client-side scripts
│   ├── images/                   # General images
│   ├── labels/                   # Stored face images of registered students
│   ├── lib/
│   │   └── global-functions.php  # Global PHP functions
│   ├── pages/
│   │   ├── admin/                # Admin pages
│   │   ├── lecturer/             # Lecturer pages
│   │   └── login.php             # Login page
├── index.php                     # Main entry point
├── .htaccess                     # Apache redirect and rewrite rules
└── README.md                     # Project documentation
🚀 Setup Guide
Follow these steps to install and run the project locally:

1️⃣ Clone or Download the Repository
bash
Copy code
git clone https://github.com/yashvanthgp/Face-Recognition-Attendance-System.git
Or download the ZIP file directly and extract it.

2️⃣ Move the Project to Your Server Directory
If using XAMPP, place the project inside:

bash
Copy code
xampp/htdocs/Face-Recognition-Attendance-System
Use a simple folder name like attendance-system for easier access.

3️⃣ Start XAMPP
Open XAMPP Control Panel

Start the Apache and MySQL services

4️⃣ Set Up the Database
Open phpMyAdmin

Create a new database — recommended name: attendance_db

Import the SQL file located in:

pgsql
Copy code
database/attendance-db.sql
Ensure your project configuration matches the database name.

5️⃣ Launch the Application
Open your browser and visit:

arduino
Copy code
http://localhost/{your-project-folder-name}
🧑‍💻 User Guide
👨‍💼 Administrator Login
Email: admin@gmail.com
Password: @admin_

Once logged in:

Add or manage students

Create and manage courses, units, and venues

Add at least two students and capture five clear facial images for each.
Avoid poor lighting or blurry images. You can retake images by clicking on them.

👨‍🏫 Lecturer Login
You can:

Create a lecturer account via the Admin Panel, or

Use the default credentials:

Email: mark@gmail.com
Password: @mark_

Once logged in:

Select a course, unit, and venue

Start Face Recognition to take attendance automatically

📊 Lecturer Panel Features
Export attendance data to Excel

Manage and review attendance sessions easily

🏷️ License & Credits
This project is licensed under the MIT License.

Credits
This project is based on the open-source repository
Face-Recognition-Attendance-System
by Francis Njenga.

Modifications and enhancements by Yashvanth GP, 2025.

📧 For inquiries or support: yashvanthgp236@gmail.com

sql
Copy code

---

## 📜 **LICENSE File (MIT License)**

```text
MIT License

Copyright (c) 2025 Yashvanth GP
Original Project: Face Recognition Attendance System by Francis Njenga

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
