Student Gradebook Analyzer

Project Overview

Student Gradebook Analyzer is a Python project developed using the Pandas library. The project reads student data from a CSV file and performs statistical analysis on students' marks. It calculates Average, Median, Maximum, Minimum, assigns Grades based on average marks, and sorts students according to their academic performance.



Objectives:

- Read student data from a CSV file.
- Calculate the Average marks of each student.
- Calculate the Median marks of each student.
- Find the Maximum marks scored by each student.
- Find the Minimum marks scored by each student.
- Assign Grades based on Average marks.
- Sort students according to their Average marks.



Technologies Used:

- Python
- Pandas



Dataset:

The dataset contains the following columns:

- Roll_No
- Name
- Maths
- Physics
- Chemistry
- English



Features:

The project performs the following operations:

- Reads data from the CSV file.
- Calculates Average marks.
- Calculates Median marks.
- Finds Maximum marks.
- Finds Minimum marks.
- Assigns Grades based on Average marks.
- Sorts students in descending order of Average marks.



Grade Criteria:

| Average Marks | Grade |
|---------------|-------|
| 90 - 99       |   A+  |
| 80 - 89       |   A   |
| 70 - 79       |   B+  |
| 60 - 69       |   B   |
| 50 - 59       |   C   |
| 40 - 49       |   D   |
| Below 40      |  FAIL |



Project Workflow:

1. Import the Pandas library.
2. Read the CSV file using `read_csv()`.
3. Calculate Average, Median, Maximum and Minimum marks.
4. Create a Grade column using a user-defined function.
5. Sort students according to their Average marks.
6. Display the sorted student records.



Required Library:

Install Pandas before running the project.

```bash
pip install pandas
```

---

How to Run:

1. Place the `students.csv` file in the project folder.
2. Open the Python file.
3. Run the program.

```bash
python student_grade_analyzer.ipynb
```



Output:

The program generates the following additional columns:

- Average
- Median
- Maximum
- Minimum
- Grade

The students are then sorted according to their Average marks in descending order.



Project Structure:


Student_Grade_Analyzer/
│
├── students.csv
├── student_grade_analyzer.ipynb
├── requirements.txt
└── README.md




Conclusion:

This project demonstrates how Python and Pandas can be used to analyze student academic records efficiently. It automates the calculation of Average, Median, Maximum, Minimum, and Grade, reducing manual work and improving accuracy. The project also provides a basic understanding of DataFrame operations, statistical functions, user-defined functions, and data sorting in Pandas.

---

## Author

Mayank