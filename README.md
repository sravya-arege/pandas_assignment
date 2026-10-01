# Pandas for AI/ML – Conceptual & Technical Assessment

## 📌 Overview

This repository contains my **Pandas for AI/ML – Conceptual & Technical Assessment** completed as part of the **Calibo AI Academy** training program.

The assignment focuses on understanding and applying Pandas and NumPy concepts for data manipulation, analysis, cleaning, and handling real-world data issues.

## 🎯 Objectives

The assignment covers:

- Pandas and NumPy fundamentals
- Output prediction of Pandas code
- Data filtering and descriptive statistics
- Group-wise data analysis
- Correlation analysis
- Code correction and debugging
- NumPy broadcasting
- CSV parsing and data cleaning
- Missing-value handling
- Duplicate detection and removal
- Outlier and invalid-value detection
- Real-world data-cleaning scenarios

## 📂 Assignment Sections

### Section A – Output Prediction

Topics covered:

- NumPy array operations and vectorization
- Pandas Series operations
- Boolean filtering
- Descriptive statistics
- Group-wise analysis using `groupby()`
- Positive correlation
- Negative correlation

### Section B – Code Correction

Topics covered:

- Reading CSV files correctly
- Header handling
- Sorting DataFrames
- Finding highest values
- Handling missing values with `fillna()`
- Calculating correlation correctly

### Section C – Edge Cases

Topics covered:

- NumPy broadcasting
- CSV parsing with quoted values
- Different date formats
- Missing and special values
- Extreme values and their effect on mean and median
- Identifying invalid records

### Section D – Scenario-Based Problems

A real-world student assessment dataset was cleaned using Pandas.

The cleaning process included:

1. Loading and inspecting the dataset
2. Standardizing department names
3. Identifying and removing duplicate records
4. Converting marks into numeric values
5. Handling `Absent`, `NA`, and blank values
6. Identifying invalid marks outside the `0–100` range
7. Displaying the cleaned dataset
8. Reporting the cleaning results

## 🛠️ Technologies Used

- **Python**
- **Pandas**
- **NumPy**
- **Jupyter Notebook**

## 📊 Key Pandas Operations Used

```text
read_csv()
head()
info()
isnull()
sum()
groupby()
mean()
median()
max()
corr()
sort_values()
fillna()
drop_duplicates()
duplicated()
to_numeric()
isna()
loc[]
