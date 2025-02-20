# ABC-Company Employee Data Analysis
This project analyzes employee data from ABC company to understand various trends and patterns related to employee demographics, salaries, and team distribution.  The analysis involves data preprocessing, statistical analysis, and data visualization.

## Project Overview
This project aims to provide ABC company with a comprehensive report detailing information about their employees across various teams.  The analysis covers employee distribution across teams, salary distribution by position, age demographics, salary expenditure, and the correlation between age and salary.  Key insights are presented through visualizations and a summary report.

## Dataset
The dataset used in this analysis consists of 458 rows and 9 columns, containing information about ABC company's employees.  The data includes details such as employee age, salary, team, position, and other relevant attributes.
> The dataset is included in this repository as `myexcel.csv`.


## Methodology

The analysis was performed using Python with the Pandas, NumPy, Matplotlib, and Seaborn libraries. The following steps were undertaken:

1. **Data Preprocessing:** The 'height' column was corrected by replacing the existing values with random numbers between 150 and 180.
2. **Employee Distribution Across Teams:**  The distribution of employees across each team was calculated and visualized using a bar chart and countplot.
3. **Employee Segregation by Position:**  The distribution of employees by position was calculated and visualized using a pie chart and countplot.
4. **Predominant Age Group:** The age distribution of employees was visualized using a histogram.
5. **Salary Expenditure:** The salary expenditure for each team and position combination was calculated and visualized using a heatmap.
6. **Correlation Between Age and Salary:** The correlation between age and salary was analyzed and visualized using a scatter plot and a calculated correlation coefficient.
   

## Results and Insights
1."The 'Development' team has the largest number of employees, while the 'Testing' team has the smallest."
2."The most common position within the company is 'Software Engineer'."
3."The predominant age group among employees is between 25 and 35 years old."
4."The 'Development' team and 'Senior Software Engineer' position combination has the highest salary expenditure."
5."There is a moderate positive correlation between age and salary, indicating that older employees tend to have higher salaries."
