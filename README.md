# AI Student Performance Insights

## Project Overview

This project analyzes the relationship between Generative AI usage, academic performance, and student well-being.

Using the AI Student Impact Dataset, the analysis explores academic performance, AI usage patterns, burnout risk, anxiety levels, and skill retention to generate data-driven insights for educational decision-making.

The original dataset contains **50,000 student records**, with **49,994 records** retained for the final analysis after data cleaning and validation.

**Project Duration:** June 2026 - June 2026

---

## Business Problem

How does Generative AI usage relate to students' academic performance and well-being, and what insights can support responsible AI adoption in education?

---

## Objectives

- Analyze the relationship between Generative AI usage and academic performance.
- Identify patterns between AI usage and burnout, anxiety, and skill retention.
- Compare AI usage across academic levels and institutional policies.
- Generate data-driven recommendations to support educational decision-making.

---

## Methodology

The analysis follows an end-to-end workflow:

**Data Understanding → Data Quality Assessment → Data Cleaning → Exploratory Data Analysis → Statistical Analysis → Dashboard Development → Business Recommendations**

### Data Preparation

- Validated data types, missing values, duplicates, and invalid values.
- Cleaned inconsistent and invalid records.
- Reduced the dataset from 50,000 to 49,994 records for analysis.

### Exploratory & Statistical Analysis

Analyzed:

- Pre vs. Post Semester GPA
- Weekly AI Hours vs. Post Semester GPA
- Burnout Risk by Institutional Policy
- Anxiety Level by Institutional Policy
- Weekly AI Usage by Academic Level
- Skill Retention by AI User Segment

---

## Key Findings

### 1. Academic Performance Improved

Average GPA increased from **3.15 to 3.35**, representing a **6.35% increase**. The improvement was observed consistently across major categories.

### 2. AI Usage Duration Has Almost No Linear Relationship with GPA

Weekly AI Hours showed an almost negligible linear relationship with Post Semester GPA, with a **Pearson correlation of -0.02**.

### 3. Institutional Policy Is Associated with Anxiety Levels

Students under a **Strict Ban** policy recorded the highest average Anxiety Level at **4.89**, compared with **4.12** for both Allowed and Encouraged policies.

### 4. AI Usage Is Consistent Across Academic Levels

Average AI usage remained relatively consistent across academic levels, ranging between **8.38–8.46 hours per week**.

### 5. Moderate AI Users Show the Highest Skill Retention

**Moderate Users** recorded the highest average Skill Retention Score at **77**, followed by Light Users at **76** and Heavy Users at **73**.

---

## Business Recommendations

- Implement balanced and responsible AI usage guidelines rather than fully restricting AI use.
- Improve AI literacy through training on prompt engineering, information evaluation, and AI ethics.
- Combine AI-assisted learning with analysis, discussion, and problem-solving activities.
- Monitor student well-being indicators such as burnout and anxiety.
- Use the dashboard to continuously monitor academic performance, AI usage, and student well-being.

---

## Dashboard

The Power BI dashboard provides an overview of:

- Academic Performance
- Weekly AI Usage
- Burnout Risk
- Anxiety Level
- Skill Retention
- Major Category
- Academic Level
- Institutional Policy

![AI Student Impact Dashboard](./dashboard/AI%20Student%20Impact%20Dashboard.jpg)

---

## Tools

- Python — Data Cleaning, EDA & Statistical Analysis
- Power BI — Dashboard Development

---

## Project Files

| File | Description |
|---|---|
| `analysis/` | Python analysis and data preparation |
| `dashboard/` | Power BI dashboard and preview |
| `presentation/` | Project presentation and analysis documentation |

---

## Disclaimer

This project was developed for educational and portfolio purposes using the AI Student Impact Dataset.

The findings represent analytical observations from the available dataset and should not be interpreted as causal evidence that Generative AI directly causes changes in academic performance or student well-being.
