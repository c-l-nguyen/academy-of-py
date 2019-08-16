# academy-of-py

I have been asked to analyze the district-wide standardized test results at the Academy of Py school region. Using every student's math and reading scores, as well as various information on the schools they attend, I use the pandas package in Python to aggregate the data and showcase obvious trends in school performance. These trends include:

### District Summary

* A high level snapshot (in table form) of the district's key metrics, including:
  * Total Schools
  * Total Students
  * Total Budget
  * Average Math Score
  * Average Reading Score
  * % Passing Math
  * % Passing Reading
  * Overall Passing Rate (Defined to be the average of % Passing Math and % Passing Reading)

### School Summary

* An overview table that summarizes key metrics about each school, including:
  * School Name
  * School Type
  * Total Students
  * Total School Budget
  * Per Student Budget
  * Average Math Score
  * Average Reading Score
  * % Passing Math
  * % Passing Reading
  * Overall Passing Rate (Defined to be the average of % Passing Math and % Passing Reading)

### Top Performing Schools (By Passing Rate)

* A table that highlights the top 5 performing schools based on Overall Passing Rate. Including:
  * School Name
  * School Type
  * Total Students
  * Total School Budget
  * Per Student Budget
  * Average Math Score
  * Average Reading Score
  * % Passing Math
  * % Passing Reading
  * Overall Passing Rate (Defined to be the average of % Passing Math and % Passing Reading)

### Bottom Performing Schools (By Passing Rate)

* Same metrics as previous section, but with bottom 5 performing schools.

### Math Scores by Grade

* A table that lists the average Math Score for students of each grade level (9th, 10th, 11th, 12th) at each school.

### Reading Scores by Grade

* A table that lists the average Reading Score for students of each grade level (9th, 10th, 11th, 12th) at each school.

### Scores by School Spending

* A table that breaks down school performances based on average Spending Ranges (Per Student). It bins schools into 4 spending range bins to summarize by.
  * Average Math Score
  * Average Reading Score
  * % Passing Math
  * % Passing Reading
  * Overall Passing Rate (Defined to be the average of % Passing Math and % Passing Reading)

### Scores by School Size

* Same as the above breakdown, but this time schools are grouped based on a reasonable approximation of school size (Small, Medium, Large).

### Scores by School Type

* Same as the above breakdown, but this time schools are grouped based on school type (Charter vs. District).

### Extra Analysis

This is a bonus analysis to check the rankings of the schools using a "corrected" average. Before, I took the average of two averages to define an overall passing rate even though, technically, this is not correct. Do the results from above change if I take the corrected average compared to the average of averages?