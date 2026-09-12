# Greenfield Academy — Automated Student Report Card Generator

## Data Analytics Portfolio Project

### Project Overview

I developed an **automated student report card system** for Greenfield Academy using Excel-based data modeling, lookup functions, and dynamic formulas.

The project was designed to replace manual report preparation with a **formula-driven reporting system** where entering a student's ID automatically retrieves their academic, attendance, and administrative information.

**Project Type:** Data Analytics / Spreadsheet Automation  
**Tools:** Microsoft Excel / Spreadsheet Formulas  
**Focus Areas:** Data Modeling, Lookup Functions, KPI Calculation, Automation, Data Validation

---

## 1. Business Problem

Manual preparation of student report cards can be time-consuming and prone to:

- Data entry errors
- Incorrect calculations
- Repetitive administrative work
- Inconsistent reporting
- Difficulty updating records when student information changes

Greenfield Academy needed a more efficient approach to retrieve student information and calculate key academic performance indicators automatically.

### Business Question

> **How can student academic and attendance information be transformed into an automated, reliable, and scalable reporting system?**

---

## 2. Project Objective

The objective was to build a dynamic report card model that:

- Retrieves student information using a unique **Student ID**
- Automatically displays subject scores
- Calculates the overall academic average
- Determines **Pass/Fail status**
- Calculates attendance percentage
- Reduces manual data entry
- Maintains consistency through formula-driven calculations

---

## 3. Data & Analytical Approach

The dataset contained student-level information covering:

- Student identification
- Grade level
- Subject scores
- Attendance
- Academic outcomes
- Administrative information

The report card was structured around **Student ID as the primary lookup key**.

### Key Performance Indicators

| KPI | Result |
|---|---:|
| Mathematics | 88 |
| English | 55 |
| Science | 60 |
| Social Studies | 52 |
| **Average Score** | **63.8** |
| **Attendance Rate** | **97.5%** |
| **Academic Status** | **PASS** |

### Average Score Calculation

The overall academic average was calculated across four subjects:

```text
(88 + 55 + 60 + 52) ÷ 4 = 63.8
