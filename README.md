# Codveda Data Analytics Internship

**Intern:** Mustapha Abdulsamod Olamilekan
**Dataset:** Telecom customer churn (667 customers, 20 features)
**Tools:** Python, pandas, matplotlib, seaborn, scikit-learn, Tableau Public

## Level 1 (Basic)
- **Data Cleaning and Preprocessing** (`Level1_cleaning.ipynb`): no missing values or duplicates found. Standardized column names and converted Yes/No and True/False columns to 1/0.
- **Exploratory Data Analysis** (`Level1_EDA.ipynb`): summary statistics, histograms, boxplot, scatter plot and correlation heatmap. Churn is most associated with high day usage, frequent customer service calls and having an international plan.

## Level 2 (Intermediate)
- **Regression Analysis** (`Level2_Regression.ipynb`): linear regression of day charge on day minutes. R-squared is close to 1 because the charge is computed from minutes.
- **K-Means Clustering** (`Level2_Clustering.ipynb`): K = 3 chosen with the elbow method. One cluster of heavy-usage customers with frequent support calls has the highest churn rate (24%).

## Level 3 (Advanced)
- **Classification** (`Level3_Classification.ipynb`): compared Logistic Regression, Decision Tree and Random Forest, then tuned a Random Forest with grid search. Tuned model: accuracy 0.925, precision 0.714, recall 0.789, F1 0.750 (cross-validated F1 0.581).
- **Tableau Dashboard:** [View the interactive dashboard](https://public.tableau.com/app/profile/mustapha.abdulsamod.olamilekan/viz/Churnbyservicecalls/Dashboard1)

## Notes
The test set contains only about 19 churned customers, so classification metrics are indicative rather than precise.
