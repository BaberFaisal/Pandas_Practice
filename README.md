# Pandas Practice

This repository contains a Python script that demonstrates core functionalities of the **Pandas** library using a sample employee dataset. It covers essential data analysis and data manipulation techniques.

## File

- `pandas__pratice.py`: A practice script for exploring Pandas functions and features.

## Dataset Overview

The dataset includes information about employees with the following columns:

- `EmployeeID`
- `Name`
- `Department`
- `Gender`
- `Age`
- `Salary`
- `JoiningDate`
- `City`
- `PerformanceScore`
- `Bonus`

## Topics Covered

### Data Exploration
- Viewing data: `head()`, `tail()`, `info()`, `describe()`
- Accessing rows and columns with `.iloc`, `.loc`, `.at`, `.iat`

### Data Cleaning
- Identifying and handling missing values: `isnull()`, `dropna()`, `fillna()`
- Replacing values
- Renaming columns
- Removing duplicates

### Data Transformation
- Changing data types
- Sorting and indexing
- Creating new columns
- Using `.apply()` with custom functions

### Data Analysis
- Aggregations: `mean()`, `sum()`, `count()`, `agg()`, etc.
- Grouping data with `.groupby()`
- Counting values and unique entries

## How to Run

Make sure you have Python installed along with the Pandas library.

To run the script:

```bash
python pandas__pratice.py
