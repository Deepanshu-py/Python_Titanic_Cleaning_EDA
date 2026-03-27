# Titanic Survival Data Analysis

## Project Overview
This project performs Exploratory Data Analysis (EDA) on the Titanic dataset to understand the factors that influenced passenger survival. The analysis focuses on identifying patterns using statistical methods and visualizations.

---

## Problem Statement
The Titanic dataset contains multiple features such as age, gender, passenger class, fare, and family size. The objective is to analyze these variables and determine which factors significantly affected survival.

---

## Objectives
- Understand the dataset structure  
- Perform data cleaning and preprocessing  
- Handle missing values  
- Conduct exploratory data analysis (EDA)  
- Visualize data patterns  
- Identify key factors affecting survival  

---

## Dataset Description
The dataset includes the following features:

- PassengerId: Unique identifier  
- Survived: Survival status (0 = No, 1 = Yes)  
- Pclass: Passenger class (1, 2, 3)  
- Name: Passenger name  
- Sex: Gender  
- Age: Age of passenger  
- SibSp: Number of siblings/spouses aboard  
- Parch: Number of parents/children aboard  
- Ticket: Ticket number  
- Fare: Ticket price  
- Cabin: Cabin number  
- Embarked: Port of embarkation (C, Q, S)  

---

## Tools and Technologies
- Python  
- Pandas  
- NumPy  
- Matplotlib  
- Seaborn  
- Jupyter Notebook  

---

## Data Preprocessing
- Missing values in **Age** were filled using median  
- Missing values in **Embarked** were filled using mode  
- Missing values in **Cabin** were replaced with 'Unknown'  
- Data types were checked and corrected  

---

## Exploratory Data Analysis

### 1. Missing Values
- Heatmap used to identify missing values  
- Age and Cabin had significant missing data  

### 2. Fare Distribution
- Highly positively skewed  
- Most passengers paid low fares  

### 3. Age Distribution
- Majority of passengers were between 20–40 years  

### 4. Outliers Detection
- Boxplot used to detect age outliers  
- Presence of very young and elderly passengers  

### 5. Gender Distribution
- Male passengers were more than female passengers  

### 6. Survival Distribution
- More passengers died than survived  

### 7. Survival by Gender
- Females had significantly higher survival rates  

### 8. Survival by Age Group
- Children and young adults had better survival chances  

### 9. Survival by Family Size
- Small families (2–4 members) had higher survival rates  

### 10. Survival by Passenger Class
- First-class passengers had the highest survival rate  
- Third-class passengers had the lowest survival rate  

### 11. Survival by Fare
- Higher fare passengers had higher survival probability  

### 12. Correlation Analysis
- Survival positively correlated with fare  
- Survival negatively correlated with passenger class  

---

## Key Insights
- Gender was the most influential factor in survival  
- First-class passengers had better survival chances  
- Younger passengers had higher survival rates  
- Fare and passenger class were strongly related  
- Moderate family size increased survival probability  

---

## Conclusion
This project demonstrates how data analysis techniques can be applied to real-world datasets. The analysis shows that gender, passenger class, age, and family size significantly influenced survival during the Titanic disaster.

---

## Future Scope
- Apply machine learning models (Logistic Regression, Decision Trees)  
- Build a predictive model for survival  
- Develop an interactive dashboard using Tableau or Power BI  

---


---

## How to Run the Project
1. Clone the repository  
2. Install required libraries  
   ```bash
   pip install pandas numpy matplotlib seaborn

## Project Structure
Titanic-EDA/
│── Dataset

│── Titanic (1).ipynb

│── Titanic_Project_Report.pdf

│── README.md

## Author

Deepanshu
