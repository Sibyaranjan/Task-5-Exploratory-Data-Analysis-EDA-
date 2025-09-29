# Task-5-Exploratory-Data-Analysis-EDA-

Project Overview
This Task performs **Exploratory Data Analysis (EDA)** on the famous **Titanic dataset** to explore passenger demographics, travel class distribution, survival patterns, and correlations between different features.  
The Titanic dataset is widely used in data science to practice data cleaning, visualization, and statistical analysis.

---

 Steps Performed
1. **Data Collection**  
   - Loaded the Titanic dataset into the environment.

2. **Data Cleaning**  
   - Checked and handled missing values (Age, Cabin, Embarked).  
   - Converted categorical variables (Sex, Embarked) into the correct format.  
   - Removed duplicate entries if any.  

3. **Univariate Analysis**  
   - Analyzed age distribution of passengers.  
   - Count plots for survival, gender, and class distribution.  

4. **Bivariate Analysis**  
   - Survival rate across gender and passenger class.  
   - Relationship between age and survival.  
   - Correlation heatmap for numerical features.  

5. **Multivariate Analysis**  
   - Impact of multiple factors (e.g., Gender + Class + Age) on survival probability.  
   - Visualization using grouped bar charts and stacked plots.  

6. **Insights & Findings**  
   - Female passengers had a much higher survival rate than males.  
   - Passengers in **1st class** were more likely to survive compared to 2nd and 3rd class.  
   - Younger passengers had a higher survival probability.  
   - Embarkation port showed survival variations (Southampton had more passengers but lower survival %).  

Tools & Libraries Used
- **Python**
- **Pandas** – Data cleaning and manipulation  
- **NumPy** – Numerical computations  
- **Matplotlib** & **Seaborn** – Data visualization  
