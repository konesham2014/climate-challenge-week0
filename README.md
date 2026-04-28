# Climate Challenge Week 0

## Setup
python -m venv venv
venv\Scripts\activate
pip install -r requirements.txt

# African Climate Trend Analysis (COP32)

## Overview
This project analyzes climate data from five African countries (Ethiopia, Kenya, Nigeria, Tanzania, and Sudan) from 2015–2026. The goal is to compare temperature trends, rainfall variability, and extreme weather events to assess climate vulnerability.

## Project Structure
- notebook/: Contains all Jupyter notebooks for analysis
- data/: Cleaned datasets used for analysis
- scripts/: (optional) helper scripts if used

## Workflow

### 1. Data Cleaning
- Removed missing values (-999)
- Converted YEAR and DOY into datetime format
- Extracted monthly features
- Handled duplicates and missing values

### 2. Exploratory Data Analysis
- Temperature and rainfall trends analyzed per country
- Correlation analysis between climate variables
- Distribution and variability studies

### 3. Cross-Country Comparison
- Compared all five countries across key climate indicators
- Analyzed extreme heat and drought frequency
- Performed statistical testing (ANOVA)

### 4. Climate Vulnerability Ranking
Countries were ranked based on:
- Temperature levels
- Rainfall variability
- Extreme heat events
- Dry day frequency

## Key Findings
- Sudan shows highest heat and drought stress
- Nigeria shows high climate variability and extreme exposure
- Ethiopia is moderately vulnerable with notable dry conditions
- Kenya and Tanzania show comparatively lower extreme stress

## Tools Used
- Python (pandas, numpy, matplotlib, seaborn, scipy)
- Jupyter Notebook

## Author Contribution
All analysis, cleaning, visualization, and interpretation were independently developed as part of a climate data analysis project for COP32 preparation.