# School_District_Analysis

### Overview of the Analysis
School Analysis projects helps to identify the per Student capita, and also to know per school performance in the reading and math subjects. This analysis also will help to 
get an overview how much spending budgets needs to be allocated in the coming years.

## Results

#### How is the district summary affected?
The overall performance of the district school summary hasn't been affected much, the averages of reading and math scores has been reduced by hardly 1%.

#### How is the school summary affected?
The overall pass percentages , reading and math scores has not changed for all the other schools except the Thomas High School. The Thomas High School has seen drastic drop of the percentages from 90 to 60.

#### How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?
After removing the 9th grade score in calculating the averages and passing percentages, Thomas High School has dropped from Top 5 Performing schools, it was previously 2nd place in the entire district. Their passing percentages dropped from 90 to 60 as shown below.
![Beforeremovalofninthgrades](/Resources/Beforeremovalofninthgrades.png) <br/>
![Afterremovalofninthgrades](/Resources/Afterremovalofninthgrades.png) <br/>

#### How does replacing the ninth-grade scores affect the following:
1. Math and reading scores by grade <br/>
   By removing the 9th grade scores, Thomas High School overall passing percentage , reading and math percentages has dropped drastically.
  
1. Scores by school spending <br/>
   Spending Budget didn't change much, but the per student captia has been changed from 638 to 600.
1. Scores by school size <br/>
   School Size didnt change the school performances as we've considered everything.
1. Scores by school type <br/>
   Samething with the School Type
   
## Summary
Replacing the summary 9th grade scores for Thomas High School was little challenging. 
1. Need to filter the Student Data to Thamos High School
2. Filtering the data to 9th Grade
3. Replace all the reading score to NaN , similarly replacing the Math Scores to NaN.
4. Calculate the percentages of the Thomas High School Averages of scores and repective percentages and also make the new calculations replace in the existing per school summary.



   

