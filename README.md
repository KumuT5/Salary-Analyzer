# Salary-Analyzer
Python-based salary analysis project using data cleaning, visualization, and insights.
A Python-based salary analysis project focused on data cleaning, merging, exploratory data analysis, visualization, and insight generation using real-world survey datasets (2019 & 2021).
This project was built entirely in Jupyter Notebook (Anaconda Cloud) using step-by-step transformations and plots.

**⭐ Project Overview**
The goal of this project is to understand how different factors influence salary in the tech/data industry.

**Key questions explored:**

-> How does experience impact salary?

-> Which job titles earn the highest?

-> Does education level affect compensation?

-> How are salaries distributed overall?

-> Which countries pay the most?

The project combines two survey datasets, cleans them, fixes inconsistencies, and produces clear, professional visualizations.

⭐ Technologies Used:
Python, 
Pandas, 
NumPy, 
Matplotlib, 
Seaborn, 
Jupyter Notebook (Anaconda Cloud).

⭐ Dataset Description:
Two survey datasets were merged -
2019responses.csv, 
2021responses.csv

After cleaning, the final dataset contains columns as:

🔹 Salary (USD)

🔹 Years of Experience

🔹 Job Title

🔹 Education Level

🔹 Company Size

🔹 Work Hours

🔹 Remote Days

🔹 Employment Type

🔹 Country

🔹 Survey Year

⭐ Data Cleaning Steps:

✔ Removed metadata rows

✔ Standardized column names

✔ Merged 2019 & 2021 datasets

✔ Converted salary to numeric

✔ Fixed invalid experience values (e.g., “2020”, “1997”)

✔ Removed outliers & duplicates

✔ Converted categoricals

✔ Filled missing values (median/mode)

✔ Sorted data by country/year

✔ Prepared final dataset stored in memory as dataset

**All transformations were performed directly inside the notebook.**

⭐ Visualizations: 

The following visualizations were created -

📌 1. Top 10 Countries by Salary **(Bar Plot)**

Shows which regions offer the highest compensation.

📌 2. Top Job Titles by Median Salary **(Column Chart)**

Reveals which roles are the highest-paying across the dataset.

📌 3. Salary vs Experience **(Scatter + Regression Line)**

A cleaned, corrected plot showing the relationship between experience and salary.

📌 4. Salary by Education Level **(Boxplot with custom blue palette)**
Visualizes how education influences pay.

📌 5. **Histograms** for Numeric Variables

Created for:
->Experience
->Work Hours
->Remote Days
->Team Size

📌 6. Modern Styled **Pie Chart**

Aesthetic pie chart showing education distribution.

**⭐ Insights**:
Here are the key insights derived from the analysis -

🔹 Experience

Salary increases with experience, but not dramatically, experience alone does not guarantee higher pay.

🔹 Job Titles

One of the strongest predictors of salary.
Roles like Data Engineer, Senior Developer, and Database Architect dominate the top salary tier.

🔹 Education

Higher education levels generally correspond to higher salaries, but Bachelor’s holders show the widest variation.

🔹 Salary Distribution

Right-skewed —> most salaries sit in the mid-range with a few extremely high earners pulling the average up.

🔹 Countries

Strong variation across regions, with US/Western Europe leading.

**Overall**:
What job you do and where you work impact salary more than years of experience.

**How to Run the Project**:

>>Clone the repository:
git clone https://github.com/KumuT5/Salary-Analyzer.git

>>Open the Jupyter Notebook:
Salary_Analyser.ipynb

>>Run each cell in order — the notebook contains:
data loading
cleaning
merging
visualization
insights

**⭐ Future Improvements**

* Build an interactive dashboard (Streamlit / Power BI)

* Add machine learning salary prediction

* Create role clustering using NLP

* Add filters for country/year to the visualizations

**Final Note**

This project represents a full real-world data analysis workflow:

✔ cleaning
✔ merging
✔ fixing corrupt values
✔ plots
✔ insights
✔ GitHub documentation
