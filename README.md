
Delhi Online Learning Platform – Student Feedback Analysis

Overview

This project analyzes student feedback data collected from an online learning platform based in Delhi. The goal is to explore learner experiences, identify satisfaction trends, and provide data-driven insights for improving the platform’s offerings.

The analysis is performed using Python with pandas for data handling.

Features
Import student feedback dataset from Excel.
Perform basic exploratory data analysis (EDA).
Identify missing values and inconsistencies.
Summarize learner satisfaction levels.
Generate insights to improve the online learning experience.

Workflow

Setup Environment
Install required libraries:
pip install pandas openpyxl


Load Dataset
The feedback data is provided in an Excel file:
import pandas as pd
df = pd.read_excel("delhi_ai_course_student_feedback_1000.xlsx")
print(df.head())


Data Cleaning
Handle missing values.
Standardize column formats.
Remove duplicates if present.
Exploratory Data Analysis
Calculate summary statistics.
Explore distributions of satisfaction ratings.
Identify trends in learner responses.
Insights & Results
Highlight strengths of the platform.
Suggest improvements based on student feedback patterns.

Requirements
Python 3.8 or higher
pandas
openpyxl
Install all dependencies:
pip install -r requirements.txt

Usage
Open the Jupyter Notebook and run the workflow:
jupyter notebook Delhi_Online_Learning_Platform.ipynb

License
This project is released under the MIT License.
