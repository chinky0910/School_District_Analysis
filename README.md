School_District_Analysis_Challenge

Purpose

A school district asked for a snapshot of several key metrics by each school campus and by the district level. The main analysis focused on the performance of math and reading scores disaggregated several ways in preparation for a board meeting. However, after the school board reviewed the data, it was determined that the data from Thomas High School's 9th grade class was suspect of cheating. The school board asked for the data to be removed and analyzed again for a comparison.

Results

How is the district summary affected?
BEFORE DATA CLEANUP
Average Math Score, Average Reading Score, % Passing Math, % Passing Reading, % Overall Passing
79.0, 81.9, 75, 86, 65
AFTER DATA CLEANUP
Average Math Score, Average Reading Score, % Passing Math, % Passing Reading, % Overall Passing
78.9, 81.9, 74, 85, 64
OBSERVATION: Slight downward change in district averages

How is the school summary affected?
BEFORE CLEANUP: Thomas High School's % Overall Passing = 91, placing second
AFTER CLEANUP: % Overall Passing = 65, placing eighth!
OBSERVATION: Overall ranking order change due to THOMAS HS, which slipped from 2ND to 13TH position, with the other intervening schools moving up.

How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance, relative to the other schools?
OBSERVATION: Relative ranking for THOMAS HS changed from 2ND to 8TH, as it's % OVERALL PASSING number decreased from 91% to 65%.

How does replacing the ninth-grade scores affect the following?

Math and Reading Scores by Grade
Thomas HS 9th grade math & reading scores set to "nan" and equivalent to 0
Totals for passing math & reading across grades are reduced as all of 9th grade scores are equivalent to failing
Average scores calculation not significantly affected by removal of 9th grade scores, seems due to count() function NOT including 9th grade scores = nan
Cacluate number of students with a math grade - use "student_school_math.groupby(["school_name"]).count()""

BEFORE cleanup: Thomas High School 1635
AFTER cleanup: Thomas High School 1174
"%age passing" score is reduced as Total number of students (denominator) remains unchanged, but total passing value (numerator) is reduced by the number of removed 9th grade scores.

Scores by School Spending
Thomas HS is in the spending bucket "$630-644"
Removing 9th grade scores reduces the "% Passing Math", "% Passing Reading" and "% Overall Passing" scores for spending bucket "$630-644" as follows
BEFORE: 73, 84, 63
AFTER: 67, 77, 56

Scores by School Size
Thomas HS is in the "Medium (1000-2000)" size bucket
Removing 9th grade scores reduces the "% Passing Math", "% Passing Reading" and "% Overall Passing" scores for size bucket "Medium (1000-2000)" as follows
BEFORE:94, 97, 91
AFTER: 88, 91, 85

Scores by School Type
Thomas HS is in the "CHARTER" type bucket
Removing 9th grade scores reduces the "% Passing Math", "% Passing Reading" and "% Overall Passing" scores for type bucket "CHARTER" as follows
BEFORE:94, 97, 90
AFTER: 90 93 87

Summary: 

Summarize four major changes in the updated school district analysis after reading and math scores for the ninth grade at Thomas High School have been replaced with NaNs.
1.	The overall passing rate for Thomas High School changed dramatically from 91% to 65%.
2.	Thomas High School's ranking dropped from 2nd to 8th in the district of 15 campuses.
3.	Data at the grade level will now show as "NaN" in reports for the 9th grade students at Thomas High School
4.	In addition to the overall passing rate, the campus math and reading averages and passing percentages all saw shifts.
