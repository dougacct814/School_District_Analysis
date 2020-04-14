# School_District_Analysis

## Project Overview

Module 4 challenge applied our skills using Pandas library and Jupyter Notebooks.  The challenge assignment background was that Maria and her supervisor discovered that the score averages for ninth graders from one high school are incorrect. Maria has asked you to replace the math and reading scores for that high school, but without removing those ninth-grade students from the analysis. 
The concept of the challenge was to replace incorrect data in columns using logical operations with conditionals; retrieve data from DataFrames; merge, filter, slice, and sort DataFrames; and apply the groupby() function to a DataFrame.


## Objectives

The goals of this challenge are for you to:
-	Filter DataFrames using logical operators.
-	Replace the incorrect values with NaN.
-	Explain how your PyCitySchools analysis changes after you handle the incorrect data. 


## Challenge Summary
Analysis:  After replacing the reading and math scores, recreate the district and school summary DataFrames and determine:

How is the district summary affected?
- The removal of the scores had a minimal affect on the overall district summary.  There are 39,710 total students analyzed in the district, so the removal of the Thomas high school 9th graders was a small fraction in the overall analysis.  The passing percentages for Reading, Math, and Overall were reduced by approximately 1%.
-	The Passing math student count was reduced by 431 students.
-	The Passing reading student count was reduced by 452 students.


How is the school summary affected?
-	The school summary included a dramatic reduction in passing percentage for Thomas High School.  Their analysis went from 90.94% Overall passing to 65.07% passing; a reduction of 25.87%.  Additionally, the overall passing math and reading percentages were drastically reduced.  
-	The Nan did not have a large impact on the average reading and math scores.

Analysis:  Recalculate the district and school summary DataFrames:

How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance, relative to the other schools?
-	The reading, math, and overall passing percentages for Thomas High School were reduced by approximately 25%.
-	Thomas High Scholl was second highest in overall passing percentage prior to the change.  Once the scores were removed, it dropped it down to 8th place. 

Analysis:  Recalculate the scores by grade, scores by school spending, scores by school size, and scores by school type:

How does replacing the ninth-grade scores affect the following?
•	Math and Reading Scores by Grade
- It had a dramatic change for Thomas High School relative to other schools.  Both the ninth-grade math and reading scores by grade displayed the NaN result when compared to the other schools.  

•	Scores by School Spending
- The category group of $630 - $644 percentage passing for reading, math, and overall were impacted and reduced.  Thomas School was categorized in this district, so it impacted the results only for this category. 
- The other spending ranges were unaffected.

•	Scores by School Size
- The category group of Medium School Size (1,000-2,000) percentage passing for reading, math, and overall were impacted and reduced.  Thomas School was categorized in this district, so it impacted the results only for this category. 
- The other school size ranges were unaffected.

•	Scores by School Type
- The category group of Charter percentage passing for reading, math, and overall were impacted and reduced.  Thomas School was categorized in this district, so it impacted the results only for this category. 
- The District School Summary was unaffected.
