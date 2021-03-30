# School District Analysis


### Resources

Data Source: "schools_complete.csv", "students_complete.csv", located here: https://github.com/MarielaKaradzhova/School_District_Analysis/tree/main/Resources

Software: Python 3.7.6,Jupyter Notebook 6.1.4

Link to the full code here: https://github.com/MarielaKaradzhova/School_District_Analysis/blob/main/PyCitySchools_Challenge.ipynb
### Overview of School District Analysis

THe purpose of this analysis was to clean the student data from the sources mentioned above, specifically for students in Grade 9 at Thomas High School. Many students entered prefixes such as [Dr. ", "Mr. ","Ms. ", "Mrs. ", "Miss ", " MD", " DDS", " DVM", " PhD"] before their first and last name, which in turn tampered the data and returned innacurate results.


In addition, it was important to note the changes in results from the raw data (see "Data Source") after the data was cleaned and organized into several data frames.

In particular, there are 4 main categories affected by the analysis as listed below:

1. Math and Reading Scores by Grade 
2. Scores by School Spending
3. Scores by School Size
4. Scores by Type of School

Below is a snippet of the District DataFrame created in this analysis. One major difference shown here is that Charter Schools yielded a higher higher overall passing percentage of students compared to District Schools. It is important to note that Thomas High School yielded the lowest overall passing percentage (65.1%) from all Charter Schools.

![](https://github.com/MarielaKaradzhova/School_District_Analysis/blob/main/Resources/District_Analysis_raw.png)
### Results

How is the district summary affected?

There are subtle differences in the district summary, in the %Overall Passing, % Passing Math, %Passing Reading columns due to formatting: 

1. Initial Analysis

![](https://github.com/MarielaKaradzhova/School_District_Analysis/blob/main/Resources/raw_school_summary.png)

2. Secondary Analysis (with formatting)

![](https://github.com/MarielaKaradzhova/School_District_Analysis/blob/main/Resources/formatted_district_summary.png)

How is the school summary affected?

How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?
How does replacing the ninth-grade scores affect the following:
Math and reading scores by grade
Scores by school spending
Scores by school size
Scores by school type





###Summary
Summarize four major changes in the updated school district analysis after reading and math scores for the ninth grade at Thomas High School have been replaced with NaNs.
1.
2.
3.
4.