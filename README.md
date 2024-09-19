# Attendance Management System 🎓📝

Welcome to the Attendance Management System! This application allows you to manage attendance using QR Codes. It is built with Flask and MySQL, providing a user-friendly interface to track student attendance effectively.

## Features ✨
- **User Authentication**: Secure login/logout system.
- **Attendance Management**: Add, edit, and view attendance records.
- **Course Management**: Manage courses and associated data.
- **Room Management**: Keep track of rooms where classes are held.
- **User Management**: Manage user roles and information.
- **Responsive Design**: Works well on various devices.

## Getting Started 🚀

### Prerequisites
- Python 3.x
- Flask
- Flask-MySQL
- MySQL Server

### Installation

1. **Clone the Repository**:
   ```bash
   git clone <repository-url>
   cd attendance-management

🛠️ Features
      User Authentication 🔒
        Secure login/logout functionality
        Password hashing using Werkzeug and MD5


CRUD Operations 📝
Create, Read, Update, Delete for:
Attendance
Buffer
Courses
Rooms
Semesters
Students
Subjects
Teachers
Users



Session Management 🗂️
Secure sessions to manage user state


MySQL Integration 🐬
Seamless connection and interaction with MySQL database
Responsive Templates 📱


Rendered using Flask's render_template for a dynamic UI
📦 Installation
Prerequisites
Python 3.x 🐍
MySQL Server 🐬
pip (Python package installer)


🗂️ Project Structure
flask-management-system/
├── app.py
├── handler.py
├── templates/
│   ├── index.html
│   ├── login.html
│   ├── attendence.html
│   ├── edit_attendence.html
│   ├── buffer.html
│   ├── edit_buffer.html
│   ├── course.html
│   ├── edit_course.html
│   ├── room.html
│   ├── edit_room.html
│   ├── semester.html
│   ├── edit_semester.html
│   ├── student.html
│   ├── edit_student.html
│   ├── subject.html
│   ├── edit_subject.html
│   ├── teacher.html
│   ├── edit_teacher.html
│   ├── users.html
│   └── edit_users.html
├── static/
│   ├── css/
│   ├── js/
│   └── images/
├── requirements.txt
└── README.md


🔧 Usage
Authentication
Login: Navigate to /login to access the login page. 🔑
Logout: Use the /logout route to end the session. 🚪
Managing Entities
Each entity has its own set of routes for managing data:

View All:

Attendance: /attendence 📅
Buffer: /buffer 🗄️
Courses: /course 📚
Rooms: /room 🏢
Semesters: /semester 📆
Students: /student 👩‍🎓👨‍🎓
Subjects: /subject 📖
Teachers: /teacher 👩‍🏫👨‍🏫
Users: /users 👥
Add/Edit:

Attendance: /edit_attendence/<action>/<id> ➕✏️
Buffer: /edit_buffer/<action>/<id> ➕✏️
Courses: /edit_course/<action>/<id> ➕✏️
Rooms: /edit_room/<action>/<id> ➕✏️
Semesters: /edit_semester/<action>/<id> ➕✏️
Students: /edit_student/<action>/<id> ➕✏️
Subjects: /edit_subject/<action>/<id> ➕✏️
Teachers: /edit_teacher/<action>/<id> ➕✏️
Users: /edit_users/<action>/<id> ➕✏️

