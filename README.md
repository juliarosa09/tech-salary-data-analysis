# Tech Salary Data Analysis

## Overview

This project explores global technology salary data with the objective of identifying compensation patterns across seniority levels, contract types, work models (remote vs on-site), and geographic regions.

The analysis focuses on data cleaning, type correction, and exploratory data analysis (EDA) using Python-based tools.

---

## Dataset

The dataset contains information about technology professionals, including:

- Year  
- Seniority level  
- Contract type  
- Job title  
- Salary (local currency and USD)  
- Country of residence  
- Remote or on-site status  
- Company size  

Initial inspection revealed missing values and type inconsistencies that required preprocessing.

---

## Data Cleaning

The following steps were performed:

- Removal of rows with missing values (representing a negligible percentage of the dataset)  
- Conversion of the `year` column from float to nullable integer (`Int64`)  
- Verification of data consistency and column types  
- Inspection of salary distribution and categorical variables  

Special attention was given to how Pandas handles numeric columns containing missing values, as these are automatically converted to float due to `NaN` representation.

---

## Exploratory Data Analysis

The analysis investigated:

- Salary distribution across seniority levels  
- Differences between remote and on-site roles  
- Country-based salary comparisons  
- Frequency distribution of job titles  
- Company size trends  

Visualizations were created to identify patterns and potential anomalies in compensation data.

---

## Key Findings

- Senior-level positions concentrate the highest salary ranges.  
- USD is the dominant reporting currency in the dataset.  
- Remote positions represent a significant portion of the roles analyzed.  
- Salary distribution varies substantially across countries and experience levels.

---

## Technologies Used

- Python  
- Pandas  
- Matplotlib  
- Seaborn  
- Google Colab  

---

## Future Improvements

- Apply statistical hypothesis testing to validate observed patterns  
- Develop a regression model to predict salary based on experience and location  
- Create interactive visualizations  
- Refactor the notebook into modular Python scripts  
