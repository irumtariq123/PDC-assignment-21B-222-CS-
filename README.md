# linear and parallel execution

This project involves processing two CSV files: one containing student information and the other containing fee payment details. The goal is to ensure data integrity, generate fee payment dates, determine the most frequent payment date for each student, and implement both linear and parallel execution versions of the code to perform the tasks efficiently.

# Dataset

Files Used:

larger_students.csv: Contains a list of students with their IDs, names, and major.

larger_fees.csv: Contains fee payment details, including student IDs, amounts, and payment dates.

# Code Functionality:

# Linear Execution:

In the linear execution approach, the program reads both the larger_students.csv and larger_fees.csv files, ensures each student appears in both files, generates a list of payment dates for each student, and determines the most frequent payment date for each student sequentially.

# Parallel Execution (Using multiprocessing):

In the parallel execution approach, the program uses Python's multiprocessing library to parallelize the task of determining the most frequent payment date for each student. This significantly reduces processing time by utilizing multiple CPU cores.
