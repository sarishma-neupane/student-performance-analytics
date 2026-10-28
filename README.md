### Student Performance & Academic Risk Analytics

This project analyzes the academic performance and placement status of 6,000 students. It uses Python (Pandas, Matplotlib, and Seaborn) to clean raw educational logs, perform exploratory data analysis (EDA), and handle missing values or data outliers. Finally, it features an interactive Power BI dashboard to visualize student risks and performance levels. 

### What is Inside This Project?

* **ecommerce_sales_dashboard.pbix** - The final Power BI dashboard with interactive charts tracking academic risk categories and performance tiers.
* **Student_Performance_Analysis.ipynb** - The Jupyter Notebook containing data understanding, data cleaning, and statistical summaries.
* **student_performance_dataset_6000_real_names.csv** - The raw dataset containing student names, attendance, marks, study hours, and placement status.

### Key Analytics & Data Cleaning Completed:

* **Missing Value Imputation:** Fixed missing data fields by replacing numeric nulls (Attendance, Family Income) with median values, and categorical columns (Extra Activities) with the statistical mode.
* **Data Standardization:** Converted grades and non-numeric strings ('A', 'B', 'C', 'Absent') in the final marks column into consistent raw integer values.
* **Outlier Management:** Analyzed internal marks, assignment scores, and final grades using box plots to ensure data integrity.
* **Feature Engineering:** Calculated overall student average scores to group individuals into actionable evaluation tiers: *Safe, Need Improvement, or At Risk*.

### Tools & Skills Used:

* **Python** (Pandas, Numpy, Matplotlib, Seaborn) - For data prep, outlier visualization, and cleaning metrics.
* **Power BI** - For building interactive academic monitoring dashboards and KPI tracking.
