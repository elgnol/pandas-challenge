# Pandas-Challenge

## Objective
Given two csv files of multiple schools' data that contains the school name, student name, budget, math and reading scores, school size, etc. Two data frames were created and merged together for the analysis. To find out the trend between these schools, we were tasked with finding the average math scores and reading scores per student, their budget, the overall reading and math scores of each schools. Additionall creating new data frames to be compared and look at to find these trends. 

## PyCity Schools Analysis
- Observation #1 :Students from charter school have a higher passing rate than those from district schools
- Observation #2: Students with higher spending seem to have a lower overall passing percentage. Most likely the high spending are from speding time going out having fun rather than studying like those students who had a lower spending. Also, students from charter schools seems to have a smaller budget than those from district schools.
- Observation #3: Schools that has a small to medium size amount of students seem to have a higher overall passing percentage. Charter schools overall have less students than district schools. And it seems that the grades that the students were in did not affect their passing percentages in both the reading and math category per school.
- Summary: Based on the data given, it seems that students who has a smaller spending budget and goes to charter school has a higher overall passing percentages in both the subjects of math and reading.

## Sources
Some codes were used with the help of ChatGPT and Xpert Learning Assistant such as:
- math_scores_by_grade = pd.concat([ninth_grade_math_scores, tenth_grader_math_scores,
                                  eleventh_grader_math_scores, twelfth_grader_math_scores],
                                 axis=1, keys=['9th', '10th', '11th', '12th']
                                )
- school_spending_df['Per Student Budget'] = school_spending_df['Per Student Budget'].str.replace('$', '')

