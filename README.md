🏥 Healthcare Data Cleaning Project

📋 Project Overview

This project demonstrates a complete workflow of data cleaning for a healthcare clinic dataset.
As a data analyst, the task is to identify and fix missing values, duplicate records, and incorrect data types before analysis.

Implemented in Python using pandas and NumPy.

🗂 Dataset

The dataset contains information about patients, including:

Column	Description
patient_id	Unique identifier for each patient 🔑
age	Patient age (some missing or incorrect values) 🎂
weight	Patient weight in kg (some missing or incorrect values) ⚖️
blood_pressure	Blood pressure measurement (some missing values) 💓
medication	Medication prescribed (some missing values) 💊
insurance_provider	Insurance provider (some missing values, categorical) 🏦

Total rows: 20 (includes intentional missing values, duplicates, and wrong types).

🛠 Project Tasks
1️⃣ Inspect the Data

Check dataset shape 📐

Identify missing values ❌

Calculate percentage of missing values 📊

Detect duplicate rows 🔍

Check column data types 🔢

2️⃣ Data Type Conversion

Convert age and weight → numeric type ✨

Convert insurance_provider → categorical type 🗂

Verify data type conversions ✅

3️⃣ Handle Missing Values

Fill missing values:

age, weight, blood_pressure → median 🧮

medication → mode 🎯

insurance_provider → 'Unknown' ❓

Ensure no missing values remain ✅

4️⃣ Handle Duplicates

Identify duplicate rows 🔍

Remove duplicates based on patient_id

Keep only the first occurrence ✅

5️⃣ Verification Report

Print before and after report:

Shape of dataset 📐

Missing values count ❌

Duplicate count 🔁

Data types 🔢

Confirm dataset is clean and ready for analysis 🎯

⚙️ Tools and Libraries

Python 3.x 🐍

pandas → Data manipulation and cleaning 📊

NumPy → Handling numerical operations 🔢

🚀 Project Workflow

Create the original dataset from a dictionary 📝

Inspect dataset for missing values, duplicates, and incorrect types 🔍

Copy dataset to a new DataFrame for cleaning 📂

Convert column types & handle missing values safely 🧹

Remove duplicates based on patient_id ❌🔁

Verify all cleaning steps with a final report 📈

🎯 Expected Outcome

After cleaning:

Shape: 20 → 18 rows (duplicates removed)

All missing values filled ✅

Correct data types for all columns 🔢

Dataset ready for further analysis 🏥

Final Verification Report Example:

Shape: (18, 6)
Missing Values: 0 for all columns
Duplicate patient_id: 0
Data Types: age/weight → float64, insurance_provider → category
🎓 Learning Outcomes

Identify & handle missing values ❌➡️✅

Detect & remove duplicate records 🔍

Convert columns to correct data types 🔢

Create verification report to confirm data cleaning 📝

Prepare a dataset for real-world healthcare analysis 🏥
