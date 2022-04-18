# School_District_Analysis


## Overview of Analysis

During this review I did an entire analysis of a School District including a district summary, a school by school summary, the top 5 performing schools and the bottom 5 performing schools, the average math and reading scores for each grade level, the scores by school spending per student, the scores by school size, and the scores by school type. The school board also has evidence of academic dishonesty for the math and reading grades for Thomas High School, so part of this analysis includes removing those values and updating the overall percentages for that school to only include 10th - 12th grade scores. 

## Results

### How is the district summary affected?

After updating and removing the 9th graders values, the overall district summary was not really affected. This is likely the case because the analysis of the School District includes data for 39,170 total students and the 9th graders of Thomas High School play a small part in that. 

![Updated_DS](https://github.com/ericajini/School_District_Analysis/blob/main/Pictures/District%20Summary.png)


### How is the school summary affected?

After replacing the 9th graders scores to NaN, the school summary is greatly affected. Thomas High School drops out of the top 5 schools. 

![Updated_DS](https://github.com/ericajini/School_District_Analysis/blob/main/Pictures/Replacing%209th%20grade%20scores_NaN.png)

When removing the scores for the 9th graders and only including the 10th-12th graders, Thoms High School shoots back up into the top 5. 

![Updated_DS](https://github.com/ericajini/School_District_Analysis/blob/main/Pictures/Removing%209th%20grade%20scores.png)

![Updated_DS](https://github.com/ericajini/School_District_Analysis/blob/main/Pictures/Top%205%20Performing%20Schools.png)

### How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?

When replacing the 9th graders scores, the math and reading percentages of students that pass go down to 66.9% and 69.7%. The overall percentage of students passing goes to 65.1%. 

After removing the 9th grade scores and only including 10th - 12th graders scores for Thoms High School, the percentage of students passing math and reading go to 93.2% and 97%. The overall percentage of students passing goes to 90.6%. 

1. Math and reading scores - 66.9% and 69.7% to 93.2% and 97%
2. Scores by school spending - 

![Updated_DS](https://github.com/ericajini/School_District_Analysis/blob/main/Pictures/Scores%20by%20School%20Spending.png)

3. Scores by school size - 

![Updated_DS](https://github.com/ericajini/School_District_Analysis/blob/main/Pictures/Scores%20by%20School%20Size.png)

4. Scores by school type - 

![Updated_DS](https://github.com/ericajini/School_District_Analysis/blob/main/Pictures/Scores%20by%20School%20Type.png)

## Summary 
