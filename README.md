# QuickSeat
# Automated Exam Seating Arrangement System

## Description
Automates student seating for exams ensuring department-wise separation and generates detailed PDF seating charts.

## Technologies
Python, Flask, Pandas, FPDF, Excel

## Features
- Upload Excel with student details (roll numbers, departments)
- Assigns seats avoiding adjacent students from the same department
- Generates professional PDF seating charts
- Web interface for uploading files and downloading results

## Setup
1. Install Python 3.x
2. Install dependencies: `pip install -r requirements.txt`
3. Run: `python app.py`
4. Open the browser at http://127.0.0.1:5000 and upload sample Excel files

## Sample Data
- `students.xlsx` – Example student list for testing
