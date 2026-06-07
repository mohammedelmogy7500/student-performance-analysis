# Application Report Master Data Science: TU Dortmund University (Winter 2026/2027)

This repository contains the complete data processing, statistical analysis, and visualization scripts conducted for the M.Sc. Data Science Application Report (Winter Semester 2026/2027) at TU Dortmund University. The project investigates whether statistically significant differences exist between male and female students in Mathematics and Language scores, and how parental educational attainment impacts these academic outcomes.

## Project Summary

Using a dataset of student test scores, this project applies descriptive and inferential statistical methods to analyze performance patterns across gender and socioeconomic lines. The analysis is designed to meet rigorous academic standards for statistical reporting and ensures full reproducibility of all mathematical results, tables, and figures presented in the formal application document.

## Dataset

* **Observations:** 486 students
* **Variables:** 5 (`student_id`, `gender`, `parental.level.of.education`, `subject`, `score`)
* **Subject Types:** Mathematics, Language
* **Data Quality:** Zero missing values. Data reshaped from long to wide format for student-level analysis.

## Methods

* **Descriptive Statistics:** Calculation of arithmetic mean, median, and standard deviation.
* **Graphical Analysis:** Standardized box plots comparing score distributions across categorical groups.
* **Assumption Testing:** Shapiro-Wilk test for normality and Levene's test for homogeneity of variances.
* **Hypothesis Testing (Gender):** Independent Two-Sample t-tests (and Welch's t-tests for unequal variances).
* **Hypothesis Testing (Education):** One-Way Analysis of Variance (ANOVA).
* **Post-Hoc Analysis:** Tukey's Honestly Significant Difference (HSD) test.

## Key Results

1. **Gender:** The analysis revealed no statistically significant difference between male and female students in Mathematics scores. However, female students demonstrated a highly significant statistical advantage in Language scores over their male counterparts.
2. **Parental Education:** The analysis confirmed a strong, positive correlation between a parent's educational background and student success. Students whose parents hold advanced degrees (Master's or Bachelor's) consistently and significantly outperformed those whose parents hold a high school or associate's degree in both subjects.

## Source Code

The repository contains all Python scripts and Jupyter Notebooks (`scores-analysis.ipynb`) required to replicate the statistical tests, generate the descriptive tables, and export the exact visualization figures used in the final report.

## Academic Context

This project was completed by **Mohamed Waleed Elmogy** as part of the application process for the M.Sc. Data Science program at TU Dortmund University and is intended for academic evaluation purposes.
