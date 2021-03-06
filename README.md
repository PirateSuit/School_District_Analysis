# School_District_Analysis

## Overview of the school district analysis:

### The purpose of this analysis is to remove the tainted data from the work we did in the module (9th grader's reading and math scores from Thomas High School) and to output data that reflects how the removal effected previous data.

## Results

### District Summary

Here is the district summary:
![image_name](https://github.com/PirateSuit/School_District_Analysis/blob/main/results_photos/district_summary.png)

And here is the district summary refactored:
![image_name](https://github.com/PirateSuit/School_District_Analysis/blob/main/results_photos/district_summary_refactored.png)

We can see that the average math score drops by .1%, the percent passing math drops by .2%, the percent passing reading drops by .3%, and the overall passing drops by .1%.

### School Summary

Here is the school summary:

![image_name](https://github.com/PirateSuit/School_District_Analysis/blob/main/results_photos/school_summary.png)

And here is the school summary refactored:

![image_name](https://github.com/PirateSuit/School_District_Analysis/blob/main/results_photos/school_summary_refactored.png)

In the refactor, the removal of the ninth grader's scores has caused the average math and reading scores at Thomas High School to drop by less than .1%, the percent passing math to drop by near .1%, and the percent passing reading to drop near one third a percentage point. The overall passing percentage dropped by .31%.

### School Performance Relative to Other Schools.

Here is a list of the top schools:

![image_name](https://github.com/PirateSuit/School_District_Analysis/blob/main/results_photos/top_schools.png)

And that same list, refactored:

![image_name](https://github.com/PirateSuit/School_District_Analysis/blob/main/results_photos/top_schools_refactored.png)

Thomas High School still sits in second place in a list of all schools, ranked by passing percentage, despite the removal of the flawed ninth grader data causing them to slip nearly one-third of a point, as mentioned above.

## How does replacing the ninth-grade scores affect the following:

  ### * Math and reading scores?
  
   It removes the ninth grade scores from Thomas High School and replaces them with NaN. All other scores from Thomas and other schools are unaffected.
    
  ### * Scores by school spending?
    
  Here are the scores by school spending:
   
   ![image](https://github.com/PirateSuit/School_District_Analysis/blob/main/results_photos/scores_by_spending.png)
  
  And here are the refactored versions of those scores:
  
   ![image](https://github.com/PirateSuit/School_District_Analysis/blob/main/results_photos/scores_by_spending_refactored.png)
   
  It appears that the scores have not changed in any way larger than a rounding error.
  
  ### * Scores by School Size?
  
   Here are the scores by school size:
   
   ![image](https://github.com/PirateSuit/School_District_Analysis/blob/main/results_photos/scores_by_school_size.png)
   
   And the refactored versions of those scores:
   
   ![image](https://github.com/PirateSuit/School_District_Analysis/blob/main/results_photos/scores_by_school_size_refactored.png)
   
   Like the scores by school spending, refactoring the data did not notably change the results.
   
  ### * Scores by School Type?
  
   Here are the scores by school type:
   
   ![image](https://github.com/PirateSuit/School_District_Analysis/blob/main/results_photos/scores_by_school_type.png)
   
   And the refactored scores:
   
   ![images](https://github.com/PirateSuit/School_District_Analysis/blob/main/results_photos/scores_by_school_type_refactored.png)
   
   Again, there is not notable change between the two.
   
   ## Summary
   
   * The removal of the Thomas High School ninth grader's data has caused a slight decrease in overall scores, which showed that the scores that we removed were above average. 
   
   * This is displayed via the specific decreases in math scores and math and reading (as well as overall) passing percentages in the summary of the entire district. 
   
   * We also see changes when we look solely at Thomas High School. Whereas the average drops in both reading and math are about .1%, the percentage of students passing reading, as well as the overall passing percentage drops by nearly .3%.

  * In a comparison to other schools, the removal of the ninth grader's scores did not knock Thomas High School from it's position as the school with the second highest overall passing percentage though, as mentioned above, it did drop that percentage by nearly .3%.

