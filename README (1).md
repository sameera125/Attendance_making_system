# 🧾 Attendance Management System (C++)

A simple **console-based Attendance Management System** written in **C++**, designed for teachers and students to record and view attendance efficiently.

---

## 🚀 Features

### 👨‍🏫 Teacher Dashboard
- Add new students  
- Mark daily attendance (Present/Absent)  
- Display all student attendance records  
- Password-protected access  

### 👨‍🎓 Student Dashboard
- View personal attendance record  

---

## 🧩 How It Works

1. **Main Menu**  
   - Choose between **Teacher Dashboard** or **Student Dashboard**

2. **Teacher Dashboard (Password Protected)**  
   - Default password: `admin123`  
   - Add student names  
   - Mark attendance by entering ‘P’ for present or ‘A’ for absent  
   - View all attendance records  

3. **Student Dashboard**  
   - Enter your name to view your own attendance record  

---

## 🛠️ Requirements

- C++ Compiler (e.g., GCC, MinGW, Clang)
- Any terminal or IDE that supports console input/output  

---

## 🧮 How to Compile and Run

### On Windows (MinGW)
```bash
g++ attendance_making_system.cpp -o attendance_system
attendance_system.exe
```

### On Linux / macOS
```bash
g++ attendance_making_system.cpp -o attendance_system
./attendance_system
```

---

## 🗂️ Project Structure

```
📁 Attendance-Management-System
 ├── attendance_making_system.cpp   # Main source code
 ├── README.md                      # Project documentation
```

---

## 🧑‍💻 Example Interaction

```
--- Attendance System Main Menu ---
1. Teacher Dashboard
2. Student Dashboard
3. Exit
Enter your choice: 1

Enter admin password: admin123

--- Teacher Dashboard ---
1. Add Student
2. Mark Attendance
3. Display All Records
4. Logout
```

---

## 🔒 Default Credentials
| Role | Password |
|------|-----------|
| Teacher (Admin) | `admin123` |

---

## ✨ Author
**Sk Sameera**  
📧 shaiksameera5002@gmail.com

