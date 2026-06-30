# Titanic Dataset Analysis

## Overview

This project performs an Exploratory Data Analysis (EDA) on the Titanic dataset to understand the factors that influenced passenger survival during the Titanic disaster.

The analysis includes data cleaning, handling missing values, feature engineering, statistical summaries, data visualization, and insights obtained from passenger demographics, travel information, and family relationships.

---

## Objectives

- Load and explore the Titanic dataset.
- Handle missing values using appropriate techniques.
- Clean and prepare the dataset for analysis.
- Analyze survival patterns using different passenger characteristics.
- Create new features for deeper analysis.
- Visualize important trends using charts and graphs.
- Generate meaningful insights through exploratory data analysis.

---

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

---

## Analysis Performed

### Data Exploration

- Dataset overview
- Dataset shape
- Data types inspection
- Statistical summary
- Missing value analysis

### Data Cleaning

- Filled missing Age values using mean imputation.
- Dropped the Cabin column due to a large number of missing values.
- Checked data consistency.

### Feature Engineering

- Created **FamilySize** using:
  
  `FamilySize = SibSp + Parch + 1`

- Created **IsAlone** feature.
- Created passenger **Age Groups** for better analysis.

### Survival Analysis

- Survival by Gender
- Survival by Passenger Class
- Survival Rate by Age Group
- Survival Rate by Embarkation Port
- Survival Rate by Family Size

---

## Data Visualization

- Gender Survival Bar Chart
- Passenger Class Survival Chart
- Age Distribution Histogram
- Correlation Heatmap
- Survival Rate by Family Size
- Survival by Embarkation Port
- Survival by Age Group

---

## Key Findings

- Female passengers had a significantly higher survival rate than male passengers.
- First-class passengers were more likely to survive than passengers in second and third class.
- Survival rates varied across different age groups.
- Passengers travelling with small to medium-sized families generally showed better survival rates.
- Survival rates differed across embarkation ports.
- Feature engineering helped provide additional insights into passenger survival patterns.

---

## Project Structure

```
Titanic_Dataset_Project/
│
├── Titanic_Dataset.ipynb
├── README.md
└── Titanic-Dataset.csv
```

---

## Sample Insights

- Women and children had higher survival rates.
- Passenger class strongly influenced survival probability.
- Family size affected the chances of survival.
- Embarkation location showed noticeable differences in survival rates.
- Data visualization made survival trends easier to understand.

---

## Learning Outcomes

Through this project, I gained practical experience in:

- Data Cleaning
- Exploratory Data Analysis (EDA)
- Feature Engineering
- Data Visualization
- Statistical Interpretation
- GroupBy Operations
- Correlation Analysis
- Using Python libraries for data analysis

---

## Author

**Sahil Jindal**

B.E. Information Technology  
UIET, Panjab University, Chandigarh

