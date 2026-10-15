# 🐍 Python OOP Projects — Management Systems

<p align="center">
  <img src="https://img.shields.io/badge/Python-3.10%2B-blue?logo=python&logoColor=white" alt="Python 3.10+">
  <img src="https://img.shields.io/badge/Projects-4-orange" alt="4 Projects">
  <img src="https://img.shields.io/badge/Concept-Object--Oriented%20Programming-purple" alt="OOP">
  <img src="https://img.shields.io/badge/Storage-CSV%20%7C%20TXT-green" alt="CSV and TXT">
  <img src="https://img.shields.io/badge/Status-Learning%20Projects-brightgreen" alt="Learning Projects">
</p>

## 🌟 About This Repository

Welcome to my **Python OOP Projects Repository!** 🚀

This repository contains four beginner-friendly, menu-driven management systems developed using **Python and Object-Oriented Programming (OOP)**.

These projects demonstrate how fundamental programming concepts can be applied to practical problems, including managing student records, organizing library books, handling simulated bank accounts, and calculating employee salaries.

📌 **Main objectives:**
- 🧠 Strengthen Python programming and OOP fundamentals.
- 🏗️ Learn to design classes, objects, and reusable methods.
- 📂 Practice file handling using CSV and TXT files.
- 🛡️ Implement input validation and exception handling.
- 💻 Build practical projects suitable for learning and college demonstrations.

---

# 📚 Projects Overview

## 🎓 Project 01 — Student Management System

**Description:** A menu-driven application for managing student information and academic performance.

### ✨ Features

- ➕ Add new students.
- 📋 Display student records.
- 🔍 Search students by student ID.
- ✏️ Update student information.
- 🗑️ Delete student records.
- 📊 Calculate individual and overall average marks.
- 💾 Save records in CSV and TXT files.
- 🔄 Load saved records automatically from CSV.

### 🛠️ Concepts Used

`Classes & Objects` · `Encapsulation` · `Inheritance` · `Abstraction` · `Lists` · `File Handling` · `Exception Handling`

### 📁 Data Files

- `students.csv`
- `students.txt`

### ▶️ Run the Project

```bash
python student_management.py
```

---

## 📖 Project 02 — Library Management System

**Description:** An application for maintaining book records, managing book availability, and tracking borrowing activity.

### ✨ Features

- ➕ Add books to the library.
- 🔎 Search books by ID or title.
- 📤 Issue books to borrowers.
- 📥 Return issued books.
- 📚 Display all registered books.
- ✅ Display available books.
- 🔢 Track total and available copies.
- 💾 Save records in CSV and TXT files.
- 🔄 Load saved book records automatically.

### 🛠️ Concepts Used

`Classes & Objects` · `Encapsulation` · `Inheritance` · `Abstraction` · `Lists` · `Conditional Statements` · `File Handling`

### 📁 Data Files

- `books.csv`
- `books.txt`

💡 **Future improvement:** Add book due dates, overdue fines, member IDs, and borrowing history.

### ▶️ Run the Project

```bash
python library_management.py
```

---

## 🏦 Project 03 — Bank Account Management System

**Description:** A simulated banking application for creating accounts, managing balances, and maintaining transaction records.

### ✨ Features

- 🆕 Create savings and current accounts.
- 💰 Deposit money.
- 💸 Withdraw money.
- 🧾 Check account balances.
- 👥 Display all registered accounts.
- 📜 Maintain transaction history.
- 💾 Save account and transaction data in CSV files.
- 📄 Generate readable TXT records.
- 🔄 Load saved records automatically.

### 🛠️ Concepts Used

`Classes & Objects` · `Encapsulation` · `Inheritance` · `Abstraction` · `Decimal Arithmetic` · `Lists & Dictionaries` · `File Handling`

### 📁 Data Files

- `accounts.csv`
- `transactions.csv`
- `bank_records.txt`

⚠️ **Disclaimer:** This is an educational banking simulation. It does not implement production-grade authentication, encryption, or financial security and must not be used for real banking.

### ▶️ Run the Project

```bash
python bank_management.py
```

---

## 💼 Project 04 — Employee Payroll System

**Description:** An employee management and payroll application for maintaining employee records, calculating salaries, and generating payslips.

### ✨ Features

- ➕ Add employee records.
- 🧮 Calculate gross and net salaries.
- 🧾 Generate individual payslips.
- 🔍 Search employees by employee ID.
- 👥 Display all employees.
- ✏️ Update employee records.
- 💾 Save payroll data in CSV and TXT files.
- 🔄 Load saved employee records automatically.

### 🧮 Salary Calculation

**Gross Salary**

`Gross Salary = Basic Salary + Allowances`

**Net Salary**

`Net Salary = Gross Salary − Deductions`

### 🛠️ Concepts Used

`Classes & Objects` · `Encapsulation` · `Inheritance` · `Abstraction` · `Decimal Arithmetic` · `File Handling` · `Exception Handling`

### 📁 Data Files

- `employees.csv`
- `payroll_records.txt`
- Individual `payslip_EMPLOYEE_ID.txt` files

### ▶️ Run the Project

```bash
python employee_payroll.py
```

---

# 🧰 Technologies & Tools

| Technology | Purpose |
|---|---|
| 🐍 Python | Core programming language |
| 🏗️ OOP | Code organization and reusable design |
| 📊 CSV | Structured record storage |
| 📝 TXT | Human-readable reports |
| 🛡️ Exception Handling | Handling errors and invalid input |
| 💻 VS Code / PyCharm / IDLE | Development environment |
| 🔧 Git & GitHub | Optional version control and project hosting |

✅ **No external Python packages are required** for the four versions described here. Python's standard library provides the required functionality.

---

# 📂 Repository Structure

```text
🐍 Python_OOP_Projects/
│
├── 🎓 Project_01_Student_Management/
│   ├── student_management.py
│   ├── students.csv
│   └── students.txt
│
├── 📚 Project_02_Library_Management/
│   ├── library_management.py
│   ├── books.csv
│   └── books.txt
│
├── 🏦 Project_03_Bank_Management/
│   ├── bank_management.py
│   ├── accounts.csv
│   ├── transactions.csv
│   └── bank_records.txt
│
└── 💼 Project_04_Employee_Payroll/
    ├── employee_payroll.py
    ├── employees.csv
    ├── payroll_records.txt
    └── payslip_EMPLOYEE_ID.txt
```

📌 *The directory structure is a suggested organization. Run each program from its own project directory so that its data files remain separate.*

---

# ⚙️ Installation & Setup

### 1️⃣ Install Python

Install Python 3.10 or later from the official website:

🔗 https://www.python.org/downloads/

### 2️⃣ Download the Repository

Clone your GitHub repository:

```bash
git clone YOUR_REPOSITORY_URL
```

Alternatively, download the repository as a ZIP file and extract it.

### 3️⃣ Open the Project Folder

Open the relevant project directory in VS Code or your preferred editor.

### 4️⃣ Run the Program

Open the terminal in that directory and execute the appropriate command listed under the project.

### 5️⃣ Test the Features

Try adding, searching, updating, and displaying records. For projects that support automatic loading, restart the program to check that saved data persists.

---

# 🧪 Testing Checklist

Use this checklist when testing each project.

- [ ] ➕ Add a new record.
- [ ] 🔍 Search for an existing record.
- [ ] ❌ Search for a nonexistent ID.
- [ ] ⚠️ Enter invalid data.
- [ ] 🔁 Test duplicate IDs where applicable.
- [ ] 🧮 Verify calculations.
- [ ] 💾 Save records.
- [ ] 🔄 Restart the program and check saved data.
- [ ] 📄 Inspect the generated CSV and TXT files.

**Tip:** Back up your CSV and TXT files before testing operations that overwrite stored records.

---

# 🚀 Future Improvements

These projects can be expanded with additional functionality:

- 🗄️ Integrate SQLite or MySQL for database storage.
- 🖥️ Create graphical interfaces using Tkinter or PyQt.
- 🌐 Build web applications using Flask or FastAPI.
- 🔐 Add authentication and role-based access.
- 📈 Generate charts and analytical reports.
- 🧪 Add automated tests using `unittest` or `pytest`.
- 📝 Improve logging, validation, and error reporting.

---

# 🎯 Learning Outcomes

By developing these projects, you can practice:

- Understanding classes, objects, and constructors.
- Applying encapsulation, inheritance, and abstraction.
- Writing modular and reusable Python code.
- Using lists, dictionaries, loops, and conditional statements.
- Validating input and handling exceptions.
- Reading and writing CSV and TXT files.
- Building menu-driven applications.
- Implementing basic data persistence.

---

# 👨‍💻 About This Project Collection

These projects are designed for **Python practice, Object-Oriented Programming coursework, and beginner-level college demonstrations**.

They provide a foundation for building larger applications and exploring databases, web development, testing, and software engineering.

⭐ If you find these projects useful, consider starring the repository on GitHub!

**Made with ❤️ and Python 🐍**



