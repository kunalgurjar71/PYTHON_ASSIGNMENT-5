# 🎓 Smart Student Performance Analyzer (Capstone Project)

### 👨‍🎓 Student Details

* **Name:** Kunal Lohia
* **Course:** BCA (AI & DS) – Semester 1
* **Subject:** Problem Solving with Python
* **Unit:** Capstone Project
* **Project:** Smart Student Performance Analyzer

---

### 📌 Project Overview

This is a **Python-based Data Analytics Project** designed to evaluate and visualize student performance using real-world CSV data.

The system performs:

✔ Data Loading & Cleaning
✔ OOP-based Modeling of Students
✔ Subject-wise and Student-wise Analysis
✔ Dashboard Visualization
✔ Summary Export (CSV + Text Report)
✔ Sample Dataset Auto-Creation for Demo

It works through a **menu-driven CLI**, making it highly interactive.

---

### 🧠 Concepts Used

* Object-Oriented Programming (Classes & Methods)
* Data Cleaning using **Pandas & NumPy**
* Data Visualization using **Matplotlib**
* File Handling (CSV I/O)
* Statistics (Grades, Averages, Ranking)
* CLI-based UI using loops and exception handling
* Logging for debugging and traceability

---

### ⚙️ Features Summary

| Feature                 | Description                                         |
| ----------------------- | --------------------------------------------------- |
| CSV Loading & Cleaning  | Reads dataset, fixes missing/invalid data           |
| OOP Student Modeling    | Creates structured student objects                  |
| Summary Table           | Roll No, Total, Average, Grade & Subject-wise marks |
| Dashboard               | 📊 Bar, Pie, Line & Scatter combined                |
| Top & Bottom Performers | Automatically identifies best & weak students       |
| Export                  | Cleaned CSV, Summary CSV & Text Report              |
| Quick Run               | Fully automatic workflow with sample data           |

---

### 📊 Output Files Generated

| Output                              | Description                            |
| ----------------------------------- | -------------------------------------- |
| `cleaned_student_data.csv`          | Cleaned dataset used in analysis       |
| `student_summary.csv`               | Student marks summary with grade       |
| `student_performance_dashboard.png` | 2×2 visualization dashboard            |
| `performance_summary.txt`           | Class average, top/bottom performers   |
| `sample_student_scores.csv`         | Auto-created if no dataset is provided |

Outputs are stored inside the **output/** folder.

---

### 🚀 How to Run the Program

1️⃣ Ensure Python and required libraries are installed

```
pip install pandas numpy matplotlib
```

2️⃣ Run the main program:

```
python student_performance_analyzer.py
```

3️⃣ Follow the on-screen menu options

✔ For instant results → Choose **Quick Run (Option 7)**

---

### 📂 Folder Structure

```
📁 Smart Student Performance Analyzer
│
├── data/
│   └── sample_student_scores.csv     # Created automatically if missing
│
├── output/
│   ├── cleaned_student_data.csv
│   ├── student_summary.csv
│   ├── student_performance_dashboard.png
│   └── performance_summary.txt
│
├── student_performance_analyzer.py   # Main Python Script
└── README.md
```

---

### 🧮 Grading Logic

| Average Marks | Grade |
| ------------- | ----- |
| 90+           | A+    |
| 80–89         | A     |
| 70–79         | B     |
| 60–69         | C     |
| 50–59         | D     |
| Below 50      | F     |

---

### 🎯 Learning Outcomes

Through this project, I gained practical knowledge of:

* Data science workflow (load → clean → analyze → visualize → export)
* Representing data using OOP in Python
* Multi-plot dashboards in Matplotlib
* Writing automated grading & reporting systems
* File handling and error-safe coding practices

---

### 🙏 Acknowledgement

Special thanks to faculty for guidance in Capstone implementation and review.

---

📌 *This project is developed for academic learning purposes only.*
