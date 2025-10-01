# Student Marks Management & Report Card Generator

A Python console-based application that allows teachers to record
student marks, calculate grades, and generate report cards in a
structured format.

------------------------------------------------------------------------

## 🎯 Objective

This project provides a simple yet effective system to:\
- Add student details (Name, Roll Number, Class, Subjects, Marks).\
- Calculate total, percentage, and grade automatically.\
- Save student data in a CSV file for future reference.\
- Generate report cards in a readable tabular format.

------------------------------------------------------------------------

## 🚀 Features

-   Add new student records with subject-wise marks.\
-   Grade calculation based on percentage:
    -   A: 90% and above\
    -   B: 80--89%\
    -   C: 70--79%\
    -   D: 60--69%\
    -   Fail: below 60%\
-   Auto-calculates **Total Marks** and **Percentage**.\
-   Saves all records in `students.csv` without overwriting previous
    data.\
-   Generates report cards in a tabular format using
    [tabulate](https://pypi.org/project/tabulate/) (if installed), else
    prints as plain text.

------------------------------------------------------------------------

## 🛠️ Tools & Libraries

-   **Python Standard Library**
    -   `csv` → Store and retrieve student records\
    -   `os` → File handling\
-   **Optional Library**
    -   `tabulate` → Pretty-print tables in the console

Install tabulate (optional but recommended):

``` bash
pip install tabulate
```

------------------------------------------------------------------------

## 📂 Project Structure

    ├── athma.py          # Main application file
    ├── students.csv      # Auto-generated CSV file storing student records
    └── README.md         # Project documentation

------------------------------------------------------------------------

## ▶️ How to Run

1.  Clone or download the project.\

2.  Navigate to the project directory.\

3.  Run the application:

    ``` bash
    python athma.py
    ```

------------------------------------------------------------------------

## 📋 Usage Guide

When you run the program, you will see a menu:

    Student Marks Management System
    1. Add Student Details
    2. Show Report Cards
    3. Exit

-   **Option 1:** Add a new student's details (Name, Roll, Class,
    Subjects, and Marks).\
-   **Option 2:** Display all report cards stored in `students.csv`.\
-   **Option 3:** Exit the application.

------------------------------------------------------------------------

## 💾 Data Storage

-   All student details are saved in `students.csv`.\

-   Each record contains:

        Name | Roll | Class | Subject1 | Subject2 | ... | Total | Percentage | Grade

------------------------------------------------------------------------

## 📊 Sample Report (with tabulate)

    +---------+------+-------+---------+---------+---------+---------+-------+-------------+--------+
    | Name    | Roll | Class | Math    | Science | English | History | Total | Percentage  | Grade  |
    +---------+------+-------+---------+---------+---------+---------+-------+-------------+--------+
    | John    | 1    | 10    | 85      | 90      | 78      | 88      | 341   | 85.25       | B      |
    | Alice   | 2    | 10    | 95      | 92      | 89      | 90      | 366   | 91.50       | A      |
    +---------+------+-------+---------+---------+---------+---------+-------+-------------+--------+

------------------------------------------------------------------------

## 📌 Future Enhancements

-   Export report cards to PDF.
-   Add search functionality by roll number.
-   Provide editing/updating of student records.
-   -------------------------------------------------------------------------------------------------
##📩Contact

-👩‍💻*Developer:*Pabbu Hemalatha
-📧*Email:*pabbu.hemalatha24@gmail.com
-🪩*Github:*https://github.com/Hemalatha24574

💡Feel free to fork,contribut,or drop a message if you have ideas to improve this project!


