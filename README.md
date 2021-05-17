# School District Analysis

## Report Overview
### Background
This report was prepared at the request of Maria, Chief Data Scientist at City School System, in order to uncover performance trends and patterns that will inform strategic decisions made by the School Board. 

### Resources
The dataset consists of school funding data for 15 high schools in the school system as well as students’ standardized test scores in math and reading.

### FERPA Compliance 
In order to ensure that confidential student data is secure in the preparation of this report, all analysis was performed in .ipynb files, which cannot be easily read within a typical text editor.

## Results
### Uncovering Academic Dishonesty
This report uncovered evidence of reading and math grades having been altered for ninth graders at Thomas High School. In order to uphold state testing standards, these scores have been disgarded, and summary statistics for the district and for Thomas High School have been adjusted with the removal of the phony scores.


### Impact on Metrics
------------------------	
<img width="500" alt="Dist_Summary_Before" src="https://user-images.githubusercontent.com/82285562/118418339-b0e69200-b67d-11eb-97dc-4ac23140b250.png">
	
*District Summary Before*
	
<img width="500" alt="Dist_Summary_After" src="https://user-images.githubusercontent.com/82285562/118418352-bcd25400-b67d-11eb-9a9d-1f7dc73613ba.png">
	
*District Summary After*

**School District**

With the removal of ninth grade scores from Thomas High School, there was a slight (<0.2%) decrease in the passing percentage for Math, Reading, and Overall.

--------------------

	
<img width="500" alt="Top_Schools_Before" src="https://user-images.githubusercontent.com/82285562/118418367-c956ac80-b67d-11eb-9ac2-3d952259f93b.png">
	
*Top Schools Before*
	
<img width="500" alt="Top_Schools_After" src="https://user-images.githubusercontent.com/82285562/118418369-cbb90680-b67d-11eb-9180-2e97eaf846af.png">
	
*Top Schools After*


**School Summary**	
- Thomas High School average scores for both Math decreased slightly. 
- The average score for Reading increased slightly. 
- The Overall passing percentage dropped from 90.95% to 90.63%.
- The removal of the ninth graders’ scores does not affect Thomas High School’s performance relative to other schools — With the removal, it is still ranked second.

------------------------

**Additional Impacts**
- Math and reading scores by grade
	- Thomas High School no longer is the best-performing school in 9th grade Math.
- Scores by school spending
	- Unchanged
- Scores by school size
	- Unchanged
- Scores by school type
	- Unchanged

## Summary
There were four major changes with the removal of the Thomas High School ninth grade math and reading scores:
1. District metrics in math, reading, and overall passing percentages decreased slightly, by <0.2%.
2. Average math score at Thomas High School decreased from 83.42% to 83.35%.
3. Average reading score at Thomas High School increased from 83.85% to 83.90%
4. Overall at Thomas High School decreased from 90.95% to 90.63%.
