# School District Analysis

## Overview 
This repo uses Jupyter Notebooks to analyze student reading and math scores from multiple schools in a school district.  I wanted to know the average scores, percentage of passing each and the percentage of overall passing for each school. I also looked at these metrics based on the spending budgets per student, school size and type of school. After further examination of the files and results, it looked like there might be evidence of academic dishonesty with the 9th grade scores at Thomas High School. I reran the analysis removing the math and reading scores for all 9th grade students at Thomas High School. I found that the metrics did not change much by removing the 9th grade scores. 

## Results
### School District Summary
  Original District Summary
  ![District Summary](https://user-images.githubusercontent.com/80648379/118420263-733d3580-b68c-11eb-9681-aa7649451f27.png)
  
  Updated District Summary
  ![Updated District Analysis](https://user-images.githubusercontent.com/80648379/118420287-7fc18e00-b68c-11eb-9ce3-3d08e02b8d86.png)
  
  When we took out the 9th graders scores at Thomas High School, not much has changed overall for the district as a whole. The average math score dropped by 0.1 points.

### School Summary
  Original School Summary
  ![Thomas](https://user-images.githubusercontent.com/80648379/118420410-c31bfc80-b68c-11eb-9d70-f9607a2397bd.png)
  
  Updated School Summary 
  ![Updated Thomas](https://user-images.githubusercontent.com/80648379/118420429-d29b4580-b68c-11eb-8ca1-3540db339deb.png)
  
  In the updated analysis without the 9th grade scores, the average math score dropped by 0.07 points and the average reading score increased by 0.4 points. The % Passing Math and % Passing English both decreased and the % Overall Passing decreased by 0.3%.

### Preformance Relative to other Schools
    Although the % Overall Passing decreased, it did not affect it’s position as the second highest based on the % Overall Passing.

### Math and Reading Scores By Grade
    The only difference in the Math and Reading Scores by Grades Summaries is that for 9th Grade Thomas High School has ```NaN``` instead of an average math score of 83.6 and average reading score of 83.7. 
    
### Scores By School Spending
  Original Spending Summary 
  [Spending](https://user-images.githubusercontent.com/80648379/118421335-fc556c00-b68e-11eb-9be0-b9c09d112727.png)

  Updated Spending Summmary 
  ![Updateed Spending](https://user-images.githubusercontent.com/80648379/118421362-0b3c1e80-b68f-11eb-9be7-f5913e2655af.png)

  
  Thomas High School falls into the 630-644 per student spending range. The removal of the 9th grade scores did not affect the average math or reading score, or the percent passing math, but it did bring down the percent the % Passing Reading and the % Overall Passing by 0.1%.!


### Scores By School Size
  Original School Size Summary 
  ![Size](https://user-images.githubusercontent.com/80648379/118421465-46d6e880-b68f-11eb-8370-a41a5a95c219.png)
  
  Updated School Size Summary
  ![Updated Size](https://user-images.githubusercontent.com/80648379/118421553-5eae6c80-b68f-11eb-8d2f-2efc76a2fb01.png)
  
  Thomas High School is considered a medium size high school. From the above it appears the only the % Passing reading changed by -0.1%, all of the other metrics stayed the same. 


### Scores By School Type
  
  Removing the math and reading scores did not have affect the summary by type, all the metrics stayed the same.

## Summary
After replacing the 9th grade Thomas High School Scores with ```NaNs``` there was not 
