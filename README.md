# 📊 Greenfield Academy — Automated Student Report Card Generator

## Data Analytics Portfolio Project

---

## 📌 Project Overview

I developed an **automated student report card system** for Greenfield Academy using **Microsoft Excel, spreadsheet-based data modeling, lookup functions, and dynamic formulas**.

The project was designed to replace manual report preparation with a **formula-driven reporting system** where entering a student's unique ID automatically retrieves their academic and attendance information and calculates key performance indicators.

The project demonstrates how spreadsheet automation can be used to transform raw educational data into a structured **reporting and decision-support system**.

### Project Details

| Category               | Details                                                     |
| ---------------------- | ----------------------------------------------------------- |
| **Project Type**       | Data Analytics / Spreadsheet Automation                     |
| **Industry**           | Education                                                   |
| **Primary Tool**       | Microsoft Excel                                             |
| **Data Type**          | Student Academic & Attendance Data                          |
| **Focus Areas**        | Data Modeling, Automation, KPI Calculation, Data Validation |
| **Reporting Method**   | Dynamic Formula-Driven Report                               |
| **Future Enhancement** | Power BI Dashboard                                          |

---

# 🎯 1. Business Problem

Manual preparation of student report cards can be time-consuming and vulnerable to errors.

Common challenges include:

* Manual data entry
* Incorrect calculations
* Repetitive administrative work
* Inconsistent reporting
* Difficulty updating student records
* Increased risk of human error
* Limited ability to analyze historical performance

Greenfield Academy needed a more efficient approach that could automatically retrieve student information and calculate key academic and attendance metrics.

### Business Question

> **How can student academic and attendance information be transformed into an automated, reliable, and scalable reporting system?**

---

# 🎯 2. Project Objectives

The primary objective was to build a **dynamic student report card model** that reduces manual reporting and improves the reliability of academic information.

The system was designed to:

* Retrieve student information using a unique **Student ID**
* Automatically display subject scores
* Calculate the overall academic average
* Determine the student's **Pass/Fail status**
* Calculate attendance percentage
* Reduce repetitive manual data entry
* Improve reporting consistency
* Minimize calculation errors
* Create a scalable foundation for future dashboards

---

# 📂 3. Data Description

The dataset contained student-level information covering academic, attendance, and administrative attributes.

### Data Categories

| Category                   | Description                               |
| -------------------------- | ----------------------------------------- |
| **Student Identification** | Unique Student ID and student information |
| **Academic Information**   | Subject scores and academic results       |
| **Grade Information**      | Student class/grade level                 |
| **Attendance**             | Days attended and total school days       |
| **Academic Outcome**       | Calculated performance status             |
| **Administrative Data**    | Supporting student information            |

### Primary Key

The **Student ID** was used as the primary lookup key.

This allowed the report card to dynamically retrieve information for a selected student without manually entering each value.

---

# 🔄 4. Analytical Approach

The project followed a structured data-to-insight workflow:

```text
Raw Student Data
       ↓
Data Modeling
       ↓
Student ID Lookup
       ↓
Retrieve Student Information
       ↓
Retrieve Subject Scores
       ↓
Calculate KPIs
       ↓
Determine Academic Status
       ↓
Generate Automated Report
       ↓
Extract Insights
```

The approach focused on converting raw student records into useful performance indicators.

---

# 📊 5. Key Performance Indicators

The automated report card calculated several important academic and attendance metrics.

| KPI                 |    Result |
| ------------------- | --------: |
| Mathematics         |    **88** |
| English             |    **55** |
| Science             |    **60** |
| Social Studies      |    **52** |
| **Average Score**   |  **63.8** |
| **Attendance Rate** | **97.5%** |
| **Academic Status** |  **PASS** |

---

## 📐 Average Score Calculation

The overall academic average was calculated across four subjects:

```text
Mathematics = 88
English = 55
Science = 60
Social Studies = 52
```

### Formula

```text
(88 + 55 + 60 + 52) ÷ 4 = 63.8
```

Therefore:

**Average Score = 63.8**

---

## 📐 Attendance Calculation

The student's attendance was calculated using the number of days attended compared with the total number of school days.

```text
Days Attended = 117
Total School Days = 120
```

### Formula

```text
117 ÷ 120 × 100 = 97.5%
```

Therefore:

**Attendance Rate = 97.5%**

---

# 💡 6. Key Insights

## 🥇 Strong Mathematics Performance

Mathematics was the student's strongest subject, with a score of **88**.

This performance was significantly higher than the overall academic average of **63.8**.

---

## 📚 Areas for Improvement

The lowest-performing subjects were:

* **Social Studies — 52**
* **English — 55**

These subjects represent the primary areas where additional academic support could be considered.

---

## 🟢 Strong Attendance

The student recorded an attendance rate of **97.5%**.

This indicates very consistent participation in school activities and provides a strong foundation for improving academic performance.

---

## ✅ Overall Academic Performance

The student's overall average was **63.8**, resulting in a **PASS** outcome.

The results indicate satisfactory overall performance, with a particularly strong result in Mathematics and opportunities for improvement in English and Social Studies.

---

# ⚙️ 7. Automation & Technical Implementation

One of the major objectives of the project was to create a **dynamic reporting architecture** rather than a manually populated report card.

The system uses the **Student ID as the input parameter**.

When the Student ID changes, the report automatically updates the associated student information and calculated metrics.

### Automated Data Flow

```text
Student ID
     ↓
Student Information
     ↓
Subject Scores
     ↓
Average Score
     ↓
Academic Status
     ↓
Attendance KPI
     ↓
Automated Report
```

### Technical Concepts Demonstrated

* Lookup functions
* Conditional logic
* Statistical calculations
* Percentage calculations
* Formula-based automation
* Data validation
* Data modeling
* KPI calculation
* Structured spreadsheet design
* Automated reporting

The model was designed to avoid hard-coded calculated outputs wherever possible.

This improves:

* Accuracy
* Maintainability
* Consistency
* Scalability
* Ease of updating

---

# 🧮 8. Data Analytics Skills Demonstrated

This project demonstrates several practical data analytics capabilities.

### Data Modeling

Structured student information so that different attributes could be retrieved and analyzed efficiently.

### Data Retrieval

Used the Student ID as a unique identifier to retrieve the relevant student record.

### KPI Development

Created meaningful performance indicators such as:

* Average Score
* Attendance Rate
* Academic Status
* Subject Performance

### Data Transformation

Converted raw subject and attendance values into meaningful performance metrics.

### Business Analysis

Interpreted the results to identify:

* Strong-performing subjects
* Areas requiring improvement
* Attendance patterns
* Overall academic performance

### Automation

Reduced repetitive manual processes through dynamic spreadsheet formulas.

---

# 💼 9. Business Impact

The automated model provides several operational benefits to the school.

## Efficiency

The system reduces repetitive manual report preparation and allows reports to be generated more quickly.

## Accuracy

Automated calculations reduce the likelihood of arithmetic and manual data-entry errors.

## Consistency

Every student can be evaluated using the same calculation structure and reporting logic.

## Scalability

The model can be expanded to support:

* Multiple students
* Multiple classes
* Multiple academic terms
* Larger datasets
* Historical performance records

## Decision Support

Teachers and administrators can use the resulting information to quickly identify:

* Academic strengths
* Academic weaknesses
* Attendance patterns
* Students requiring additional support

---

# 📈 10. Recommendations

## 1. Expand the Dataset

Move from a single-student reporting template to a centralized student database containing:

* Multiple students
* Multiple classes
* Multiple academic terms
* Historical records

This would allow the system to support broader analysis.

---

## 2. Introduce Historical Analysis

Store previous academic results to enable trend analysis.

Potential analysis could include:

* Student performance trends
* Term-over-term comparisons
* Grade-level performance
* Subject performance trends
* Attendance trends

---

## 3. Develop an Interactive Dashboard

The Excel model could be connected to **Power BI** to create an interactive academic performance dashboard.

Potential dashboard metrics could include:

* Average score by subject
* Pass/fail rate
* Attendance rate
* Class performance
* Top-performing students
* Students requiring academic support
* Subject performance trends
* Term-over-term performance

---

## 4. Strengthen Academic Intervention

Subject-level performance data could be used to identify students who may require additional academic support.

For example:

```text
Low Subject Score
       ↓
Identify Student
       ↓
Analyze Performance
       ↓
Provide Targeted Support
       ↓
Monitor Future Results
```

This would allow the school to move from simply reporting performance to actively using data for academic improvement.

---

# 🚀 11. Future Improvements

The current Excel model provides a foundation for a more advanced analytics solution.

Future improvements could include:

### Power BI Integration

Create interactive dashboards for teachers, administrators, and management.

### Automated Data Refresh

Connect the reporting system to a centralized data source so that reports update automatically when new records are added.

### Historical Performance Tracking

Store previous academic terms to monitor student progress over time.

### Class-Level Analysis

Compare performance across different classes and grade levels.

### Subject-Level Analysis

Identify subjects with consistently high or low performance.

### Early Intervention Analytics

Develop indicators that flag students who may require additional academic support based on performance and attendance patterns.

---

# 🏆 12. Project Outcome

The project successfully demonstrates how **data analytics and spreadsheet automation can transform a manual educational reporting process into a dynamic decision-support system**.

The model connects raw student data to meaningful KPIs and automatically generates a structured report based on the selected Student ID.

The analysis revealed:

* **63.8** overall average score
* **97.5%** attendance rate
* **PASS** academic status
* **88** as the strongest subject score in Mathematics
* **52** as the lowest subject score in Social Studies
* **55** in English, highlighting another area for improvement

More importantly, the project demonstrates the ability to move beyond simply recording data toward **using data to understand performance, identify improvement opportunities, and support better decisions**.

---

# 📋 13. Portfolio Summary

## Greenfield Academy — Automated Student Report Card Generator

| Category               | Summary                                                                                              |
| ---------------------- | ---------------------------------------------------------------------------------------------------- |
| **Business Problem**   | Manual student report generation was repetitive and vulnerable to calculation and data-entry errors. |
| **Solution**           | Built a dynamic spreadsheet reporting model driven by Student ID and automated formulas.             |
| **Tools**              | Microsoft Excel and spreadsheet formulas                                                             |
| **Analysis**           | Calculated subject performance, overall average, academic status, and attendance rate.               |
| **Average Score**      | **63.8**                                                                                             |
| **Attendance Rate**    | **97.5%**                                                                                            |
| **Academic Status**    | **PASS**                                                                                             |
| **Strongest Subject**  | Mathematics — **88**                                                                                 |
| **Improvement Areas**  | English — **55** and Social Studies — **52**                                                         |
| **Business Impact**    | Improved reporting efficiency, accuracy, consistency, and decision support.                          |
| **Future Enhancement** | Power BI dashboard and historical performance analytics                                              |

---

# 🛠️ 14. Tools & Skills

### Tools

* Microsoft Excel
* Spreadsheet formulas
* Power BI *(future enhancement)*

### Technical Skills

* Data Modeling
* Data Validation
* Lookup Functions
* Conditional Logic
* KPI Calculation
* Percentage Analysis
* Spreadsheet Automation
* Data Transformation
* Performance Analysis
* Data Visualization

### Business Skills

* Business Problem Solving
* Insight Generation
* Decision Support
* Process Improvement
* Reporting Automation
* Performance Monitoring

---

# 🔑 15. Key Takeaway

> **This project demonstrates how a data analyst can transform a manual reporting process into an automated, data-driven solution that improves efficiency, accuracy, consistency, and decision-making.**

The project is not simply an Excel report card. It demonstrates the complete analytics workflow:

```text
Business Problem
       ↓
Data
       ↓
Data Modeling
       ↓
Analysis
       ↓
Automation
       ↓
KPIs
       ↓
Insights
       ↓
Business Impact
       ↓
Future Dashboard
```

---

# 📌 Project Classification

**Portfolio Category:** Data Analytics
**Industry:** Education
**Project Type:** Spreadsheet Automation / Reporting
**Primary Tool:** Microsoft Excel
**Future Tool:** Power BI
**Level:** Beginner–Intermediate Data Analytics Project

---

## 👤 About the Project

This project was developed as part of my **Data Analytics portfolio** to demonstrate practical experience in spreadsheet automation, data modeling, KPI development, performance analysis, and business-oriented reporting.

The project showcases my ability to take a real-world operational problem, structure the underlying data, automate repetitive processes, calculate meaningful metrics, identify insights, and recommend improvements that can support better decision-making.
