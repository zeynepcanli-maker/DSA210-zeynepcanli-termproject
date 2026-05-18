# DSA210 Data Science Project

This repository contains my term project for the course  
DSA 210 Introduction to Data Science.
Student: Zeynep Canlı

#DSA210 - Movie Success Analysis
Milestone 1 Submission
I have enhanced the Exploratory Data Analysis (EDA) process by incorporating statistical hypothesis tests (Chi-Square & Kruskal-Wallis) and advanced visualizations to provide a mathematically rigorous analysis of the relationship between movie budgets and audience satisfaction for Milestone 1."
# DSA 210 Data Science Project: Predicting Movie Success# DSA 210: Predicting Movie Success - Final Project

**Student:** Zeynep Canlı  
**Course:** DSA 210 - Introduction to Data Science (Spring 2026)  
**Instructor:** Sabancı University  

## Project Overview
This project explores the relationship between a movie's financial power (budget and revenue) and audience appreciation (happiness score). Using combined datasets from TMDB and Rotten Tomatoes, we perform Exploratory Data Analysis (EDA), non-parametric hypothesis testing (Kruskal-Wallis), unsupervised learning (K-Means Clustering), and supervised regression models (Random Forest).

## Key Files in this Repository
* `DSA210_Final_Project.ipynb`: The complete Python pipeline, data cleaning, visualizations, and model configurations executed in Google Colab.
* `DSA210_Final_Project_Report.pdf`: The final formal academic report detailing our methodology, findings, and the resolution of the predictive paradox.

## Main Finding (The Predictive Paradox)
While macro financial groups display statistically distinct shapes under the Kruskal-Wallis test ($p < 0.05$), financial metrics completely fail to predict an individual movie's exact happiness score ($R^2 < 0$). This underfitting perfectly demonstrates **Omitted Variable Bias**, proving that while massive budgets can buy production scale, they cannot buy raw human emotional resonance.


