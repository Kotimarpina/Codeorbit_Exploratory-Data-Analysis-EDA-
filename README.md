# Exploratory Data Analysis (EDA) – Titanic Dataset

## Project Overview

This project focuses on performing Exploratory Data Analysis (EDA) on the Titanic dataset using Python. The analysis explores passenger characteristics, survival patterns, relationships between variables, and potential outliers through statistical techniques and visualizations.

This project was completed as part of the **Data Science Internship at CodeOrbit Tech**.

## Objectives

- Understand the structure and characteristics of the dataset.
- Perform univariate, bivariate, and multivariate analysis.
- Visualize numerical and categorical variables.
- Explore passenger survival patterns.
- Identify relationships between different features.
- Detect potential outliers.
- Summarize meaningful findings from the analysis.

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

## Dataset

The project uses the Titanic passenger dataset.

The cleaned dataset generated during Task 1 is used as the primary input for the EDA process.

**Input file:** `Titanic_Cleaned.csv`

## Exploratory Data Analysis

### 1. Univariate Analysis

Examined individual variables to understand their distributions.

- Passenger age distribution.
- Passenger fare distribution.
- Gender distribution.
- Passenger class distribution.
- Survival distribution.

### 2. Bivariate Analysis

Explored relationships between two variables.

- Gender vs Survival.
- Passenger Class vs Survival.
- Age vs Fare.
- Age vs Survival.

### 3. Multivariate Analysis

Used a correlation heatmap to explore relationships between numerical features.

### 4. Outlier Detection

Used box plots to visually inspect potential outliers in:

- Age.
- Fare.

### 5. Key Findings

The analysis explores:

- Differences in survival percentages across genders.
- Survival patterns across passenger classes.
- Age and fare distributions.
- Relationships between numerical variables.
- Potential unusual observations in the dataset.

## Visualizations

The notebook includes:

- Histograms.
- Bar charts.
- Scatter plots.
- Box plots.
- Correlation heatmap.

## Project Structure

```text
CodeOrbit-Titanic-EDA/
│
├── Dataset/
│   └── Titanic-Dataset.csv
│
├── Cleaned_Data/
│   └── Titanic_Cleaned.csv
│
├── Notebooks/
│   └── Task_2_Codeorbit_EDA.ipynb
│
├── Visualizations/
│
├── Reports/
│   └── CodeOrbit_Task_2_EDA_Report.pdf
│
└── README.md
```

## How to Run

1. Clone this repository.
2. Install the required libraries:

```bash
pip install pandas numpy matplotlib seaborn jupyter
```

3. Open Jupyter Notebook:

```bash
jupyter notebook
```

4. Open the Task 2 EDA notebook.
5. Execute the cells sequentially.

## Results

The analysis provides a visual and statistical understanding of passenger characteristics and survival patterns in the Titanic dataset.

## Internship Details

**Organization:** CodeOrbit Tech  
**Program:** Data Science Internship  
**Task:** Exploratory Data Analysis (EDA)  
**Dataset:** Titanic Dataset

---

*This project demonstrates practical data analysis, visualization, and interpretation skills using Python.*
