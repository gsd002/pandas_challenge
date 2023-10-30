# pandas_challenge
Module 4 Challenge - PyCitySchools 
As the new Chief Data Scientist for the local government area, help the school board and mayor make strategic decisions regarding future school budgets and priorities.
	**TASK** 
    Analyse the area-wide standardised test results – Being given access to every student's maths and reading scores, as well as various information on the schools they attend, aggregate the data to showcase obvious           trends in school performance.
    Report at least 2 observable trends based on the data.
	**LGA SUMMARY**
    Perform necessary calculations and create a high-level snapshot of the local government area’s key metrics in a DataFrame. (Passing Grade is 50 or higher)
      Include –
        1. Total number of unique schools
				2. Total students
        3. Total budget
        4. Average maths score
        5. Average reading score
        6. % passing maths (the percentage of students who passed maths)
        7. % passing reading (the percentage of students who passed reading)
        8. % overall passing (the percentage of students who passed maths AND reading)

  **SCHOOL SUMMARY**
    Perform the necessary calculations and then create a DataFrame that summarises key metrics about each school.
      Include –
        1.	School name
        2.	School type
        3.	Total students
        4.	Total school budget
        5.	Per student budget
        6.	Average maths score
        7.	Average reading score
        8.	% passing maths (the percentage of students who passed maths)
        9.	% passing reading (the percentage of students who passed reading)
        10.	% overall passing (the percentage of students who passed maths AND reading)

  **HIGHEST-PERFORMING SCHOOLS (BY % OVERALL PASSING)**
        1.	Sort the schools by ‘% Overall Passing’ in descending order and display the top 5 rows.
        2.	Save the results in a DataFrame called "top_schools".

  **LOWEST-PERFORMING SCHOOLS (BY % OVERALL PASSING)**
        1.	Sort the schools by ‘% Overall Passing’ in ascending order and display the top 5 rows. 
        2.	Save the results in a DataFrame called “bottom_schools”.

  **MATHS SCORES BY YEAR**
    Perform the necessary calculations to create a DataFrame that lists the average maths score for students of each year level (9, 10, 11, 12) at each school.

  **READING SCORES BY YEAR**
    Create a DataFrame that lists the average reading score for students of each year level (9, 10, 11, 12) at each school.

  **SCORES BY SCHOOL SPENDING**
    Create a table that breaks down school performance based on average spending ranges (per student).
    Use the code provided below to create four bins with reasonable cutoff values to group school spending. 
    Use ‘pd.cut’ to categorise spending based on the bins.
    Use the following code to then calculate mean scores per spending range. 
    Use the scores above to create a DataFrame called ‘spending_summary’.
      Include the following metrics in the table:
        1.	Average maths score
        2.	Average reading score
        3.	% passing maths (the percentage of students who passed maths)
        4.	% passing reading (the percentage of students who passed reading)
        5.	% overall passing (the percentage of students who passed maths AND reading)

  **SCORES BY SCHOOL SIZE**
    Use the following code to bin the ‘per_school_summary’.
    Use ‘pd.cut’ on the "Total Students" column of the ‘per_school_summary’ DataFrame.
    Create a DataFrame called ‘size_summary’ that breaks down school performance based on school size (small, medium, or large).

  **SCORES BY SCHOOL TYPE**
    Use the ‘per_school_summary’ DataFrame from the previous step to create a new DataFrame called ‘type_summary’.
    This new DataFrame should show school performance based on the "School Type".
