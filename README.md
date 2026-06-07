# Student Performance Analysis: Gender and Parental Education
**TU Dortmund University - M.Sc. Data Science Application Project**

This repository contains the data processing, statistical hypothesis testing, and data visualization scripts used to analyze a cohort of 486 students. The primary objective of this project is to determine the statistical impact of gender and parental educational attainment on student proficiency in Mathematics and Language.

## 📊 Project Overview
* **Research Question 1:** Is there a statistically significant difference between male and female students in Mathematics and Language scores?
* **Research Question 2:** Does parental level of education significantly impact student performance, and which specific educational tiers differ?

## 🛠️ Tech Stack & Methods
The analysis was conducted entirely in Python, utilizing standard data science libraries for robust inferential statistics and visualizations.
* **Data Wrangling:** `pandas`, `numpy` (Reshaping from long to wide formats, handling European CSV delimiters).
* **Statistical Testing:** `scipy.stats`, `statsmodels` (Shapiro-Wilk, Levene's Test, Welch's t-test, One-Way ANOVA, Tukey's HSD).
* **Visualization:** `matplotlib`, `seaborn` (Standardized boxplots).

## 🚀 Key Findings
1. **Gender:** Welch’s t-tests revealed no statistically significant difference between male and female students in Mathematics. However, female students demonstrated a highly significant statistical advantage in Language scores.
2. **Parental Education:** A One-Way ANOVA and subsequent Tukey HSD post-hoc tests confirmed a strong positive correlation between a parent's educational background and student success. Students whose parents hold advanced degrees (Bachelor's or Master's) consistently outperformed those whose parents hold a high school or associate's degree in both subjects.

## 📂 Repository Structure
* `/data`: Contains the raw `Scores.csv` dataset.
* `/notebooks`: Contains the documented Jupyter Notebook with complete step-by-step code and execution outputs.
* `/images`: High-resolution `.png` exports of the generated statistical graphics.
* `/report`: The final, rigorously formatted 10-page academic report detailing the mathematical definitions, methodology, and evaluated conclusions.

## 👤 Author
**Mohamed Waleed Elmogy**
* Data Analyst | Junior AI Engineer
* [LinkedIn](https://www.linkedin.com/) *(Add your link here)*
* Email: mohammed.elmogy7500@gmail.com
