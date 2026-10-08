# COVID-19 World Vaccination Progress

## Project Overview

This project analyzes how COVID-19 vaccination rolled out across countries using Python.

The project focuses on cleaning the raw vaccination data, exploring vaccination progress over countries and time, creating visualizations, and reporting the key insights obtained from the data.

The analysis is descriptive and exploratory. No prediction or machine-learning models are included.

---

## Problem Statement

Countries began COVID-19 vaccination at different times and at very different speeds.

The raw daily vaccination records contain missing values, different data types, repeated records, and uneven reporting. Because of this, it can be difficult to compare countries fairly and understand which countries led, which lagged, and which vaccines were widely used.

This project aims to clean the data and use Python visualization techniques to make these patterns easier to understand.

---

## Objectives

1. Clean the raw vaccination dataset by handling:
   - Missing values
   - Duplicate records
   - Incorrect data types
   - Outliers

2. Explore vaccination progress:
   - By country
   - Over time
   - By vaccination coverage
   - By vaccine type

3. Create at least 6 meaningful visualizations.

4. Prepare a short insights report explaining the main findings.

5. Maintain the complete project in a GitHub repository with contributions from both team members.

---

## Dataset

**Dataset Name:** COVID-19 World Vaccination Progress

**Source:** Kaggle

**Dataset Link:**  
https://www.kaggle.com/datasets/gpreda/covid-world-vaccination-progress

### Main Dataset Files

- `country_vaccinations.csv`
- `country_vaccinations_by_manufacturer.csv`

The main dataset contains country-level vaccination records with information such as country, date, total vaccinations, people vaccinated, people fully vaccinated, daily vaccinations, population-normalized vaccination measures, vaccines, and source information.

---

## Data Cleaning

The following cleaning steps will be performed:

### Missing Values
Missing values will be identified using Pandas and handled according to the type of variable and analysis.

### Duplicate Records
Duplicate records will be checked and exact duplicates will be removed where appropriate.

### Data Types
The `date` column will be converted from text into a datetime format, and numerical columns will be checked and converted to suitable numeric types.

### Outliers
Outliers will be investigated using descriptive statistics, box plots, and the IQR method.

### Consistency Checks
Country names, dates, and numerical vaccination values will be checked for inconsistent or unsuitable records.

---

## Planned Visualizations

The project will contain at least 6 visualizations.

### 1. Total Vaccination Progress
**Plot type:** Line chart

Shows how total vaccination doses changed over time for the leading countries.

### 2. Fully Vaccinated Coverage
**Plot type:** Bar chart

Compares countries by people fully vaccinated per 100 people.

### 3. Daily Vaccinations
**Plot type:** Line chart

Shows changes in daily vaccination activity for selected countries.

### 4. Vaccine Usage by Country
**Plot type:** Bar chart

Shows how widely different vaccine manufacturers were used across reporting countries.

### 5. Daily Vaccinations per Million
**Plot type:** Box plot

Compares the distribution of daily vaccination rates across different years.

### 6. Correlation Between Vaccination Metrics
**Plot type:** Correlation heatmap

Shows relationships between numerical vaccination variables.

### 7. Vaccination Coverage Distribution
**Plot type:** Histogram

Shows how vaccination coverage varies across countries.

### 8. Vaccination Coverage by Continent
**Plot type:** Line chart

Compares people fully vaccinated per 100 across continents.

---

## Project Methodology

The project will follow these steps:

1. Download the dataset from Kaggle.
2. Load the data using Pandas.
3. Inspect the dataset structure and data types.
4. Check missing values and duplicate records.
5. Convert data types where necessary.
6. Detect and investigate outliers.
7. Clean and preprocess the dataset.
8. Perform exploratory data analysis.
9. Create visualizations using Matplotlib and Seaborn.
10. Interpret the graphs and prepare a short insights report.
11. Upload the notebook, cleaned data, visualizations, and documentation to GitHub.

---

## Project Structure

```text
covid19-vaccination-progress/
│
├── README.md
│
├── data/
│   ├── README.md
│   ├── country_vaccinations.csv
│   └── country_vaccinations_by_manufacturer.csv
│
├── notebooks/
│   └── covid19_vaccination_analysis.ipynb
│
├── visuals/
│   └── project visualization files
│
└── reports/
    └── short insights report
Technologies and Libraries
Python 3
Pandas
NumPy
Matplotlib
Seaborn
Jupyter Notebook
VS Code
Git
GitHub
Expected Outcome

The project is expected to provide a clear exploratory analysis of COVID-19 vaccination progress across countries and over time.

The final result will include:

Cleaned vaccination data
At least 6 visualizations
A short insights report
Python analysis notebook
Complete project documentation
GitHub repository with version-control commits

Status
🚧 Project in Progress
The GitHub repository currently contains the dataset and project structure. The analysis notebook, final visualizations, and insights report will be added as the project progresses.

References
Kaggle — COVID-19 World Vaccination Progress
Python Documentation
Pandas Documentation
NumPy Documentation
Matplotlib Documentation
Seaborn Documentation

Team: ALPHA
Member name: Priya Dave
Enrollment NO : IU2441230629

