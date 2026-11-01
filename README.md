# NextGenLearners-Intern

Task Overview

This repository contains Week 1 task of NextGen Learners Data Science Internship. The goal was to clean a messy dataset applicants.csv.

# Dataset

. Original File: applicants.csv (with missing values, duplicates, inconsistent formats)
. Cleaned File: applicants_cleaned.csv (final analysis-ready data)

# Data Cleaning Steps Performed
1. Checked Data: Used df.info(), df.isnull().sum(), df.duplicated()

2. Handled Missing Values: Filled/Removed null values in important columns

3. Removed Duplicates: Used df.drop_duplicates()

4. Standardized Text: Fixed 'Web Dev' to 'Web Development', 'ML' to 'Machine Learning' etc.

5. Fixed Data Types: Converted application_date to datetime format

6.Trimmed Spaces: Removed extra spaces from text columns

# Tools & Libraries
. Python

.Pandas

.Google Colab / Jupyter Notebook

# How to Run

. Open Google Colab

. Upload applicants.csv

. Run cleaning script

# Output

Cleaned dataset is saved as applicants_cleaned.csv and uploaded in this repo.

# Week 2 EDA Intern Applicants

DA on 76 internship applications for NextGen Learners Internship.

Dataset:applicants_cleaned.csv

Key Insights:

. Web Development: 36 apps (47%) - Most Popular
. Graphic Designing: 6 apps - Least
. Karachi University: 23 apps (30%) - Top
. Acceptance Rate: 31.5% (23/73)

Visuals: 6 Charts - Domain, University, Status Pie, Timeline, Top 10, Dashboard

Tools: Python, Pandas, Matplotlib, Seaborn, Colab, GitHub

Author: Syed Muhammad Ali Hassan - Data Science Intern
