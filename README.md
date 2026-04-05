# Student Performance Analysis

A simple Python project that generates a synthetic student dataset and performs basic data analysis and visualization to study academic performance.

## Project Overview

This project creates a dataset of 250 students using `Faker` and random values for marks, attendance, department, gender, and year.  
After generating the data, it performs preprocessing, calculates total marks, average marks, and grades, and then visualizes the results using charts.

## Features

- Generates synthetic student data
- Removes duplicate values
- Calculates:
  - Total marks
  - Average marks
  - Grade based on average
- Finds top-performing students
- Identifies failed students
- Performs group analysis by:
  - Department
  - Gender
  - Year
- Visualizes results using:
  - Bar chart
  - Histogram
  - Scatter plots
- Exports the final dataset to a CSV file

## Technologies Used

- Python
- Pandas
- NumPy
- Faker
- Matplotlib
- Seaborn

## Dataset Details

The dataset contains the following columns:

- `Student_ID`
- `Name`
- `Gender`
- `Department`
- `Year`
- `Maths`
- `Science`
- `English`
- `Attendance`
- `Internal_Marks`
- `Total`
- `Average`
- `Grade`

## How It Works

1. Generates fake student names using `Faker`
2. Randomly assigns gender, department, year, marks, and attendance
3. Creates a DataFrame using Pandas
4. Cleans the data by checking missing values and removing duplicates
5. Calculates total marks, average marks, and grades
6. Displays top students and failed students
7. Groups the data for department-wise, gender-wise, and year-wise comparison
8. Visualizes the patterns using Seaborn charts
9. Saves the final dataset as a CSV file

## Installation

Clone the repository:

```bash
git clone https://github.com/vickyjuxtin/Database_Students.git
cd Database_Students
