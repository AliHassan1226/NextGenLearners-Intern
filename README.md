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

# Week 3 - SQL Queries for Internship Analysis
This project analyzes internship applicants data using SQL in Google Colab with SQLite and Python.

# Queries Performed
1. Completed interns per domain
2. Average score per domain
3. Top performers with JOIN
4. Conversion rate with LEFT JOIN
5. Top universities

# Charts Created
1. Completed Interns per Domain
2. Conversion Rate per Domain

# Key Insights
. Total Applicants: 76
. Total Interns: 24
. Completed Interns: 19
. Data Science has the highest conversion rate: 38.9%
. Web Development has the highest completed interns: 9

# Tools Used
. Python
. SQLite
. Pandas
. Matplotlib
. Google Colab

# Week 4 Capstone - Predicting Internship Selection

Objective: Predict internship selection using applicant data and explain results honestly.

Dataset: 120 applicants. 4 features are SIMULATED (not real): num_skills_listed, has_portfolio, prior_hackathon_participation, statement_quality_score.

Method: Cleaning -> Encoding -> Train/Test 80/20 -> Logistic Regression -> Accuracy, Precision, Recall, Confusion Matrix.

Results: Accuracy 38.10%, Precision 38.46%, Recall 50%. Strongest Feature: Graphic Design.

How to Run: Open in Google Colab, Run All. No extra file needed.

Limitation: Small, simulated data. Decision-support tool only, not replacement for human review.

Visuals: 6 Charts - Domain, University, Status Pie, Timeline, Top 10, Dashboard

Tools: Python, Pandas, Matplotlib, Seaborn, Colab, GitHub

Author: Syed Muhammad Ali Hassan - Data Science Intern
