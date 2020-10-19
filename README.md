# School_District_Analysis

## Project Overview
An employee for the Education District has been tasked with getting key metrics from School District grades. The analysis was completed by performing calculations to get sums, averages, and percentages in the School District data for high school grades.
## Challenge Overview
After the school district committee reviewed the result, the school district suspected that the standardized test scores for ninth grade students at Thomas High School were somehow tampered or manipulated in some manner and they requested for the analysis to be repeated only this time excluding the grades for 9th graders in Thomas High School but the students would remain for that grade in order not to skew the other numbers in regards to budget, school size, budget per student and 

## Resources
- Data Source: schools_complete.csv
               students_complete.csv
- Software: Jupyter Notebook, Python 3.9.0

## Summary

### District School Analysis - Complete Data
Below are the results for the initial ananlysis for the school district summary. The high-level snapshot of the key metrics is as follows:

- Total number of students 39,170
- Total number of schools 15
- Total budget $24,649,428
- Average math score 79.0 (78.98537146)
- Average reading score 81.9 (81.87750517)
- Percentage of students who passed math 75%
- Percentage of students who passed reading 86%
- Overall passing percentage 65%

![alt text]( )


### School District Analysis - Excluding data
Below are the results for the second ananlysis performed for the school district summary after the grades for Thomas High School 9th Graders were removed from the data. This is a high-level snapshot of the district's key metrics:

Total number of students 38,709
Total number of schools 15
Total budget $24,649,428
Average math score 79.0 (78.93053295)
Average reading score 81.9 (81.85579581)
Percentage of students who passed math 75%
Percentage of students who passed reading 86%
Overall passing percentage 65%

![alt text]( )

## Results
Below is a more detailed analysis performed and the explanation of how they differ with the initial analysis of the data. Both math and reading scores were replaced with "NaN", which represents a "Not-a-Number" value. As a result of this change, 461 student grades were removed for math and reading respectively. Although it may seem a large number, compared to the total amount of students, the 461 only represents 1.2% of the total grades that were analyzed. 

### District Summary 
The District summary was not visibly affected due to the fact that when rounding the values up the changes were so minimally that they were not reflected in the formatted data. 
- District Summary Analysis Complete Data
![alt text]( )

- District Summary Analysis Excluded Data
![alt text]( )

### School Summary
The School Summary was affected by changing the grades for Thomas High School for math and reading. This ended up improving Thomas High School grades by 25%-30% when the 9th graders were removed compared to their math and reading scores in the initial analysis. Below are the images for both of the results:

- School Summary Analysis Complete Data
![alt text]( )

- School Summary Analysis Excluded Data
![alt text]( )

### Math and reading scores by grade

### 5 Top Schools and 5 Bottom Schools
### Scores by school spending
### Scores by school size
### Scores by school type


Summary: Summarize four major changes in the updated school district analysis after reading and math scores for the ninth grade at Thomas High School have been replaced with NaNs.




