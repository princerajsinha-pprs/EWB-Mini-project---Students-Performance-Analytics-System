# Student Performance Analytics System

## 📌 Project Overview

**Student Performance Analytics System** is a Python-based data analysis project developed for the **Python with AI** course.

The project reads student academic data, processes the marks using **Python, NumPy and Pandas**, and generates meaningful performance insights such as total marks, average marks, grades, pass/fail status, class performance, subject-wise analysis, and top-performing students.

---

## 🎯 Project Objective

The main objective is to analyze student performance from a structured dataset and convert raw student records into useful academic information.

The system answers questions such as:

- Which student has the highest average?
- Which student has the lowest average?
- What is the overall class average?
- How many students passed?
- How many students failed?
- Which subject has the highest average?
- Who are the top-performing students?

---

## 🛠️ Technologies Used

- Python
- NumPy
- Pandas
- Google Colab / Jupyter Notebook
- CSV Dataset
- GitHub

---

## 📂 Project Structure

```text
student-performance-analytics/
│
├── Student_Performance_Analytics.ipynb
├── students.csv
├── student_analysis_output.csv
├── subject_analysis_output.csv
├── README.md
└── Project_Documentation.md
```

| File | Purpose |
|---|---|
| `Student_Performance_Analytics.ipynb` | Main Google Colab project |
| `students.csv` | Student input dataset |
| `student_analysis_output.csv` | Processed student performance |
| `subject_analysis_output.csv` | Subject-wise analysis |
| `README.md` | Project information and instructions |
| `Project_Documentation.md` | Detailed project documentation |

---

## 📊 Dataset

The project uses **20 student records**.

### Dataset Columns

| Column | Description |
|---|---|
| Student_ID | Unique student identification number |
| Name | Student name |
| Department | Student department |
| Python | Python marks |
| NumPy | NumPy marks |
| Pandas | Pandas marks |
| Statistics | Statistics marks |
| Data_Analysis | Data Analysis marks |
| Attendance | Attendance percentage |

---

## 🧮 Project Calculations

### Total Marks

```text
Total = Python + NumPy + Pandas + Statistics + Data Analysis
```

NumPy is used for the numerical calculation.

### Average Marks

```text
Average = Total Marks / 5
```

NumPy's `mean()` function is used.

---

## 🏆 Grading System

| Average Marks | Grade |
|---:|:---|
| 90–100 | A+ |
| 80–89.99 | A |
| 70–79.99 | B |
| 60–69.99 | C |
| 50–59.99 | D |
| Below 50 | F |

---

## ✅ Pass/Fail Rule

A student is considered **Pass** when:

1. Every subject has at least **40 marks**, and
2. Attendance is at least **75%**.

If either condition is not satisfied, the student is marked **Fail**.

---

## 🔍 Main Features

### Student-wise Analysis
- Total marks
- Average marks
- Grade
- Attendance
- Pass/Fail result

### Class-level Analysis
- Total number of students
- Overall class average
- Highest average
- Lowest average
- Number of passed students
- Number of failed students

### Subject-wise Analysis
For every subject:
- Average marks
- Highest marks
- Lowest marks

### Top Performers
Students are sorted by average marks to identify the **Top 3 performers**.

---

## 🐍 Python Concepts Used

- Variables
- Data types
- Lists
- Dictionaries
- Functions
- `if-elif-else`
- `for` loops
- Pandas DataFrame
- NumPy functions
- Data filtering
- Data sorting
- CSV file handling

---

## 🔢 NumPy Usage

Example:

```python
def calculate_total(marks):
    return int(np.sum(marks))
```

Average:

```python
def calculate_average(marks):
    return round(float(np.mean(marks)), 2)
```

---

## 🐼 Pandas Usage

Pandas is used to:

- Create DataFrames
- Load and organize data
- Add calculated columns
- Filter records
- Sort students
- Analyze data
- Export results to CSV

Example:

```python
df = pd.DataFrame(data)
```

---

## 🔄 Project Workflow

```text
Student Dataset
      ↓
Load Data
      ↓
Pandas DataFrame
      ↓
Calculate Total Marks
      ↓
Calculate Average
      ↓
Assign Grade
      ↓
Check Pass/Fail
      ↓
Class Analysis
      ↓
Subject-wise Analysis
      ↓
Find Top Performers
      ↓
Export Results
```

---

## 🚀 How to Run in Google Colab

### Step 1: Open Google Colab

Open [Google Colab](https://colab.research.google.com/).

### Step 2: Open the Notebook

Upload:

```text
Student_Performance_Analytics.ipynb
```

### Step 3: Run the Cells

Use:

```text
Shift + Enter
```

to run each cell.

### Step 4: View Results

The notebook displays:

- Student dataset
- Student-wise performance
- Class summary
- Subject analysis
- Top 3 performers

---

## 💾 Output Files

### `student_analysis_output.csv`

Contains:

```text
Student_ID
Name
Total
Average
Grade
Attendance
Result
```

### `subject_analysis_output.csv`

Contains:

```text
Subject
Average
Highest
Lowest
```

---

## 📈 Expected Results

Using the included dataset:

```text
Total Students: 20
Class Average: 73.6
Highest Average: 93.0
Lowest Average: 45.0
Passed Students: 15
Failed Students: 5
```

### Top 3 Performers

| Rank | Student | Average | Grade |
|---:|---|---:|:---|
| 1 | Kavya Mishra | 93.0 | A+ |
| 2 | Priya Verma | 92.0 | A+ |
| 3 | Harsh Tiwari | 90.6 | A+ |

---

## 📚 Learning Outcomes

This project demonstrates:

- Dataset creation and handling
- Pandas DataFrames
- NumPy numerical calculations
- Reusable Python functions
- Loops and conditions
- Student performance analysis
- CSV export
- Project organization
- GitHub project submission

---

## 📸 Screenshots

Add screenshots after running the Google Colab notebook:

1. Dataset
2. Student-wise performance
3. Class summary
4. Subject-wise analysis
5. Top 3 performers

---

## 👨‍🎓 Student Details

**Student Name:** Prince Raj

college: Rungta college of engineering and technology

**Email:** princerajsinha979@gmail.com

**Course:** Python with AI

**Project Title:** Student Performance Analytics System

**GitHub Repository:** __________________________

---

## 📅 Submission

The EWB project guideline specifies the submission deadline as:

**15 October 2026**

Before submission, verify that the project, dataset, README, documentation and required GitHub files are complete.

---

## 📌 GitHub

Create a repository named:

```text
student-performance-analytics
```

Upload the project files and verify that the repository contains the notebook, dataset, README and documentation.

Then copy the GitHub repository URL and submit it through the EWB Google Form as instructed.

---

## 👤 Author

**Student:** Prince Raj

**Email:** princerajsinha979@gmail.com

**Course:** Python with AI

**Project:** Student Performance Analytics System

---

## ⭐ Project Status

**Status:** Completed and Tested

**Tools:** Python + NumPy + Pandas + Google Colab
