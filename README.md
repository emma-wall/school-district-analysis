# School District Analysis

##Overview 
This repo uses Jupyter Notebooks to analyze student reading and math scores from multiple schools in a school district.  I wanted to know the average scores, percentage of passing each and the percentage of overall passing for each school. I also looked at these metrics based on the spending budgets per student, school size and type of school. After further examination of the files and results, it looked like there might be evidence of academic dishonesty with the 9th grade scores at Thomas High School. I reran the analysis removing the math and reading scores for all 9th grade students at Thomas High School. I found that the metrics did not change much by removing the 9th grade scores. 

##Results
* School District Summary
  Original District Summary
  ![District Summary](https://user-images.githubusercontent.com/80648379/118420263-733d3580-b68c-11eb-9681-aa7649451f27.png)
  
  Updated District Summary
  ![Updated District Analysis](https://user-images.githubusercontent.com/80648379/118420287-7fc18e00-b68c-11eb-9ce3-3d08e02b8d86.png)
  
  When we took out the 9th graders scores at Thomas High School, not much has changed overall for the district as a whole. The average math score dropped by 0.1 points.

* School Summary
  Original School Summary
  ![Thomas](https://user-images.githubusercontent.com/80648379/118420410-c31bfc80-b68c-11eb-9d70-f9607a2397bd.png)
  
  Updated School Summary 
  ![Updated Thomas](https://user-images.githubusercontent.com/80648379/118420429-d29b4580-b68c-11eb-8ca1-3540db339deb.png)
  In the updated analysis without the 9th grade scores, the average math score dropped by 0.07 points and the average reading score increased by 0.4 points. The % Passing Math and % Passing English both decreased and the % Overall Passing decreased by 0.3%.

* Preformance Relative to other Schools
    Although the % Overall Passing decreased, it did not affect it’s position as the second highest based on the % Overall Passing.
* Math and Reading Scores By Grade
    The only difference in the Math and Reading Scores by Grades Summaries is that for 9th Grade Thomas High School has ```NaN``` instead of an average score. 
    
* 
