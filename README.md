# Task 10 – Python EDA + Outlier Detection

## Objective
Perform Exploratory Data Analysis (EDA), detect outliers using IQR method, handle them, and export cleaned dataset.

## Dataset Used
Students Performance in Exams (Kaggle)

## Steps Performed
1. Loaded dataset using pandas
2. Checked shape, info, head
3. Generated descriptive statistics
4. Calculated missing value percentage
5. Plotted histograms and boxplots
6. Detected outliers using IQR
7. Capped outliers instead of removing
8. Created correlation matrix
9. Exported cleaned dataset

## Outlier Handling Strategy
IQR method was used.
Outliers were capped instead of removed to preserve dataset size.

## Key Insights
- Strong correlation between Reading and Writing scores.
- No missing values.
- Data ready for ML model building.

## Tools Used
Python
Pandas
NumPy
Matplotlib
Google Colab

## Files Included
- task10_eda.ipynb
- cleaned_dataset.csv
- eda_findings.txt
