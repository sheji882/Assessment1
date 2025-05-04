ABC Company Employee Data Analysis Project
Overview
This project is a comprehensive data analysis and visualization task based on a real-world employee dataset provided by ABC Company. The dataset consists of 458 rows and 9 columns, capturing various employee attributes such as team, position, salary, height, and age.

The goal of this project is to preprocess the data, perform multiple layers of analysis, and present key insights through visualizations. This exercise demonstrates proficiency in data wrangling, statistical analysis, and storytelling through data.# Assessment1
Module one assessment 
First Task Preprocessing
Task:
The height column contained inconsistent or unreliable data.
As part of the preprocessing step, the height values were replaced with random integers between 150 and 180 cm to ensure uniformity and realistic physical data.
Steps Taken
Loaded the dataset using pandas.
Verified presence and type of the height column.
Used numpy to generate random heights.
Confirmed data consistency post replacement.
**Analysis Tasks & Visualizations**

1. Employee Distribution by Team
Counted the number of employees in each team.
Calculated each team’s percentage share relative to total employees.
Visualization: Bar chart.
Insight: Identified dominant and underrepresented teams in the organization.

2. Employee Segregation by Position
Analyzed the distribution of employees across different job roles.
Visualization: Pie chart for role proportion.
Insight: Detected key positions that comprise the workforce and potential specialization areas.

3. Predominant Age Group
Binned age data into groups (19-23,24-29 etc.).
Counted number of employees in each group.
Visualization: Bar chart.
Insight: Identified the most common age range among employees, helping understand workforce demographics.

4. Salary Expenditure Analysis
Grouped data by team and position to compute total salary expenditure.
Identified the team and position with the highest financial impact.
Visualization: Bar charts for both team-wise and position-wise expenditure.
Insight: Gave visibility into cost-heavy areas, guiding budgeting and restructuring decisions.

5. Correlation Between Age and Salary
Calculated correlation coefficient.
Visualization: Scatter plot of age vs. salary.
Insight: There was a moderate positive correlation between age and salary, indicating that employees above 25 and below 35 generally earned more.
However, afew youngerand elder employees were seen earning high salaries

Key Insights
Certain teams dominate the employee distribution, indicating central departments.
The company has a young-to-mid-career workforce, with the 19–40 age group being the most common.
There is a moderate positive correlation between age and salary, suggesting that experience might influence pay.
Salary expenditure varies significantly across teams and positions, highlighting key investment areas.
The most financially impactful roles/teams can inform talent strategy and hiring.
