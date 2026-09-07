# Task 5: Exploratory Data Analysis (EDA) — Titanic Dataset

## Objective
Explore the Titanic dataset using statistical summaries and visualizations to identify patterns, relationships, trends, and anomalies.

## Tools Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook / Google Colab

## Analysis Performed
- Dataset structure and statistical summary using `info()` and `describe()`
- Missing-value and duplicate checks
- Categorical frequency analysis using `value_counts()`
- Data cleaning and feature creation
- Survival distribution
- Survival by gender and passenger class
- Age and fare distributions
- Fare outlier analysis using a boxplot
- Survival-rate analysis
- Pairplot and correlation heatmap
- Age-group analysis
- Cabin availability analysis

## Key Findings
- 891 passengers were analyzed.
- 342 passengers (38.38%) survived and 549 (61.62%) did not.
- Female survival rate was 74.20%, compared with 18.89% for males.
- First-class passengers generally had higher survival than third-class passengers.
- Female first-class survival was about 96.81%, while male third-class survival was about 13.54%.
- Fare was strongly right-skewed and contained high-value outliers.
- Cabin had 687 missing values, so cabin numbers were not artificially imputed; a `CabinAvailable` indicator was created instead.

## Files
- `Task_5_Titanic_EDA_Final.ipynb` — final annotated Jupyter Notebook
- `Titanic_EDA_Report.pdf` — PDF report of findings
- `titanic-dataset.csv` — source dataset (upload your original CSV to GitHub if permitted)

## Conclusion
The EDA indicates that gender and passenger class were the strongest visible factors associated with survival in the Titanic dataset. The analysis also demonstrates the importance of handling missing values and outliers carefully before further statistical or machine-learning work.
