# School District Analysis with Jupyter Notebook and Python

## Overview of the project
 
  Maria and her supervisor analyze the student performance (Math and Reading) and investigate the budget for each student/school for this specific school district. In this challenge, we will take out the ninth graders’ math and reading scores and see how this action impact the overall performance of the school district.

### Results

* How is the district summary affected?  
When we calculate the total school and total student, we apply count() function and these two numbers are the same as module. However, when we calculate the student performance, the count for the students will ignore the NaN from the ninth graders. So, except % Passing Math and % Overall passing, other stats are slightly a little bit higher than original numbers. See below screenshot 1 or original and screenshot 2 for the modified numbers from removing the ninth graders.

**Original**

![Original](https://github.com/jkmom/PyCitySchool_Challenge4/blob/main/Resources/district%20summary_original.png)

**After remove 9th graders**

![modified](https://github.com/jkmom/PyCitySchool_Challenge4/blob/main/Resources/district_summary_modified.png)

* How is the school summary affected?
Except Average Reading Score is higher than the original. Other performances are slightly lower (around 0.03%)

**Original**

![Original](https://github.com/jkmom/PyCitySchool_Challenge4/blob/main/Resources/school_summary_original.png)

**After remove 9th graders**

![modified](https://github.com/jkmom/PyCitySchool_Challenge4/blob/main/Resources/district_summary_modified.png)


* How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?
Thomas High School remain second place after remove the 9th graders. The overall passing % dropped from 90.94% to 90.63%. But still higher than #3.
* How does replacing the ninth-grade scores affect the following?
__Math and reading scored by grade__: Because math and reading scores are calculated independently from 9th grader. To other grades in Thomas High School, there is no difference from original module.
**Scores by school size**: Thomas High School belongs to the group “Medium”. So, the performances for group “Medium” are all slightly lower (around 0.05%). For groups “Small” and “Large”, the performances stay the same.
**Scores by school spending**: Same as above (school size). The performance will be slightly lower with the group (631-645) which has Thomas High school.  
**Scores by school type**: Thomas High School belongs to Charter school. So again, the Charter school performances are slightly lower than originally module. District school performances stay the same.
### Summary
The major changes are: 
* The performances overall passing% decreased.
* The spending group (631-645) performance decreased.
* The school size group “Medium” performance decreased.
* The school type (Charter) performance decreased.




 





	



