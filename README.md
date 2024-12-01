## PyCitySchools Analysis

Project Overview
This project analyzes the performance of schools within a city’s school district. The goal is to help district leaders make informed decisions on school budgets and priorities by examining various factors that impact student success, such as school type, size, and per-student spending. The analysis was conducted using Python and the Pandas library.

Summary of Analysis
This analysis evaluates school performance across math and reading scores, exploring the effects of school type, size, and per-student spending. By understanding these relationships, district leaders can better allocate resources to enhance academic outcomes.

## Key Findings
1. Charter vs. District Schools
Charter schools consistently outperformed District schools.
Charter schools had a higher overall passing rate (90.43%) and average math and reading scores (83.47 and 83.90, respectively) compared to District schools, where the passing rate was 53.67% with lower average scores.
This suggests Charter schools may benefit from unique instructional methods that could inform improvements in District schools.

3. School Size and Student Success
Smaller schools (<1,000 students) showed the best overall passing rate at 89.88%.
Larger schools (2,000-5,000 students) had a significantly lower passing rate of 58.29%.
The data suggests that smaller or medium-sized learning environments (up to 2,000 students) may allow for more effective student support, leading to higher academic achievement.

5. Spending Efficiency
Schools spending less than $585 per student had the highest overall passing rate at 90.37%.
Schools in the highest spending bracket ($645-680) showed the lowest passing rate at 53.53%.
This trend implies that resource allocation efficiency, rather than increased spending alone, plays a critical role in academic performance.

## Conclusion
These findings suggest that promoting smaller school sizes, studying Charter school practices, and optimizing resource use could enhance academic outcomes across the district.

Files
PyCitySchools_starter.ipynb: Jupyter Notebook containing the code for data loading, cleaning, analysis, and visualization.
Resources/schools_complete.csv: Data file containing school information (name, type, student size, and budget).
Resources/students_complete.csv: Data file containing individual student scores and school associations.
Installation
To run this project, you need:

Python 3.x
Jupyter Notebook
Pandas library
