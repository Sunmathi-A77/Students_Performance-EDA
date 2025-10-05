# 🎓 Students Performance Analysis – EDA Project

## 📌 Project Overview

This project explores and analyzes a Students Performance Dataset (sourced from Kaggle) using Python. The goal is to perform data cleaning, feature engineering, and exploratory data analysis (EDA) to uncover insights about student performance, study habits, attendance, and other academic and socio-economic factors.

## 📂 Dataset Details

Source: Kaggle – Students Performance Dataset ( Link - https://www.kaggle.com/datasets/anassarfraz13/student-success-factors-and-insights )

## Description:

The dataset contains academic, demographic, and socio-economic information for students, including exam scores, hours studied, attendance, parental involvement, and other factors affecting performance.

## Key Features:

Hours_Studied: Number of hours a student studies

Attendance: Percentage of classes attended

Parental_Involvement: Level of parental support

Access_to_Resources: Access to study materials

Extracurricular_Activities: Participation in extracurriculars

Sleep_Hours: Average hours of sleep

Previous_Scores: Scores from previous exams

Motivation_Level: Self-reported motivation

Internet_Access: Internet accessibility

Tutoring_Sessions: Number of tutoring sessions attended

Family_Income: Household income

Teacher_Quality: Quality of teaching

School_Type: Public or Private school

Peer_Influence: Influence of peers

Physical_Activity: Hours spent in physical activity

Learning_Disabilities: Any learning disabilities

Parental_Education_Level: Parents’ education level

Distance_from_Home: Distance to school

Gender: Male / Female

Exam_Score: Score in the current exam

## ⚙️ Steps Performed

## Basic Data Understanding

Explore dataset structure: shape, columns, and data types.

View sample rows with head(), tail(), sample().

Check summary statistics for numeric and categorical data using describe().

Identify unique values and frequency counts.

Detect missing values and duplicate rows.

## 🔹 Data Cleaning

Checked for missing values.

Filled missing values in Teacher_Quality, Parental_Education_Level, and Distance_from_Home.

Ensured all numeric columns were properly formatted.

Verified that there were no NaNs remaining.

## 🔹 Exploratory Data Analysis (EDA)

Detected outliers in numeric columns using the IQR method.

Examined distributions and relationships between features using boxplots, scatter plots, and pie charts.

Analyzed correlations between Hours_Studied, Attendance, and Exam_Score.

Insights:

Most students have moderate attendance and study hours.

Students with higher extracurricular participation tend to have slightly higher exam scores.

Outliers were identified in hours studied and previous scores.

Visualizations:

Boxplot of Hours Studied: Shows distribution and outliers.

<img width="454" height="451" alt="image" src="https://github.com/user-attachments/assets/77c8fb37-23ab-4e42-8e64-78f747b11e5f" />

Pie Chart of Attendance Levels: Highlights top attendance percentages.

<img width="404" height="427" alt="image" src="https://github.com/user-attachments/assets/510e8ba6-2658-46b8-89ac-d1fd63810c78" />

Exam Score vs Extracurricular Activities: Reveals trends in academic performance.

<img width="587" height="445" alt="image" src="https://github.com/user-attachments/assets/957a89f3-d126-4650-b1c2-45bf91be1cf0" />

## 🔹 Linear Algebra

Created Total_Score by combining Previous_Scores and Exam_Score to measure overall performance.

Performed vectorized operations using NumPy for efficiency.

Insights:

Total score highlights top-performing students more effectively than individual scores.

## 🔹 Differential Calculus

Analyzed rate of change in Exam_Score relative to Hours_Studied.

Insights:

Students’ exam scores tend to increase with more study hours, but the rate of improvement varies.

## 🔹 Probability

Analyzed distribution of School_Type and other categorical features.

Insights :

Majority of students are from a specific school type (e.g., Public).

Probability distributions help identify common trends in the dataset.

Visualization :

Bar chart : Probability of Each School Type

<img width="536" height="393" alt="image" src="https://github.com/user-attachments/assets/0bddbcaf-6d19-4288-857a-a86c73b997d2" />

## 🔹 Statistics

Computed average Exam_Score by Gender.

Calculated correlation between Hours_Studied and Exam_Score.

Insights:

Positive correlation (~0.5) between study hours and exam scores.

Male and female students have similar average scores, indicating minimal gender effect on performance.

Visualizations:

Scatter plots show relationships between key features like study hours and exam score.

<img width="540" height="393" alt="image" src="https://github.com/user-attachments/assets/e2a9c336-3a45-4ee6-be8c-054b385199a9" />

## 🔹 Feature Engineering

Encoded categorical features for ML purposes (e.g., Gender → numeric).

Binned Attendance into Low, Medium, High levels.

Insights:

Higher attendance levels are associated with higher exam scores.

Feature engineering improves model readiness and analysis clarity.

## 🔹 SQL Simulation in Pandas

Identified top 5 students by Total_Score.

Sorted students by Exam_Score.

Filtered students with high Exam_Score and Attendance.

Insights:

Students with both high attendance and high previous scores consistently perform the best.

Visualizations:

Bar charts for top students highlight outstanding performance.

<img width="556" height="393" alt="image" src="https://github.com/user-attachments/assets/112206d0-012b-4408-a290-0f8e009b2868" />


## ✅ Results & Findings

Missing values in key columns were filled to ensure clean analysis.

Outliers in Hours_Studied and Exam_Score were identified.

Feature engineering helped create meaningful metrics like Total_Score and Attendance_Level.

Positive correlation exists between study hours and exam performance.

Visualizations revealed trends, top-performing students, and attendance patterns.

## 📌 Tech Stack

Language: Python 🐍

Libraries: Pandas, NumPy, Matplotlib