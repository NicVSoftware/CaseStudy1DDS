# Case Study 1 – Attrition Analysis (KNN & Naive Bayes Models)
**Course:** MSDS 6306 – Doing Data Science  
**Student:** Nicholas Vandra  
**Date:** October 26, 2025  
**Instructor:** Bivin Sadler  

---

## Overview
This case study explores employee attrition by developing and evaluating classification models (K-Nearest Neighbors and Naïve Bayes).  
The goal was to identify key factors driving turnover and to build predictive models that meet the minimum performance thresholds of **60% sensitivity** and **60% specificity**.

---

## Key Insights
- Employees with **lower job satisfaction**, **higher overtime frequency**, and **longer commute distances** are more likely to leave.  
- The **top three attrition drivers** identified were:
  1. Work-life balance  
  2. Monthly income  
  3. Overtime frequency  

---

## Model Performance Summary

| Model         | Accuracy | Sensitivity | Specificity | ROC AUC |
|----------------|-----------|--------------|--------------|----------|
| **KNN**        | 0.81      | 0.65         | 0.74         | 0.79     |
| **Naïve Bayes**| 0.77      | 0.61         | 0.72         | 0.76     |

**Best Model:** Naïve Bayes – Selected for final predictions and submission.

---

## Presentation
**Google Slides (with embedded videos):**  
[View Presentation](https://docs.google.com/presentation/d/19NQwVb1t9N5s5d9-k88fBEGKKAFPwtQYlrlAjbw29wM/edit?usp=sharing)

---

## Files Included

| File | Description |
|------|--------------|
| `CaseStudy1_Attrition_KNN_NB_Report.Rmd` | Full analysis and R code for both models |
| `CaseStudy1_Attrition_KNN_NB_Report.html` | Rendered HTML report from the R Markdown file |
| `Project_1_Presentation_Slides.pptx` | Backup copy of the Google Slides presentation |
| `Case1PredictionsVandra_Attrition.csv` | Final predictions submitted for competition |
| `README.md` | Repository overview and documentation |

---

## Repository Purpose
This repository serves as the complete submission for **Case Study 1 – Attrition Analysis**, part of the **MSDS 6306 Doing Data Science** course.  
It includes all materials necessary for review: the analysis code, presentation, and prediction results.

---

**© 2025 Nicholas Vandra**
