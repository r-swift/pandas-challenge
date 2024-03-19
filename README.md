# pandas-challenge
In this assignment, you’ll create and manipulate Pandas DataFrames to analyze school and standardized test data.

## Background
You are the new Chief Data Scientist for your city's school district. In this capacity, you'll be helping the school board and mayor make strategic decisions regarding future school budgets and priorities.

As a first task, you've been asked to analyze the district-wide standardized test results. You'll be given access to every student's math and reading scores, as well as various information on the schools they attend. Your task is to aggregate the data to showcase obvious trends in school performance.

## Instructions
Using Pandas and Jupyter Notebook, create a report that includes the following data. Your report must include a written description of at least two observable trends based on the data.

### District Summary
Perform the necessary calculations and then create a high-level snapshot of the district's key metrics in a DataFrame.

Include the following:
* Total number of unique schools
* Total students
* Total budget
* Average math score
* Average reading score
* % passing math (the percentage of students who passed math)
* % passing reading (the percentage of students who passed reading)
* % overall passing (the percentage of students who passed math AND reading)

### School Summary
Perform the necessary calculations and then create a DataFrame that summarizes key metrics about each school.

Include the following:
* School name
* School type
* Total students
* Total school budget
* Per student budget
* Average math score
* Average reading score
* % passing math (the percentage of students who passed math)
* % passing reading (the percentage of students who passed reading)
* % overall passing (the percentage of students who passed math AND reading)

### Highest-Performing Schools
* Sort the schools by % Overall Passing in descending order and display the top 5 rows.
  * Save the results in a DataFrame called "top_schools".

### Lowest-Performing Schools
* Sort the schools by % Overall Passing in ascending order and display the top 5 rows.
  * Save the results in a DataFrame called "bottom_schools".

### Math Scores by Grade
Perform the necessary calculations to create a DataFrame that lists the average math score for students of each grade level (9th, 10th, 11th, 12th) at each school.

### Reading Scores by Grade
Create a DataFrame that lists the average reading score for students of each grade level (9th, 10th, 11th, 12th) at each school.

### Scores by School Spending
Create a table that breaks down school performance based on average spending ranges (per student).
* Use the code provided below to create four bins with reasonable cutoff values to group school spending.
* Use pd.cut to categorize spending based on the bins.
* Use the following code to then calculate mean scores per spending range.
* Use the scores above to create a DataFrame called spending_summary.

Include the following metrics in the table:
* Average math score
* Average reading score
* % passing math (the percentage of students who passed math)
* % passing reading (the percentage of students who passed reading)
* % overall passing (the percentage of students who passed math AND reading)

### Scores by School Size
* Use pd.cut on the "Total Students" column of the per_school_summary DataFrame.
* Create a DataFrame called size_summary that breaks down school performance based on school size (small, medium, or large).

## Resources 
* Snippets of initial starter code provided by the school
* Class notes and lessons
* Assistance from Professor and TA to help fix formatting issue on school provided code

