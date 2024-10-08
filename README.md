# Stanford Open Policing Project

## Overview

The **Stanford Open Policing Project** aims to understand police practices by analyzing public data on traffic stops. The project includes a dataset containing millions of traffic stop records from across the United States. By analyzing this dataset, we aim to uncover trends related to racial disparities, reasons for stops, and outcomes such as arrests or citations. 

This analysis is part of a Kaggle competition aimed at fostering new insights into policing practices using data science techniques.

## Dataset

### Data Description

The dataset includes information about traffic stops in different states, with key fields like:
- **Date and Time** of the stop
- **Location**: State, City, and County of the stop
- **Driver Information**: Gender, Race, Age
- **Stop Information**: Reason for the stop, Violation type, Search conducted, Arrests made
- **Outcome**: Citation, Arrest, Warning
- **Police Information**: Officer's actions and search outcomes


### Data Sources

The dataset is sourced from public records made available by state governments and police departments across the U.S. Each state's records may have slightly different formats, making it essential to perform data cleaning and standardization before analysis.

## Objectives

The main goals of the project are:
- **Identify Racial Disparities**: Examine whether certain racial or ethnic groups are disproportionately stopped or searched by police.
- **Analyze Stop Outcomes**: Investigate what factors lead to different outcomes such as arrests, citations, or warnings.
- **Understand Patterns in Search Conducted**: Explore trends related to vehicle searches, including the reasons and success rates of these searches.
- **Compare States**: Investigate differences in policing practices across states or cities.

## Steps for Analysis

### 1. Data Preprocessing
- **Data Cleaning**: Handle missing values, outliers, and inconsistent formatting across states.
- **Standardization**: Ensure consistent formats for categorical fields like `Race`, `Outcome`, `Search Type`, etc.
- **Feature Engineering**: Create new features that can provide deeper insights, such as calculating `Search Success Rate` or `Stop Duration`.

### 2. Exploratory Data Analysis (EDA)
- **Distribution of Stops**: Analyze the distribution of stops over time, by state, and by demographic features (race, gender, age).
- **Violation Types**: Explore the most common reasons for stops and the outcome for each violation type.
- **Racial Disparities**: Compare stop outcomes and search rates between different racial groups.
- **Geospatial Analysis**: Use maps to visualize traffic stops and searches by location.

### 3. Hypothesis Testing
- **Chi-Square Tests**: To examine relationships between categorical variables like `Race` and `Search Conducted`.
- **Logistic Regression**: Model the probability of a particular outcome (e.g., `Arrest`) based on various features (e.g., `Race`, `Violation Type`, `Gender`).
  

### 4. Visualization
- **Bar Charts**: Display the distribution of stops by race, gender, state, and outcome.
- **Scatter Plots**: Visualize correlations between features like `Age` and `Stop Outcome`.
- **Heatmaps**: Show the concentration of traffic stops across different locations or states.

## Tools & Libraries

- **Python**: Used for data manipulation, analysis, and modeling.
- **Pandas**: For data cleaning and preprocessing.
- **Matplotlib & Seaborn**: For visualizations.
- **Plotly**: For interactive geospatial maps and other dynamic charts.
- **Scikit-learn**: For machine learning models and evaluation.
- **Statsmodels**: For hypothesis testing and statistical analysis.

