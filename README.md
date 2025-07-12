# 🧑‍🏫 E-Classroom Database Management System

A fully normalized Oracle-based database system for managing online classrooms. This project includes a ready-to-import `.dmp` file, query-based question/answer documentation, and a complete project report in PDF format.

---

## 📦 Included Files

| File                          | Description                                           |
|------------------------------|-------------------------------------------------------|
| `classroom_dump.dmp`         | Oracle dump file with full schema and sample data     |
| `queries_answers.txt`        | Questions & answers based on SQL queries              |
| `queries.sql`                | Executable SQL queries for testing                    |
| `E-Classroom_Project_Report.pdf` | Final project report covering design, ERD, normalization, etc. |

---

## 🛠️ Technologies Used

- Oracle SQL Plus / SQL Developer
- Oracle Database (tested on Oracle 19c)
- ER Modeling and Normalization (1NF–3NF)

---

## 🚀 How to Run This Project

### 1. Import the `.dmp` File

#### Option A: Using `imp` (legacy)
```bash
imp USER/PASS@ORCL file=classroom_dump.dmp full=y
````

#### Option B: Using `impdp` (Data Pump)

```bash
impdp USER/PASS@ORCL DIRECTORY=dp_dir DUMPFILE=classroom_dump.dmp FULL=Y
```

> Make sure `dp_dir` is a valid Oracle directory object pointing to the `.dmp` location.

### 2. Run Queries

Open `queries.sql` in SQL Plus or SQL Developer and run the SQLs to test functionality.

---

## 🧪 Educational Value

This project demonstrates:

* Proper **normalization** and **relational schema design**
* Real-world **student-course-classroom** modeling
* Query writing and **performance optimization**
* **Report writing & documentation** for academic submission

---

## 📄 Documentation

* Refer to `queries_answers.txt` for explanation of SQL queries.
* Refer to `E-Classroom_Project_Report.pdf` for the full academic report (ERD, use cases, normalization process, etc.)

---

## 👨‍💻 Author

* [Rohit Joshi](https://github.com/rohitjoshi333)

---

> A structured database for structured learning. 🎓
