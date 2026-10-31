# 🎓 Student Records and Marks Analyzer

A Python-based command-line student record management system that stores student details, manages subject marks, calculates academic results, and generates class-level summaries using Python data structures.

## 📌 Project Overview

This project allows users to enter and manage multiple student records. Each student has a unique ID, name, and marks in three subjects: Python, Maths, and DBMS.

The program calculates total marks and average, assigns a result category, allows searching and updating student records, and performs set operations to analyze subject-wise performance.

## ✨ Features

- Add multiple student records.
- Store student details using nested dictionaries.
- Store subject names in a fixed tuple.
- Store marks in lists.
- Validate unique student IDs.
- Validate marks between 0 and 100.
- Calculate total marks and average.
- Assign result categories.
- Display complete student reports.
- Search student records using student ID.
- Update subject marks.
- Analyze unique and passed subjects using sets.
- Display class-level performance summaries.

## 📚 Subjects

| Subject | Type |
|---|---|
| Python | Fixed subject |
| Maths | Fixed subject |
| DS | Fixed subject |

## 🏆 Result Criteria

| Average Marks | Result |
|---|---|
| 75 or above | Distinction |
| 40 or above | Pass |
| Below 40 | Fail |

## 🛠️ Technologies Used

- Python 3
- Command Line Interface (CLI)
- Built-in Python Data Structures

## 📖 Python Concepts Used

- Lists
- Tuples
- Sets
- Dictionaries
- Nested Dictionaries
- List Indexing and Slicing
- List Methods and Traversal
- Tuple Unpacking
- Set Operations:
  - Union
  - Intersection
  - Difference
  - Symmetric Difference
- Conditional Statements
- Loops and Input Validation

## 📂 Project Structure

```text
Student-Records-and-Marks-Analyzer/
│
├── main.py
└── README.md
```

## ▶️ How to Run

**1. Clone the repository**

```bash
git clone YOUR_REPOSITORY_URL
```

**2. Open the project folder**

```bash
cd Student-Records-and-Marks-Analyzer
```

**3. Run the Python program**

```bash
python main.py
```

## 🧾 Sample Output

```text
----- STUDENT REPORT -----

S101 | Aman
Python: 78, Maths: 65, DS: 88
Total: 231
Average: 77.00
Result: Distinction

S102 | Riya
Python: 35, Maths: 72, DS: 61
Total: 168
Average: 56.00
Result: Pass

Unique subjects: {'Python', 'Maths', 'DS'}
Students recorded: 2
```

## 📦 Requirements

- Python 3 installed.
- No external libraries or packages required.

## 🎯 Learning Objective

The main objective of this project is to understand how Python data structures work together in a practical application. It provides hands-on practice with lists, tuples, sets, dictionaries, data manipulation, and basic student performance analysis.

## 👨‍💻 Author

**Ayush Rana**

B.Tech CSE (AI/ML) Student

GitHub: [ayushrana6900-jpg](https://github.com/ayushrana6900-jpg)