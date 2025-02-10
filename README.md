# School Performance and Standardized Testing Analysis
Created and manipulated Pandas DataFrames to analyze school and standardized test data. 

## Project Overview
As the newly appointed Chief Data Scientist for the city's school district, your role is to leverage data-driven insights to assist the school board and the mayor in making strategic decisions about school budgets, resource allocation, and educational priorities.
<br><br>
Your first task is to analyze district-wide standardized test results to identify trends in student performance. You have access to a dataset containing math and reading scores for every student, along with additional school-related information such as budget, school size, and demographics.
<br><br>
By aggregating and manipulating this data using Pandas DataFrames, your goal is to uncover patterns in school performance. This analysis will help stakeholders understand how different factors impact student outcomes and guide future decision-making to improve educational quality across the district.

## Written Report
[Review PyCitySchool Report](https://github.com/skythelimitdt/pandas-challenge/blob/main/PyCitySchool%20Report.pdf)

## Data Sources
- School information: [schools_complete.csv](https://github.com/skythelimitdt/pandas-challenge/tree/main/Resources)
- Student Information: [student_complete.csv](https://github.com/skythelimitdt/pandas-challenge/tree/main/Resources)


## Technologies Used
- Jupyter Notebook
- Pandas

## References
Peer support on error below when pd.cut was used on this step # Use `pd.cut` on the per_school_capita Series from earlier to categorize per student spending based on the bins.
TypeError: '<' not supported between instances of 'int' and 'str'
This error was fixed by removing $ sign from per student budget.
