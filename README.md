# 🎓 Computer Science Students Query Script

This project contains a Bash script that connects to a PostgreSQL database called `students` and executes various SQL queries to retrieve useful insights about students and courses. It's part of a hands-on exercise to practice shell scripting and PostgreSQL queries.

---

## 🗂️ Project Structure

.
├── students_info.sh # Main script file
└── README.md # Project documentation


---

## ⚙️ Prerequisites

- Linux or macOS environment (or WSL for Windows)
- PostgreSQL installed and running
- A `students` database already created
- A PostgreSQL user named `freecodecamp` with access to the `students` database
- Tables such as `students`, `courses`, `majors`, `majors_courses` prepopulated with data

---

## 🚀 How to Run

1. **Make the script executable:**

```bash
chmod +x students_info.sh
