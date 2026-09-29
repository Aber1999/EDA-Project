Exploratory Data Analysis (EDA) - Used Cars Dataset
Student Name: Aber Hamoud Abd
Supervised by: Dr. Mustafa Al-Youssef
Course: Big Data Analysis
Environment: Jupyter Notebook
Project Overview
This project presents a complete Exploratory Data Analysis (EDA) on a used cars dataset. The main goal is to clean the dataset, analyze car price distributions, inspect potential outliers, and uncover the main factors driving car prices using visualization and correlation analysis.
Repository & Folder Structure
EDA_Homework.ipynb: Main Jupyter Notebook containing code cells, data cleaning, plots, and markdown explanations.
dataset.csv: Primary raw dataset containing used car listings.
requirements.txt: List of Python libraries required to run the notebook.
README.txt: Project documentation and overview.
Analysis Workflow (Sections A - F)
Section A: Introduction & Objectives — Defining core research questions regarding price factors and mileage impact.
Section B: Data Loading & Inspection — Loading dataset.csv and reviewing shape, column types, and head rows.
Section C: Data Cleaning & Type Conversion — Cleaning string formatting, handling duplicates, and converting AskPrice and kmDriven into numeric types.
Section D: Univariate & Bivariate Visualizations — Plotting price distribution (Histogram), mileage spread (Boxplot), and fuel distribution (Bar Chart).
Section E: Correlation & Relationships — Constructing a Correlation Heatmap and a Scatter Plot to evaluate interactions between variables.
Section F: Conclusions — Summarizing findings and providing answers to initial hypotheses.
Key Summary Findings
Price Distribution: Car prices are right-skewed; most cars lie in the lower to mid-price range, with very few high-priced outliers.
Mileage vs. Price: An inverse relationship exists where higher mileage (kmDriven) strongly reduces selling price (AskPrice).
Vehicle Age: Depreciation significantly affects price as older models drop in market value compared to recent years