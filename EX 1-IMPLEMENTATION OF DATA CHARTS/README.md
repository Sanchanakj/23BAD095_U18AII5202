# Experiment 1 – Implementation of Data Charts

## Aim
To analyze student performance data and visualize key insights using different data chart techniques in R.

---

## Objective
- To understand the structure of student performance data.
- To compute average marks from multiple assessments.
- To visualize the data using bar charts, line charts, and pie charts.
- To interpret trends and distributions from graphical representations.

---

## Dataset Description
**File:** `1.student_performance.csv`

The dataset contains the following attributes:
- `Student_ID` – Unique identifier for each student
- `Subject` – Subject name
- `Internal_Test1` – Marks obtained in Internal Test 1
- `Internal_Test2` – Marks obtained in Internal Test 2
- `Assignment_Marks` – Marks obtained in assignments
- `Final_Grade` – Final grade obtained by the student

---

## Methodology
1. Load the dataset into R using `read.csv()`.
2. Calculate the average marks for each student using internal tests and assignments.
3. Group the data subject-wise to compute average performance.
4. Generate different data charts using `ggplot2`.
5. Interpret the visual output to understand student performance trends.

---

## Visualizations Implemented

### 1️⃣ Subject-wise Average Marks (Bar Chart)
- Displays the average marks obtained in each subject.
- Helps compare performance across different subjects.

📁 Output File:
- `Subject-wise Average Marks.png`

---

### 2️⃣ Performance Trend Across Assessments (Line Chart)
- Shows average performance across assessment types.
- Helps identify trends between internal tests and assignments.

📁 Output File:
- `Performance Trend Across Assessments.png`

---

### 3️⃣ Final Grade Distribution (Pie Chart)
- Represents the proportion of students in each final grade category.
- Helps understand overall grade distribution.

📁 Output File:
- `Final Grade Distribution.png`

---

## Tools & Libraries Used
- R (version 4.4.1)
- ggplot2
- dplyr
- tidyr
- RStudio

---


## Conclusion
Data charts are effective tools for understanding and communicating insights from educational datasets.  
This experiment demonstrates how R can be used to perform data analysis and create meaningful visualizations for academic performance evaluation.

---

