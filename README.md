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

![alt text](https://github.com/sandramcardona/School_District_Analysis/blob/main/Resources/Disctrict_School_Analysis_Final.png )


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

![alt text](https://github.com/sandramcardona/School_District_Analysis/blob/main/Resources/Challenge_District_Summary.png )

## Results
Below is a more detailed analysis performed and the explanation of how they differ with the initial analysis of the data. Both math and reading scores were replaced with "NaN", which represents a "Not-a-Number" value. As a result of this change, 461 student grades were removed for math and reading respectively. Although it may seem a large number, compared to the total amount of students, the 461 only represents 1.2% of the total grades that were analyzed. 

### District Summary 
The District summary was minimally affected due to the fact that when rounding the values up the changes were so minimally that they were not reflected in the formatted data. 
- District Summary Analysis Complete Data
![alt text](https://github.com/sandramcardona/School_District_Analysis/blob/main/Resources/Disctrict_School_Analysis_Final.png )

- District Summary Analysis Excluded Data
![alt text](https://github.com/sandramcardona/School_District_Analysis/blob/main/Resources/Challenge_District_Summary.png )

### School Summary
The School Summary was affected by changing the grades for Thomas High School for math and reading. This ended up improving Thomas High School grades by 25%-30% when the 9th graders were removed compared to their math and reading scores in the initial analysis. 
Thomas High School now has some of the highest passing scores compared to other schools. Below are the images for both of the results:

- School Summary Analysis Complete Data
![alt text](https://github.com/sandramcardona/School_District_Analysis/blob/main/Resources/Per_School_Summary.png )

- School Summary Analysis Excluded Data
![alt text](https://github.com/sandramcardona/School_District_Analysis/blob/main/Resources/Challenge_School_Summary.png )

### Math and reading scores by Grade
The Math and Reading scores by grade were not affected. This is due to the fact that this number is calculated as an average of all the values within the school. 

### Math and Reading Passing Percentages
The passing percentages were  affected by removing the 9th graders grades for Thomas High School for math and reading. This ended up improving Thomas High School passing percentages from 25%-30%. This improved the performance of the high school by close to 30%. Below are the images for a better understanding of the changes that occurred:

- Math and Reading Passing Percentages Complete Data
![alt text](https://github.com/sandramcardona/School_District_Analysis/blob/main/Resources/Thomas_HS_results_Complete_Data.png )

- Math and Reading Passing Percentages Excluded Data
![alt text](https://github.com/sandramcardona/School_District_Analysis/blob/main/Resources/Thomas_HS_Removed_Data.png )

### 5 Top Schools and 5 Bottom Schools
The biggest changed observed after removing the 9th graders grades for Thomas High School was that it became the 2nd Top school with an overall passing score of 90.6% compared to being in the 7th place with an overall passing score of 65.1%. Below are the images for both analysis for the 5 top Schools

- Top Schools  Complete Data - Thomas High School shows as 7th place
![alt text]( https://github.com/sandramcardona/School_District_Analysis/blob/main/Resources/Top_5_Schools_THS_7th_complete_Data.png)

- Top Schools Excluded Data - Thomas High School shows as 2nd place
![alt text]( https://github.com/sandramcardona/School_District_Analysis/blob/main/Resources/Challenge_Top_5_Schools.png)


### Scores by school spending
There was no change observed for this metric because the number of students did not change, only the grades for math and reading were removed for the 9th graders at Thomas High School. Thomas High school remained in the $630-644 ranges per student in both analysis.

### Scores by school size
There was no change observed for this metric because the number of students did not change, only the grades for math and reading were removed for the 9th graders at Thomas High School. Thomas High school remained a Medium size School in both analysis.

### Scores by school type

The scores by school type were also affected by removing the 9th graders grades for Thomas High School for math and reading. This ended up improving the charter school passing percentages from by 3-4 points higher compared to the intial review. This is du to Thomas High School being a Charter school.  Below are the images that show the initial numbers and the ones after.

- Scores by school type Complete Data
![alt text](https://github.com/sandramcardona/School_District_Analysis/blob/main/Resources/School_Type_Summary_Complete_Data.png )

- Scores by school type Excluded Data
![alt text](https://github.com/sandramcardona/School_District_Analysis/blob/main/Resources/School_Type_Summary_Removed_Data.png )

After finishing the review, it was concluded that by removing the 9th graders grades for Thomas High School for math and reading made a significance improvement. The Summary of School shows that the school now ranks some of the highest passing scores. For the passing percentages for math, reading and overall passing scores it shows a 25-30% increase compared to the original scores. It now ranks 2nd instead of 7th among all the other schools based on these scores. Lastly, it improved the Charter schools overall passing percentges compared to the District schools. 




