# Task 5 – Exploratory Data Analysis (EDA) on Titanic Dataset

## Objective
The objective of this task is to perform Exploratory Data Analysis (EDA) on the Titanic dataset to identify patterns, trends, relationships, and factors influencing passenger survival.

## Tools Used
- Python
- Pandas
- Matplotlib
- Seaborn
- Jupyter Notebook

## Dataset
- Dataset Name: Titanic Dataset
- File: train.csv
- Total Records: 891
- Total Features: 12

## Notebook
- task_5.ipynb

## Analysis Performed

### 1. Data Inspection
- Used `info()` to understand data types and missing values.
- Used `describe()` to obtain statistical summaries.

### 2. Missing Value Analysis
Identified missing values in:
- Age
- Cabin
- Embarked

### 3. Univariate Analysis
- Age Distribution Histogram
- Fare Distribution Boxplot
- Survival Count Plot

### 4. Bivariate Analysis
- Gender vs Survival
- Passenger Class vs Survival
- Age vs Fare Scatter Plot

### 5. Multivariate Analysis
- Correlation Heatmap
- Pairplot Analysis

## Key Findings

### Age Distribution
- Most passengers were between 20 and 40 years old.
- Very few passengers were above 70 years old.

### Fare Distribution
- Fare values were highly right-skewed.
- Several extreme outliers were observed.

### Survival Analysis
- More passengers died than survived.
- Survival rate was approximately 38%.

### Gender vs Survival
- Female passengers had significantly higher survival rates.
- Most male passengers did not survive.

### Passenger Class vs Survival
- First-class passengers had the highest survival rate.
- Third-class passengers had the highest mortality rate.

### Correlation Analysis
- Fare showed a positive correlation with survival.
- Passenger class showed a negative correlation with survival.
- Fare and passenger class were strongly related.

### Scatter Plot Analysis
- Passengers paying higher fares were more likely to survive.
- Age alone did not significantly affect survival.

## Conclusion
The exploratory data analysis revealed that gender, passenger class, and ticket fare were the most important factors affecting passenger survival. Female passengers and first-class travelers had considerably better survival chances. The analysis successfully identified meaningful patterns and relationships within the Titanic dataset.

## Files Included

```text
Task-5-EDA-Titanic/
│
├── train.csv
├── task_5.ipynb
├── Titanic_EDA_Report_With_Images.pdf
├── README.md
└── Screenshots/
```

## Outcome
Successfully performed Exploratory Data Analysis (EDA) on the Titanic dataset and gained practical experience in data visualization, statistical analysis, trend identification, and insight generation using Python.
