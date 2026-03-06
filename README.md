# 🚢 Titanic Data Analysis Capstone Project

A complete step-by-step data analysis project exploring the Titanic dataset using Python, NumPy, Pandas, and Matplotlib. This project demonstrates fundamental data science techniques including data cleaning, exploratory data analysis (EDA), and visualization.

## 📋 Project Overview

This capstone project provides a comprehensive analysis of the Titanic dataset, investigating what factors influenced passenger survival during the tragic maritime disaster. Through systematic data exploration and visualization, the project uncovers patterns and insights about survival rates across different passenger demographics and conditions.

## 🎯 Objectives

- Load and explore the Titanic dataset structure
- Perform data cleaning and handle missing values
- Conduct exploratory data analysis (EDA)
- Analyze survival patterns across multiple dimensions
- Create meaningful visualizations using Matplotlib
- Document findings and key insights

## 📊 Analysis Sections

### Step 1-3: Data Loading & Exploration

- Import required libraries (NumPy, Pandas, Matplotlib)
- Load the Titanic CSV dataset
- Examine dataset structure, dimensions, and data types
- Display summary statistics

### Step 4-5: Data Cleaning

- Identify missing values
- Fill missing Age values using median imputation
- Fill missing Embarked values using mode
- Create feature engineering (Has_Cabin indicator)

### Step 6-12: Survival Analysis

The project analyzes survival rates from multiple perspectives:

1. **Overall Survival Distribution** - Understand baseline survival statistics
2. **Survival by Gender** - Compare male vs female survival rates
3. **Survival by Passenger Class** - Analyze impact of ticket class (1st, 2nd, 3rd)
4. **Age Group Analysis** - Categorize passengers into age groups (Child, Teen, Adult, Senior, Elder)
5. **Fare Analysis** - Examine relationship between ticket price and survival
6. **Embarkation Port Analysis** - Compare survival by departure port (C, Q, S)
7. **Cabin Availability Impact** - Analyze effect of cabin information availability

## 🔑 Key Insights

- **Gender Impact**: Females had significantly higher survival rates than males (Women and children first policy)
- **Class Privilege**: First-class passengers enjoyed substantially better survival chances
- **Fare Correlation**: Higher ticket fares correlated with increased survival probability
- **Age Factor**: Children and younger passengers had higher survival rates than adults
- **Cabin Info**: Passengers with cabin information available had slightly improved survival rates
- **Port Variation**: Survival rates varied by embarkation port

## 📁 Project Structure

```
Titanic Project/
├── Titanic_Capstone.ipynb    # Main Jupyter notebook with analysis
├── titanic.csv               # Dataset
└── README.md                 # This file
```

## 🛠️ Technologies & Libraries

- **Python 3.x**
- **Pandas** - Data manipulation and analysis
- **NumPy** - Numerical operations
- **Matplotlib** - Data visualization

## 📊 Dataset Columns

- **PassengerId**: Unique identifier for each passenger
- **Survived**: Binary indicator (0 = Did not survive, 1 = Survived)
- **Pclass**: Passenger class (1st, 2nd, or 3rd)
- **Name**: Passenger name
- **Sex**: Gender (male/female)
- **Age**: Age in years
- **SibSp**: Number of siblings/spouses aboard
- **Parch**: Number of parents/children aboard
- **Ticket**: Ticket number
- **Fare**: Ticket fare in pounds
- **Cabin**: Cabin number
- **Embarked**: Port of embarkation (C, Q, S)

## 📈 Visualizations Included

- Bar charts for survival rates by gender, class, and port
- Histograms for age distribution
- Box plots for fare analysis
- Summary statistics tables

## 🚀 How to Use

1. Ensure you have Python and required libraries installed:

   ```bash
   pip install pandas numpy matplotlib jupyter
   ```

2. Navigate to the project directory:

   ```bash
   cd "Titanic Project"
   ```

3. Launch Jupyter Notebook:

   ```bash
   jupyter notebook
   ```

4. Open `Titanic_Capstone.ipynb` and run cells sequentially from top to bottom

5. Review outputs and visualizations for each analysis section

## 💡 Learning Outcomes

By completing this project, you will understand:

- How to load and explore real-world datasets
- Data cleaning techniques and handling missing values
- Feature engineering basics
- Exploratory data analysis methods
- Creating meaningful visualizations
- Drawing conclusions from data patterns

## 📝 Notes

- The analysis uses median imputation for missing Age values
- The mode is used for filling missing Embarked values
- Age groups are binned into 5 categories for analysis
- All survival rates are expressed as percentages for clarity

## 🔗 Dataset Source

The Titanic dataset is a classic dataset in machine learning and data science, widely used for educational purposes.
**Author**: Data Analysis Capstone Project  
**Date**: 2026  
**Status**: Complete
