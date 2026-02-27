# COSC 2P08 Data Challenge
#  Gym Member Attendance Analysis

##  Project Overview
This project analyzes gym attendance data from `team05_gym.csv` to uncover usage patterns, demographic insights, and workout performance trends.

The analysis answers six key analytical questions using Python (Pandas, Matplotlib, Seaborn).

---

##  Dataset Description

The dataset includes:
- VisitID
- MemberID
- Date
- TimeOfDay
- WorkoutDuration (minutes)
- MembershipType
- AgeGroup
- WorkoutType
- CaloriesBurned
- DayOfWeek

---

##  Data Cleaning Process

The following preprocessing steps were performed:

- Missing value detection and filling in missing values with the mean
- Data consistency with date formatting (mm/dd/yyyy to yyyy-mm-dd)
- Age grouping for demographic analysis
- Logically ordered categories for applicable columns

---

##  Questions Answered

1. Which time of day has the highest average workout duration?
2. How does membership type affect gym usage frequency?
3. What is the average calories burned by workout type?
4. Which age group visits the gym most frequently?
5. Is there a correlation between workout duration and calories burned?
6. How does gym usage vary by day of the week?

---

##  Key Findings

- Identified peak workout time by duration is morning.
- Determined most frequently visited membership type is Basic.
- Found highest calorie-burning workout is weights.
- Identified most active age demographic is 26-35.
- Established correlation between workout duration and calories burned is very weak (r=-0.0286).
- Determined most active day of the week is Thursday.

---

##  Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn

---

## ▶ How to Run
- Open data_challenge.ipynb on git repository
- Open in Colab
