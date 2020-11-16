# School_District_Analysis


## Project Overview
The School Board has asked Maria to review the student data files "students_complete.csv" because the file shows evidence of academic dishonesty.
Apparently, the grades for the 9th graders may have been altered at Thomas High School.
We have been asked to replace the school's 9th grade scores with "NaNs", while keeping the rest of the data intact.
We will then re-analyze the data, based on the school district learning module, to identify how the 9th grade scores at Thomas High School affected
the overall analyis.

## Resources
- Data Source: schools_complete.csv, students_complete.csv
- Software: Python 3.6.1, junyper notebook

## Results

### How is the district summary affected?
The chart below shows the original district summary.
![Graph](/Resources/District_Summary_Old.PNG)


And this chart show the new district summary after the exclusion of the 9th grade scores from Thomas High School
![Graph](/Resources/District_Summary_New.PNG)

After excluding the 9th grade data from Thomas High School:
We see that the average math score for the district dropped by 0.1%.
That the average reading score was unchanged.
That the percent of students passing math fell by 0.2%.
That the percent of students passing reading fell by 0.1%.
That the percent of students passing both math and reading fell by 0.3%

Based on the data above, we can conclude that the District Summary is not severly affected by the exclusion of the 9th grade data from Thomas High School.


### How is the school summary affected?

The chart below shows the original school summary.
![Graph](/Resources/School_Summary_Old.PNG)

And this chart below show the new school summary.
![Graph](/Resources/School_Summary_New.PNG)

The school summary is significantly affected by the exclusion of the 9th grade data.
The overall passing rate in the original data set is 65.1%.
With the exclusion of the original data, the overal passing rate jumps up to 90.6%.

### How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?

In the original analysis, Thomas High School was ranked second based on the % Overall Passing.
This remained unchanged after 9th grade data exclusion.


###  How does replacing the ninth-grade scores affect the following:
- Math and reading scores by grade.
The math and reading scores by grade are unaffected.

-Scores by school spending.
The scores by school spending are unaffected.

-Scores by school size.
The scores by school size are unaffected.

-Scores by school type.
The scores by school type are unaffected.


### Summary
There were no major changes observed by the exclusion of the 9th grade data from Thomas High School.
