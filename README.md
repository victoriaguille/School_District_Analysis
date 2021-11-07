# School District Analysis
## Overview of School District Analysis
####
A school district employee, Maria, reached out to request an analysis of the school district's data using Python, Pandas, and Juypter Notebook. In this analysis, fifteen high schools, both charter and district, were compared to better understand what trends are occuring. Each school had gathered data based on grade levels, budget, and grades for their high school students within two CSV files. With the use of Python and Jupyter Notebook, dataframes were created to allow the school board to easily read the long strings of data with a quick glance. At the end of this initial process, it was discovered by the school board that the students_complete.csv file had evidence of academic dishonesty when reporting the grades of the ninth graders from Thomas High School. In order to still provide an analysis for the school board, those grades were replaced with "NaN" and the previous calculations refactored to include all of the true reporting only.
## School District Analysis Results
####
Below are the following findings from the analysis once the ninth graders' scores were replaced. 
* The district summary data frame had miniscule changes as this data frame looked at the whole of both CSV files. There is enough data amongst all of the other high schools to make up for the removal of fraudulent scores from one grade level in one school. The largest difference in scoring is .3%, as seen below. 
*****insert pre and post ds df pics
* The school summary data frame had the highest change, and only for one school, Thomas High School. The scores for the other high schools stayed the same from the previous analysis as Thomas High School was the only school to have any changes to their reporting. 
* Replacing the ninth graders' scores at Thomas High School with "NaN" made it so that roughly a fourth of the students' information no longer could be used for any averages or calculations. This meant that the overall percentages of Thomas High School were significantly boosted. At minimum, each percentage average for Thomas High School was increased by twenty-five percent from the original analysis. The averages of the reading and math score, however, remained in line with the rest of the high schools. removing the data for the ninth graders in thomas significantly boosts the overall percentages of thomas high by at minimum twenty-five percent from original data. In the below images, without the ninth graders' scores, Thomas High School looks like one of the top performing schools. 
******* insert pre and post ss df pics
* The math and reading scores by grade have little to no change when placed into an edited dataframe. The only difference that is seen is that there is now "NaN" in the 9th grade column for Thomas High School.  
* The scores by school spending dataframe also has little to no change with the new ninth-grade scores. This is due to the fact that the dollar amount per student stays the same, so spending per student has little impact to the overall picture being shown. 
* The scores by school size dataframe follows the trend of the district summary dataframe in that Thomas High School is labeled a medium school alongside a significant amount of other schools, making up for the loss of the ninth-grade scores. The size of the data is large enough to not be impacted by a lose in reporting of that size. 
* Much like the previous dataframe, the scores by school type is also not impacted. In the original analysis, the charter schools were the top performer compared to the district high schools. The large population size being compared in this dataframe makes up for the loss of the ninth-grade scores in one high school. 
## Summary
####
Prior to the discovery of the fraudulent grades, the analysis displayed a very different picture of Thomas High School. the different dfs provide different pictures from the data. prior to the discovery of the fraudulent grades, the data showed a very different picture for thomas high. removing the grades did little to impact the entire disctrict summary. on its own, removal of those grades skews the analysis of thomas high more positively. 
