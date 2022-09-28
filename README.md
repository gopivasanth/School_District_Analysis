# School District Analysis
Analysis on school district performance using Jupyter Notebook, Pandas and Numpy.

## Project Overview

A School Board wanted an analysis of the test scores across the regional schools especially on math and reading scores. They intend to use this to formalize next years budget for the school and therefore require summary metrics of each school in order to make this decision.

This summary was completed when the school board learned of academic dishonesty happening among the ninth grade students at Thomas Highschool (THS.

A new summary has to be constructed for the school board. The School Board wanted to understand the impact of changing all the grade 9 math and reading scores at Thomas High School to NaN - we will now review how this change impact various parts of the analysis relative to when it was ran including the Thomas High School grade 9 scores

The School Board wanted to understand various performance metrics of different school districts and schools. 

## Purpose 

The purpose of this analysis is to analyze data on students math and reading scores from various schools in the selected districts. To showcase trends in school performance, the analysis focuses on the following.

1.  The district summary
    - total number of students
    - the total number of schools
    - total budget
    - math and reading averages
    - math performance
    - reading performance
    - overall passing percentages

2. The school summary
    - school type
    - number of students
    - school budget
    - average math and reading scores 
    - math performance 
    - reading performance 
    - overall passing percentages for each school

3.  The top 5 and bottom 5 performing schools, based on the overall passing rate.

4.  The  average math and reading scores for each grade level (9th, 10th, 11th and 12th) from each school.

5.  The math and reading scores by
    -   Spending ranges per students
    -   School size
    -   School type

The analysis will assist the school board in making decisions regarding the school budgets.

## Approach

The data was in two different CSV files (school data and student data). 
This raw data was transformed to perform analysis using Pandas and Numpy libraries.

## Results
Owing to academic dishonesty for math and reading scores in Thomas High School for ninth graders; 
The grades for math and reading in Thomas High School, 9th graders were replaced with NaNs. 
In the analysis below is the comparison from both analyses before and after the replacement the grades with NaNs.The analysis aims to address the folloing points:

How is the district summary affected?
-   In this summary, the results were NOT impacted by NaNs. The change of results from Thomas High School 9th grade had minimal impact on district Analysis.
-   Each metric decreased by less that 0.5 percentage point each (meaning scores changed by less than 0.5%

![Old District Summary](https://github.com/gopivasanth/School_District_Analysis/blob/0e484e8f33b4d4f98aa692de640b61f553d6c0d3/Resources/new_district_summary.png)

![New District Summary](https://github.com/gopivasanth/School_District_Analysis/blob/0e484e8f33b4d4f98aa692de640b61f553d6c0d3/Resources/old_district_summary.png)

How is the school summary affected?
-   results for School summary remained unchanged.
-   Average math and reading scores remained unchanged.
-   Passing math and reading percentage remained unchanged.
-   Overall passing percentage had no impact either.

![New School Summary](https://github.com/gopivasanth/School_District_Analysis/blob/0e484e8f33b4d4f98aa692de640b61f553d6c0d3/Resources/new_school_summary.png)

![Old School Summary](https://github.com/gopivasanth/School_District_Analysis/blob/0e484e8f33b4d4f98aa692de640b61f553d6c0d3/Resources/school_summary_old.png)

The analysis aims to address the below points as well

How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?

- only grades from Thomas High school in 9th grade was affected for math and reading.
- Grade 9 students at Thomas High School have NaN's
- analysis were performed separately for each class and each school; hence other graders and schools weren’t affected.

Below is the comparison of schools Maths Perforamance before and after converting NaN's

![Old_Maths](https://github.com/gopivasanth/School_District_Analysis/blob/0e484e8f33b4d4f98aa692de640b61f553d6c0d3/Resources/Old_Maths.png)

![New_Maths](https://github.com/gopivasanth/School_District_Analysis/blob/0e484e8f33b4d4f98aa692de640b61f553d6c0d3/Resources/New_Maths.png)

Below is the comparison of schools Reading Perforamance before and after converting NaN's

![Old_Reading](https://github.com/gopivasanth/School_District_Analysis/blob/0e484e8f33b4d4f98aa692de640b61f553d6c0d3/Resources/Old_Reading.png))

![New_Reading](https://github.com/gopivasanth/School_District_Analysis/blob/0e484e8f33b4d4f98aa692de640b61f553d6c0d3/Resources/New_Reading.png)

**The top 5 and bottom 5 performing schools, based on the overall passing rate**
-   The overall rating for Thomas High School changed slightly.
-   The school rank remained second after changing scores with NaNs.

**impact on school spending**

-   From the Data Frame we can see that Thomas High school falls into a category  _spending range per students $630-$644_.
-   Calculations are made separately for those categories; therefore, scores in this summary are affected only within a category with NaNs.
-   Each metric changing less than 0.1 percentage points or change of less than 0.1%.

![Old_Spending](https://github.com/gopivasanth/School_District_Analysis/blob/0e484e8f33b4d4f98aa692de640b61f553d6c0d3/Resources/Old_Spending.png)

![New_Spending](https://github.com/gopivasanth/School_District_Analysis/blob/0e484e8f33b4d4f98aa692de640b61f553d6c0d3/Resources/New_Spending.png)

**impact on school size**

-   From the Data Frame we can see that Thomas High school falls into a category  _medium size school_.
-   Calculations are made separately for those categories; therefore, scores in this summary are affected only within a category with NaNs.
-   Each Metric was impacted by less than 0.1%. 

![Old_School_Size](https://github.com/gopivasanth/School_District_Analysis/blob/0e484e8f33b4d4f98aa692de640b61f553d6c0d3/Resources/Old_School_Size.png)

![New_School_Size](https://github.com/gopivasanth/School_District_Analysis/blob/0e484e8f33b4d4f98aa692de640b61f553d6c0d3/Resources/New_School_size.png)

**impact on the type of school**
-   From the Data Frame we can see that Thomas High school falls into a category  _Charter_  for school type.
-   Calculations are made separately for those categories; therefore, scores in this summary are affected only within a category with NaNs.
-   Again the overall impact to all metrics was less than 0.1%.

![Old_School_Type](https://github.com/gopivasanth/School_District_Analysis/blob/0e484e8f33b4d4f98aa692de640b61f553d6c0d3/Resources/Old_School_Type.png)

![New_School_Type](https://github.com/gopivasanth/School_District_Analysis/blob/0e484e8f33b4d4f98aa692de640b61f553d6c0d3/Resources/New_School_Type.png)

## Summary
Replacing the maths and reading grades for 9th grade students of Thomas High School didn't impact the summary reports to a great extent.
*  The overall impact on results very minimal. In individual case it is as less than 1%. 
*  There were minor changes in school summaries by spending per student, size, and type.    