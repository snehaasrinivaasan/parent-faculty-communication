
# Parent-Faculty-Communication

Parent-Faculty Communication Application – A web-based application that helps parents and faculty communicate and monitor student attendance, marks, notices, and academic progress.

# 🎓 Parent-Faculty Communication Application

## 👥 Team Members

- **S.Snehaa** (112505030)
- **G.Yogalakshmi** (112505040)

## 🛠️ Technologies Used

- **HTML** - Web Page Structure
- **CSS** - User Interface Design
- **JavaScript** - Frontend Interaction
- **Python Flask** - Backend Development
- **MySQL** - Database Management

## 📊 Project Objective

The main objectives of this project are:

1. Provide easy communication between parents and faculty
2. Allow parents to view student attendance
3. Allow parents to view student marks
4. Share important notices with parents
5. Provide parent-faculty messaging
6. Help parents monitor student academic progress

## 📁 Database

- **Database:** MySQL
- **Database Name:** `parent_faculty_db`

### Main Tables

- `users` - Parent and faculty login details
- `students` - Student information
- `attendance` - Attendance details
- `marks` - Student marks
- `notices` - Important announcements
- `messages` - Parent-faculty communication

## 🔄 System Flow

User Login → Frontend → Python Flask Backend → MySQL Database → Dashboard

## 📦 Project Modules

### 🔐 Login Module
Provides login authentication for parents and faculty.

### 👤 Student Profile
Displays student basic information.

### 📊 Attendance Module
Allows parents to view subject-wise attendance details.

### 📝 Marks Module
Displays student marks and grades.

### 📢 Notice Module
Displays important notices and announcements.

### 💬 Message Module
Allows parents and faculty to communicate through messages.

## 🚀 Execution Steps

### 1. Install Requirements

```bash
py -m pip install -r requirements.txt