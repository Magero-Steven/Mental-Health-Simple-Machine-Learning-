# Mental-Health-Simple-Machine-Learning

![image](https://github.com/user-attachments/assets/35d96580-3661-4ce2-a96c-aced9aaf4370)


## Project Overview
This project explores the correlation between various socioeconomic factors and mental health outcomes, specifically depression risk. The goal is to use machine learning techniques to identify how independent variables such as **income, education, marital status, and physical health** influence depression risk.

## Table of Contents
- [Introduction](#introduction)
- [Dataset Description](#dataset-description)
- [Project Structure](#project-structure)
- [Installation](#installation)
- [Methodology](#methodology)
- [Results & Findings](#results--findings)
- [Contributing](#contributing)
- [Data Visualization](#data-visualization)


## Introduction
Mental health issues, particularly depression, are influenced by a variety of social and economic factors. This study utilizes a dataset containing socioeconomic indicators to determine the extent to which education level, marital status, and income contribute to an individual's depression risk.

## Dataset Description
The dataset consists of:
- **Independent Variables (Predictors)**
  - Level of Education
  - Marital Status (Single, Married, Divorced, Widowed)
  - Income Level (Annual Income in USD)
  - Physical Health Score
    
Data [Link](https://drive.google.com/file/d/1K2Bn671SMguz6aPAz0O8Y8-9y_ie_6oR/view?usp=drive_link)

 **Dependent Variable (Target)**
  - Depression Risk (Binary: `0` = No risk, `1` = High risk)

## Project Structure

```
 📂 Mental-Health-Simple-Machine-Learning
  ├── 📁 data/              # Contains raw and processed datasets
  ├── 📁 notebooks/         # Jupyter notebooks for exploratory analysis
  ├── 📁 src/               # Python scripts for processing & modeling
  │   ├── data_cleaning.py
  │   ├── correlation_analysis.py
  │   ├── visualization.py
  │   ├── regression_model.py
  ├── README.md             # Project documentation
  ├── requirements.txt      # Dependencies
  └── LICENSE               # License information


```


## Installation

- Import the neccessary libaraies for Data Manipulation, reading and visualization
  - Pandas
  - Seaborn
  - Matplotlib
  - Numpy
  
  
## Methodology
- Data Cleaning & Preprocessing- Handle missing values and outliers
- Standardize categorical data (one-hot encoding)
- Normalize numerical variables

  ### Exploratory Data Analysis (EDA)- Compute correlation coefficients
  - Generate distribution plots

  ### Regression Modeling- Logistic Regression & Linear Regression
  - Feature importance analysis


## Results & Findings
- High-income individuals showed lower depression risk.
- Lower education levels correlated with higher depression rates.
- Marital status impacted mental health, with divorced individuals having a higher risk.
- Physical health strongly influenced depression risk.

## Data Visualization
The data visualization was employed the use of Dashboard by Tablaue Public [Link]()
## Contributing
Contributions are welcome! Feel free to fork the repository and submit a pull request.


