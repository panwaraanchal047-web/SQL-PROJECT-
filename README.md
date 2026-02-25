Project Overview

This project analyzes hospital infection data using SQL to identify trends, high-risk departments, and patterns in hospital-acquired infections (HAIs).
The objective is to support infection control decisions through data-driven insights.

 Objectives

Analyze infection rates across departments

Identify most common infection types

Detect trends over time

Support better hospital infection control strategies

🛠 Tools Used

SQL (MySQL)

Database Management System

🗄 Database Structure

The dataset includes tables such as:

Patients

Admissions

Departments

Infection Records

Treatment Details

 Key SQL Concepts Used

SELECT, WHERE, GROUP BY, ORDER BY

JOIN (INNER JOIN, LEFT JOIN)

Aggregate Functions (COUNT, AVG, SUM)

Subqueries

Date functions

📊 Sample Queries
1️⃣ Department-wise Infection Count
SELECT department_name, COUNT(infection_id) AS infection_count
FROM infections
GROUP BY department_name
ORDER BY infection_count DESC;
2️⃣ Most Common Infection Type
SELECT infection_type, COUNT(*) AS total_cases
FROM infections
GROUP BY infection_type
ORDER BY total_cases DESC;
📈 Key Insights

Certain departments reported higher infection rates.

Some infection types were more frequent than others.

Trend analysis helps in early detection and prevention.

🚀 How to Use

Import the dataset into your SQL database.

Run the provided queries.

Analyze results for insights.

👩‍💻 Author

Aanchal Panwar
