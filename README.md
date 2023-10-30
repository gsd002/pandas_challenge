# pandas_challenge
Module 4 Challenge - PyCitySchools 
As the new Chief Data Scientist for the local government area, help the school board and mayor make strategic decisions regarding future school budgets and priorities.
**TASK** 
    Analyse the area-wide standardised test results – Being given access to every student's maths and reading scores, as well as various information on the schools they attend, aggregate the data to showcase obvious           trends in school performance.
    Report at least 2 observable trends based on the data.
**LGA SUMMARY**
    Perform necessary calculations and create a high-level snapshot of the local government area’s key metrics in a DataFrame. (Passing Grade is 50 or higher)
      Include –
        	Total number of unique schools
        	Total students
        	Total budget
        	Average maths score
        	Average reading score
        	% passing maths (the percentage of students who passed maths)
        	% passing reading (the percentage of students who passed reading)
        	% overall passing (the percentage of students who passed maths AND reading)

**SCHOOL SUMMARY**
    Perform the necessary calculations and then create a DataFrame that summarises key metrics about each school.
      Include –
        	School name
        	School type
        	Total students
        	Total school budget
        	Per student budget
        	Average maths score
        	Average reading score
        	% passing maths (the percentage of students who passed maths)
        	% passing reading (the percentage of students who passed reading)
        	% overall passing (the percentage of students who passed maths AND reading)

**HIGHEST-PERFORMING SCHOOLS (BY % OVERALL PASSING)**
        	Sort the schools by ‘% Overall Passing’ in descending order and display the top 5 rows.
        	Save the results in a DataFrame called "top_schools".

**LOWEST-PERFORMING SCHOOLS (BY % OVERALL PASSING)**
        	Sort the schools by ‘% Overall Passing’ in ascending order and display the top 5 rows. 
        	Save the results in a DataFrame called “bottom_schools”.

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
        	Average maths score
        	Average reading score
        	% passing maths (the percentage of students who passed maths)
        	% passing reading (the percentage of students who passed reading)
        	% overall passing (the percentage of students who passed maths AND reading)

**SCORES BY SCHOOL SIZE**
    Use the following code to bin the ‘per_school_summary’.
    Use ‘pd.cut’ on the "Total Students" column of the ‘per_school_summary’ DataFrame.
    Create a DataFrame called ‘size_summary’ that breaks down school performance based on school size (small, medium, or large).

**SCORES BY SCHOOL TYPE**
    Use the ‘per_school_summary’ DataFrame from the previous step to create a new DataFrame called ‘type_summary’.
    This new DataFrame should show school performance based on the "School Type".
