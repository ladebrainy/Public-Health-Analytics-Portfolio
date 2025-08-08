# 📊 R Case Study – Habit Tracking & Statistical Modeling (QMM7301)

## 🔍 Project Overview

This project presents an in-depth statistical analysis of a personalized dataset collected over **193 days**, spanning two academic terms — **Fall 2024** and **Winter 2025**. It was developed as part of **Case Study 2** for QMM7301 – Advanced Statistics for Analytics at Cambrian College.

The analysis aims to uncover trends in academic and lifestyle habits, test differences between student streams, and forecast study behavior using real-time, self-reported data. The project integrates a variety of statistical tools and models in **R**, building from raw CSV data to insight-driven interpretation.

## 🎯 Objective

To use personalized and class-wide datasets to answer three central research questions:

1. **Are there differences in average study times across analytics streams?**
2. **Is the distribution of days studied more than 3.13 hours (McGill student average) the same across streams?**
3. **How does personal study time evolve over time?**

## 🧠 Variables Collected

| Variable | Type |
|----------|------|
| `Date` | Identifier |
| `Attend Class` | Categorical |
| `Hours Studying` | Quantitative |
| `Exercise` | Categorical (Nominal) |
| `Social Media` | Categorical (Ordinal) |
| `Leaving the House (hrs)` | Quantitative (Continuous) |
| `Dish Cooked` | Quantitative (Discrete) |
| `Term (F24 or W25)` | Categorical |

## 🛠️ Tools & Techniques

- **R + RMarkdown** – for analysis and reproducible reporting
- **ANOVA + Tukey's HSD** – for testing study time differences
- **Chi-square tests** – for categorical behavior comparison
- **Time series decomposition & forecasting** – for personal habit tracking
- **Data wrangling & visualization** – using `dplyr`, `ggplot2`, and `forecast`

## 🧪 Methods Summary

- Calculated summary statistics across personalized and class-wide datasets
- Performed ANOVA to test mean differences across student streams
- Validated assumptions and applied Tukey’s post-hoc test
- Categorized study time and tested distribution differences using chi-square
- Created time series subsets, applied smoothing models, and generated forecasts

## 📂 Files

- `QMM7301AJAYIAISHATRMD_CASE2.Rmd` – Full report and code in RMarkdown
- `Personalisied.data.set.csv` – Personal data (Fall & Winter terms)
- `Combined (1).csv` – Class-wide data from past and current students

## 📌 Project Highlights

- Used **real-world personal data** to investigate behavior over time
- Cleaned and visualized data using reproducible code
- Applied **advanced statistical techniques** and interpreted results in context
- Modeled and forecasted study habits using exponential smoothing and MA models

---

🟡 **Note**: This assignment-based project shows how personalized tracking and structured statistical analysis can lead to actionable insights and trend interpretation. It demonstrates strong command of R, academic research methods, and transparent communication using reproducible tools.

---
*Prepared by Aishat Ajayi | Health Analytics Student | Cambrian College*
