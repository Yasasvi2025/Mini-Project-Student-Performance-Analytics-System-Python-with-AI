# Student Performance Analytics System

## Python with AI – Mini Project

## Project Overview

The **Student Performance Analytics System** is a Python-based mini project that analyzes students' academic performance using marks, attendance, and department information. It uses **Python, NumPy, and Pandas** to process student data, calculate performance metrics, and generate meaningful insights.

The system helps identify top-performing students, analyze subject-wise and department-wise performance, assign grades, and evaluate pass/fail results.

## Technologies Used

- **Python** – Core programming and data analysis
- **Pandas** – Dataset loading, processing, and analysis
- **NumPy** – Numerical calculations and statistical operations
- **Google Colab / Jupyter Notebook** – Environment for running the project

## Concepts Covered

- Variables and data types
- Conditional statements
- Loops
- Functions
- NumPy arrays and calculations
- Pandas DataFrames
- Data cleaning and validation
- Statistical analysis
- Data grouping and aggregation
- Student performance analysis
- CSV file handling

## Dataset Description

The project uses a student dataset named **`student.csv`**.

The dataset contains student details, subject marks, and attendance information.

| Column | Description |
|---|---|
| `Student_ID` | Unique student identifier |
| `Name` | Student name |
| `Department` | Student's department |
| `Python` | Python subject marks |
| `SQL` | SQL subject marks |
| `HTML` | HTML subject marks |
| `CSS` | CSS subject marks |
| `JavaScript` | JavaScript subject marks |
| `Attendance` | Student attendance percentage |

## Project Objectives

1. Load and validate the student dataset.
2. Calculate each student's total and average marks.
3. Assign grades based on academic performance.
4. Determine student pass/fail results.
5. Identify the highest- and lowest-performing students.
6. Analyze performance across individual subjects.
7. Compare performance between departments.
8. Analyze grade distribution and attendance.
9. Use NumPy for numerical calculations.
10. Generate a final CSV report containing the analyzed student data.

## Key Features

### 1. Dataset Loading and Validation
Loads the CSV dataset into a Pandas DataFrame and checks the data before analysis.

### 2. Total and Average Marks
Calculates total marks and average marks for each student across the included subjects.

### 3. Grade Assignment
Assigns grades according to the grading criteria implemented in the program.

### 4. Pass/Fail Analysis
Evaluates student results using the pass/fail conditions defined in the program.

### 5. Top and Lowest Performers
Identifies students with the highest and lowest academic performance.

### 6. Subject-Wise Analysis
Examines performance in Python, SQL, HTML, CSS, and JavaScript.

### 7. Department-Wise Analysis
Compares student performance across departments.

### 8. Grade Distribution and Attendance
Analyzes grade distribution and attendance patterns.

### 9. NumPy Calculations
Uses NumPy to perform numerical calculations and summarize data.

### 10. CSV Report Generation
Exports the analyzed student data to `student_performance_analysis.csv`.

## Pass/Fail Criteria

The project uses the following criteria:

- A student must score at least **40 marks in every subject**.
- A student must have at least **75% attendance**.
- A student who meets both conditions is marked as **Pass**; otherwise, the student is marked as **Fail**.

## Project Workflow

1. Import the required libraries.
2. Load the `student.csv` dataset.
3. Validate and prepare the data.
4. Calculate total and average marks.
5. Assign grades and determine results.
6. Analyze top-performing students.
7. Perform subject-wise and department-wise analysis.
8. Analyze grade distribution and attendance.
9. Perform numerical calculations using NumPy.
10. Export the final analysis to a CSV file.
11. Display the project completion summary.

## How to Run the Project

### Option 1: Google Colab

1. Open [Google Colab](https://colab.research.google.com/).
2. Upload or open the project notebook.
3. Upload the dataset named `student.csv` when prompted.
4. Run the notebook cells in order.
5. Review the analysis and results.
6. Download the generated `student_performance_analysis.csv` report if needed.

### Option 2: Run Locally

1. Install Python.
2. Install the required libraries:

   ```bash
   pip install pandas numpy
   ```

3. Place the notebook and `student.csv` in the appropriate working environment.
4. Open the notebook in Jupyter Notebook or VS Code.
5. Run the cells in order.

## Output

The project generates:

- Student total and average marks
- Student grades and pass/fail results
- Highest- and lowest-performing student details
- Subject-wise performance summaries
- Department-wise performance summaries
- Grade distribution and attendance analysis
- NumPy calculation summaries
- `student_performance_analysis.csv` — the final analyzed dataset

## Project Structure

```text
Student-Performance-Analytics-System/
│
├── Mini_Project_Student_Performance_Analytics_System.ipynb
├── student.csv
├── README.md
├── Project_Documentation.pdf
└── student_performance_analysis.csv
```

*Note: The output CSV is generated when the notebook runs successfully.*

## Learning Outcomes

Through this project, students gain practical experience in:

- Using Python for data analysis
- Processing tabular data with Pandas
- Performing numerical calculations with NumPy
- Applying functions, loops, and conditional statements
- Analyzing academic performance
- Generating useful summaries from datasets
- Exporting processed results to CSV files

## Future Enhancements

- Add charts and interactive dashboards.
- Develop a web-based student performance interface.
- Include attendance and academic performance predictions.
- Add automated PDF report generation.
- Explore machine learning techniques for performance prediction.

## Conclusion

The **Student Performance Analytics System** demonstrates how Python, NumPy, and Pandas can be used to analyze student academic data systematically. It calculates performance metrics, evaluates results, compares subjects and departments, and generates a CSV report to support data-driven understanding of student performance.

## Author

**Python with AI – Mini Project**

## License

This project is intended for educational and academic purposes.
