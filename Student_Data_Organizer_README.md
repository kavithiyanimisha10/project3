# 🎓 Student Data Organizer

## 📌 Project Overview

The **Student Data Organizer** is a Python command-line application
designed to manage student records efficiently. It allows users to
perform CRUD operations (Create, Read, Update, Delete) and manage
student subjects.

------------------------------------------------------------------------

## 🚀 Features

-   ➕ Add new student records
-   📄 Display all student details
-   ✏️ Update student information (Age & Subjects)
-   ❌ Delete student records
-   📚 View all unique subjects offered
-   🚪 Exit the program

------------------------------------------------------------------------

## 🧠 Concepts Used

This project demonstrates:

-   Lists (to store student records)
-   Dictionaries (to represent each student)
-   Tuples (to store ID and DOB)
-   Sets (to store unique subjects)
-   Loops and Conditional Statements
-   User Input Handling

------------------------------------------------------------------------

## 🗂️ Data Structure

Each student is stored in the following format:

``` python
{
    "id_dob": (student_id, dob),
    "name": name,
    "age": age,
    "grade": grade,
    "subjects": set(subjects)
}
```

------------------------------------------------------------------------

## 🛠️ How to Run the Project

### Step 1: Install Python

Make sure Python is installed on your system.

### Step 2: Save the File

Save your code as:

    student_data_organizer.py

### Step 3: Run the Program

    python student_data_organizer.py

------------------------------------------------------------------------

## 📋 Menu Options

  Option   Description
  -------- --------------------------
  1        Add Student
  2        Display All Students
  3        Update Student
  4        Delete Student
  5        Display Subjects Offered
  6        Exit

------------------------------------------------------------------------

## ✏️ Example

    Enter your choice: 1

    Enter student details.
    Enter student ID: 101
    Enter student name: John
    Enter Age: 20
    Enter Grade: A
    Enter Date of Birth: 2005-01-01
    How many subjects? 2
    Enter subject: Math
    Enter subject: Science

------------------------------------------------------------------------

## 🔄 Update Functionality

You can update: - Student Age - Student Subjects

------------------------------------------------------------------------

## ⚠️ Limitations

-   Data is stored temporarily (no database/file saving)
-   No validation for duplicate IDs
-   Limited error handling

------------------------------------------------------------------------

## 💡 Future Improvements

-   Add file storage (CSV/JSON)
-   Add database integration (SQLite/MySQL)
-   Input validation and error handling
-   GUI version using Tkinter or Web App (Flask/Django)
-   Search and filter functionality

------------------------------------------------------------------------

## 👨‍💻 Author

This project is created for learning Python and improving
problem-solving skills.

------------------------------------------------------------------------

## ⭐ Support

If you found this project helpful, consider giving it a ⭐ and sharing
it!

------------------------------------------------------------------------

## explanation video

https://drive.google.com/file/d/1vqHoBvLLAwPRlVq2TccLD4Qfp4UIrScB/view?usp=drive_link