# School_District_Analysis
Jupyter Notebook 
## Overview of Project
Perform an analysis of the school district using Pandas to retrieve overall passing percentages for fifteen schools and setup up school spending bins based on school size.
## Results
* The district summary changed slightly by removing the ninth grade reading and math scores from Thomas High School. The overall passing scores were 65.17% and now it is 64.9%.

* Thomas High School had the reading score, math score, and overall score updated on the school summary dataframe.
[https://github.com/ninagoodwin88/School_District_Analysis/blob/main/PyCity1.png]
[https://github.com/ninagoodwin88/School_District_Analysis/blob/main/PyCity2.png]

* Replacing the ninth grade reading and math scores with NaN placed Thomas High School in the top five schools.
[https://github.com/ninagoodwin88/School_District_Analysis/blob/main/Top_5_schools.png]

* Replacing the ninth grade reading and math scores barely made a difference in math and reading scores by grade. The scores by school spending, school type, and school size rougly remained the same. The removal of ninth grade barely made one percent change in the scores listed above.
## Summary
Four changes that resulted in replacing the reading and math scores with NaN are the ninth grade reading and math scores have no value and are not calculated in the averages for Thomas High School. The averages for math and reading were re-calculated removing the ninth grade students from the student count and dividing the math and reading percentages by the new student count. Thomas High School was listed in the top five performing schools and it slightly lowered and the reading, math, and overall percentages were changed in the school summary.
