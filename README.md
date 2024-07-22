# pandas-challenge
Using Pandas and Jupyter Notebook, I created a report that includes the following data. 

# District Summary

    Total number of unique schools

    Total students

    Total budget

    Average math score

    Average reading score

    % passing math (the percentage of students who passed math)

    % passing reading (the percentage of students who passed reading)

    % overall passing (the percentage of students who passed math AND reading)

# School Summary

    School name

    School type

    Total students

    Total school budget

    Per student budget

    Average math score

    Average reading score

    % passing math (the percentage of students who passed math)

    % passing reading (the percentage of students who passed reading)

    % overall passing (the percentage of students who passed math AND reading)

    Highest-Performing Schools (by % Overall Passing)
    Sort the schools by % Overall Passing in descending order and display the top 5 rows.

    Save the results in a DataFrame called "top_schools".

    Lowest-Performing Schools (by % Overall Passing)
    Sort the schools by % Overall Passing in ascending order and display the top 5 rows.

    Save the results in a DataFrame called "bottom_schools".

    Math Scores by Grade
    Perform the necessary calculations to create a DataFrame that lists the average math score for students of each grade level (9th, 10th, 11th, 12th) at each school.

# Reading Scores by Grade
    Create a DataFrame that lists the average reading score for students of each grade level (9th, 10th, 11th, 12th) at each school.

    Scores by School Spending
    Create a table that breaks down school performance based on average spending ranges (per student).

    Use the code provided below to create four bins with reasonable cutoff values to group school spending.


# Scores by School Spending
    Create a table that breaks down school performance based on average spending ranges (per student).

    Use the code provided below to create four bins with reasonable cutoff values to group school spending.

    spending_bins = [0, 585, 630, 645, 680]
    labels = ["<$585", "$585-630", "$630-645", "$645-680"]
    Use pd.cut to categorize spending based on the bins.

    Calculate mean scores per spending range.

    Include the following metrics in the table:

    Average math score

    Average reading score

    % passing math (the percentage of students who passed math)

    % passing reading (the percentage of students who passed reading)

    % overall passing (the percentage of students who passed math AND reading)

    Scores by School Size
    Use the following code to bin the per_school_summary.

    size_bins = [0, 1000, 2000, 5000]
    labels = ["Small (<1000)", "Medium (1000-2000)", "Large (2000-5000)"]
    Use pd.cut on the "Total Students" column of the per_school_summary DataFrame.

    Create a DataFrame called size_summary that breaks down school performance based on school size (small, medium, or large).

# Scores by School Type
    Use the per_school_summary DataFrame from the previous step to create a new DataFrame called type_summary.

    This new DataFrame should show school performance based on the "School Type".


PyCity School Analysis

Analysis Overview:

    Total Schools: 15
    Total Students: 39170
    Total Budget: $24,649,428.00
    Average Math Score: 78.985371
    Average Reading Score: 81.87784
    Passing Math(%) : 74.980853
    Passing Reading(%): 85.805463
    Overall Passing Rate(%): 65.172326

# Two observable trends based on the data.

The Top 5 Highest-Performing Schools by Percentage of Overall Passing
    Cabrera High School: 91.3%
    Thomas High School: 90.9%
    Griffin High School: 90.6%
    Wilson High School: 90.58%
    Pena High School: 90.54%

The Three Lowest-Performing Schools by Percentage of Overall Passing
    Rodriguez High School: 52.99%
    Figueroa High School: 53.20%
    Huang High School: 53.51%


