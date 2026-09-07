# PRODIGY_DS_02

## Titanic Dataset - Exploratory Data Analysis

### Project Overview

This project is part of my Data Science Internship at Prodigy Infotech.

The objective of this task is to perform Exploratory Data Analysis (EDA) on the Titanic dataset to understand the factors that influenced passenger survival. The analysis includes data cleaning, visualization, relationship analysis, and identification of important patterns and trends.

### Dataset

The Titanic dataset contains information about passengers aboard the Titanic, including:

- Passenger ID
- Survival status
- Passenger class
- Name
- Gender
- Age
- Number of siblings/spouses aboard
- Number of parents/children aboard
- Ticket
- Fare
- Cabin
- Port of embarkation

### Tools and Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

### Data Cleaning

The following data cleaning steps were performed:

- Checked the dataset structure and data types.
- Identified missing values.
- Filled missing `Age` values using the median age.
- Filled missing `Embarked` values using the mode.
- Created a `CabinKnown` feature to indicate whether cabin information was available.
- Checked for duplicate records.
- Created `SexEncoded` for numerical analysis.
- Created `FamilySize` using the number of siblings/spouses and parents/children.

### Exploratory Data Analysis

The following relationships were explored:

- Overall survival distribution
- Survival by gender
- Survival by passenger class
- Age distribution
- Age and survival
- Fare and survival
- Survival by embarkation port
- Survival by siblings/spouses aboard
- Survival by parents/children aboard
- Survival by cabin information
- Gender and passenger class
- Family size and survival
- Correlation between numerical variables

### Key Findings

1. **Gender and Survival**

   Female passengers had a much higher survival rate of approximately **74.2%**, compared with **18.9%** for male passengers.

2. **Passenger Class and Survival**

   First-class passengers had the highest survival rate (**63.0%**), followed by second-class passengers (**47.3%**) and third-class passengers (**24.2%**).

3. **Gender and Passenger Class**

   The combination of gender and passenger class showed a strong pattern. Female passengers in first and second class had very high survival rates, while male passengers in third class had the lowest survival rate.

4. **Age and Survival**

   Age showed some differences between survivors and non-survivors, although its relationship with survival was weaker compared with gender and passenger class.

5. **Fare and Survival**

   Higher fares were generally associated with higher survival. Fare had a positive correlation with survival.

6. **Cabin Information and Survival**

   Passengers with recorded cabin information had a survival rate of approximately **66.7%**, compared with approximately **30.0%** for passengers without cabin information.

7. **Family Size**

   Family-related variables showed meaningful patterns in passenger survival. `SibSp` and `Parch` also showed a positive relationship with each other.

### Overall Survival

Out of **891 passengers**:

- **342 passengers survived**
- **549 passengers did not survive**
- Overall survival rate: approximately **38.4%**

### Conclusion

The Exploratory Data Analysis indicates that **gender and passenger class were among the strongest factors associated with survival** in the Titanic dataset.

Female and higher-class passengers generally had better survival outcomes, while male and third-class passengers had lower survival rates. Fare, cabin information, age, and family-related variables also showed meaningful patterns.

These findings represent associations observed in the dataset and do not necessarily imply that one variable directly caused survival.

### Project File

The complete analysis is available in the Jupyter Notebook:

`Task2_Titanic_EDA.ipynb`

---

**Internship:** Prodigy Infotech  
**Task:** Task 02 - Exploratory Data Analysis
