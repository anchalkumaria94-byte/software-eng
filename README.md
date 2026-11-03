# Student Attendance Management System

A simple **Student Attendance Management System** developed in **C++** as an academic project. The system helps manage student details, record attendance, view attendance summaries, and calculate attendance percentages.

## 📌 Project Overview

The Student Attendance Management System is a menu-driven console application designed to make attendance management more organized and easier to maintain.

The project provides basic operations such as:

- Adding student details
- Displaying registered students
- Marking students as Present or Absent
- Viewing individual attendance records
- Calculating attendance percentage
- Saving and loading records using local files

The project is developed as an educational prototype and is not intended to replace a secure, institution-wide attendance system.

## ✨ Features

- **Add Student** – Register a student using ID, name, and class/section.
- **Display Students** – View all registered students.
- **Mark Attendance** – Record Present or Absent status.
- **View Attendance Summary** – View a student's attendance details.
- **Attendance Percentage** – Automatically calculate attendance percentage.
- **File Handling** – Store and retrieve attendance data using local files.
- **Input Validation** – Handle duplicate IDs and invalid inputs.

## 🛠️ Technologies Used

- **Programming Language:** C++
- **Concepts:** Functions, Classes/Structures, Loops, Conditional Statements
- **File Handling:** C++ File I/O
- **Interface:** Console / Command Line
- **Compiler:** GCC / MinGW

## 📂 Project Structure

```text
Student-Attendance-Management-System/
│
├── README.md
├── Student_Attendance_Management_System.cpp
├── student_data.txt
├── attendance_data.txt
└── Student_Attendance_Management_System_Project_Report.pdf
```

> File names can be changed according to the actual files uploaded to this repository.

## 🔄 System Workflow

```text
Start
  ↓
Load Student & Attendance Files
  ↓
Display Main Menu
  ↓
Choose Operation
  ↓
Add / Display / Mark / View
  ↓
Validate Input
  ↓
Update Records
  ↓
Save Data
  ↓
Return to Menu / Exit
```

## 📊 Attendance Calculation

The attendance percentage is calculated using:

```text
Attendance (%) = (Present Sessions / Total Sessions) × 100
```

For example:

```text
Present Sessions = 8
Total Sessions = 10

Attendance = (8 / 10) × 100
            = 80%
```

## 🖥️ Main Menu

The application provides the following options:

```text
STUDENT ATTENDANCE MANAGEMENT SYSTEM

1. Add Student
2. Display Students
3. Mark Attendance
4. View Attendance Summary
5. Exit
```

## 🧪 Testing

The project includes test scenarios for:

| Test Case | Description |
|---|---|
| TC-01 | Add a new student |
| TC-02 | Reject duplicate student ID |
| TC-03 | Display registered students |
| TC-04 | Mark student Present |
| TC-05 | Mark student Absent |
| TC-06 | Search for unknown student ID |
| TC-07 | Handle zero attendance sessions |
| TC-08 | Calculate attendance percentage |

The report includes validation examples such as **8 present sessions out of 10 = 80% attendance**.

## 🚀 How to Run

### 1. Clone the Repository

```bash
git clone YOUR_GITHUB_REPOSITORY_LINK
```

### 2. Open the Project

Open the project folder in **VS Code** or another C++ IDE.

### 3. Compile

Using g++:

```bash
g++ Student_Attendance_Management_System.cpp -o attendance
```

### 4. Run

Windows:

```bash
attendance.exe
```

or:

```bash
.\attendance.exe
```

## 👩‍💻 Author

**Anchal Kumari**

- **UID:** 25BCD10251
- **Class/Section:** 25BBCD4A
- **Program:** Bachelor of Computer Applications (BCA)
- **University:** Chandigarh University

## 🎓 Academic Project

This project was developed for academic/educational purposes as a C++ programming project.

## 🔮 Future Enhancements

Future versions could include:

- Secure login system
- Teacher and administrator roles
- Database integration
- Class-wise and subject-wise reports
- Date-wise attendance tracking
- Search and edit functionality
- GUI/Web/Mobile interface
- Backup and restore
- Improved privacy and security
- Integration with an institution-approved student information system

These improvements are also identified in the project report's future-work section.

## 📄 Project Report

The complete project report is available in this repository:

**Student_Attendance_Management_System_Project_Report.pdf**

## 📚 References

1. Bjarne Stroustrup, *The C++ Programming Language*, 4th Edition.
2. cppreference.com – C++ language and standard library reference.
3. ISO/IEC 14882 – Programming Languages — C++.
4. ISO/IEC 25010 – Systems and software Quality Requirements and Evaluation.
5. Pressman & Maxim, *Software Engineering: A Practitioner's Approach*, 8th Edition.
