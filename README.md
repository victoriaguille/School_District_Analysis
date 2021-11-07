# School District Analysis
## Overview of School District Analysis
####
A school district employee, Maria, reached out to request an analysis of the school district's data using Python, Pandas, and Juypter Notebook. In this analysis, fifteen high schools, both charter and district, were compared to better understand what trends are occuring. Each school had gathered data based on grade levels, budget, and grades for their high school students within two CSV files. With the use of Python and Jupyter Notebook, dataframes were created to allow the school board to easily read the long strings of data with a quick glance. At the end of this initial process, it was discovered by the school board that the students_complete.csv file had evidence of academic dishonesty when reporting the grades of the ninth graders from Thomas High School. In order to still provide an analysis for the school board, those grades were replaced with "NaN" and the previous calculations refactored to include all of the true reporting only.
## Results
####
* changes made in district summary are miniscule. enough data amongst all schools to make up for the removal of fraudulent grades from one grade level in one school. (insert comparison images). 
* breaking data down by school only impacts thomas high, everyone else has the same percentages. nothing changed for the school summary outside of thomas high. 
* removing the data for the ninth graders in thomas significantly boosts the overall percentages of thomas high by at minimum twenty-five percent from original data. averages remain in line with the rest of the schools. w/out 9th grade, thomas high looks like one of the top performing schools. (insert image)
* math and reading scores by grade have little to no impact in total. only difference is now there is "nan" in the 9th grade column for thomas high. 
* amount per student stays the same, so spending per student has little impact
* thomas high is a medium school, enough data to make up for the 460ish students' scores removed to not effect the data
* school type not impacted. same as above, plus charter schools were larger anyways
## Summary
####
the different dfs provide different pictures from the data. prior to the discovery of the fraudulent grades, the data showed a very different picture for thomas high. removing the grades did little to impact the entire disctrict summary. on its own, removal of those grades skews the analysis of thomas high more positively. 
