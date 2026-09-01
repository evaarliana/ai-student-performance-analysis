# AI Student Performance Insights

## Project Overview

This project analyzes the relationship between Generative AI usage, academic performance, and student well-being.

The original dataset contains **50,000 student records** and 16 variables covering academic performance, AI usage patterns, burnout risk, anxiety levels, skill retention, and institutional factors. The analysis uses **49,994 records** to generate data-driven insights for educational decision-making.

---

## Business Questions

- Is Generative AI usage associated with changes in academic performance?
- How is AI usage duration related to students' academic performance?
- How do institutional policies relate to student well-being?
- Does AI usage differ across academic levels?
- How does AI usage intensity relate to skill retention?

---

## Data & Scope

### Dataset

**AI Student Impact Dataset**

- Original records: **50,000 students**
- Analytical records: **49,994 students**
- Variables: **16**
- Unit of analysis: **Student**

### Key Analytical Dimensions

- Academic Performance
- Weekly AI Usage
- AI User Segment
- Burnout Risk
- Anxiety Level
- Skill Retention
- Institutional Policy
- Academic Level
- Major Category

---

## Methodology

The analysis follows an end-to-end workflow:

**Data Understanding → Data Quality Assessment → Data Cleaning & Validation → Exploratory Data Analysis → Statistical Analysis → Dashboard Development → Business Recommendations**

### 1. Data Understanding

Identified the key variables required to evaluate academic performance, AI usage, student well-being, and institutional factors.

### 2. Data Quality Assessment

Validated data completeness, duplication, data types, categorical values, and numerical ranges before analysis.

### 3. Exploratory & Statistical Analysis

Analyzed:

- Pre vs. Post Semester GPA
- Weekly AI Hours vs. Post Semester GPA
- Burnout Risk by Institutional Policy
- Anxiety Level by Institutional Policy
- Weekly AI Hours by Academic Level
- Skill Retention by AI User Segment

### 4. Dashboard Development

Developed an interactive Power BI dashboard to monitor academic performance, AI usage, burnout risk, anxiety, and skill retention.

---

## Key Insights

### 1. Academic Performance Improved

Average GPA increased from **3.15 to 3.35**, representing a **6.35% increase** after AI adoption. The increase was observed consistently across major categories.

### 2. AI Usage Has Almost No Linear Relationship with GPA

Weekly AI Hours showed an almost negligible relationship with Post Semester GPA, with a **Pearson correlation of -0.02**.

This suggests that the duration of AI usage alone is not a strong indicator of academic performance.

### 3. Institutional Policy Is Associated with Anxiety Levels

Students under a **Strict Ban** policy recorded the highest average Anxiety Level at **4.89**, compared with **4.12** for both Allowed and Encouraged policies.

### 4. AI Usage Is Relatively Consistent Across Academic Levels

Average AI usage remained around **8.4 hours per week** across Freshman to Graduate levels, with only small differences between academic levels.

### 5. Moderate AI Users Show the Highest Skill Retention

**Moderate Users** recorded the highest average Skill Retention Score at **77**, compared with **76** for Light Users and **73** for Heavy Users.

---

## Business Recommendations

- Encourage balanced and responsible AI usage rather than relying on blanket restrictions.
- Improve AI literacy through training on prompt engineering, information evaluation, and ethical AI usage.
- Combine AI-assisted learning with active learning, analysis, discussion, and problem-solving activities.
- Monitor student well-being indicators alongside academic performance when evaluating AI adoption.

---

## Dashboard Preview

![AI Student Impact Dashboard](./dashboard/dashboard.png)

The dashboard provides an interactive view of:

- Academic performance
- Weekly AI usage
- Burnout risk
- Anxiety level
- Skill retention
- Major Category
- Academic Level
- Institutional Policy

---

## Tools

- **Python** — Data Cleaning, Exploratory Data Analysis, and Statistical Analysis
- **Power BI** — Dashboard Development

---
