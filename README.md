# School District Analysis

## Overview

After conducting a school district analysis, it was reported that academic dishonesty was discovered in the math and reading test scores of Thomas High School. Specifically, the scores for ninth graders were altered. As a result, the previous analysis must be adjusted by replacing the math and reading scores for the ninth grade students need to be replaced with "NaN" values and the analysis for the district rerun.

### Analysis Results
After replacing all of the ninth graders' scores with "NaN" (as shown below):

<img width="1112" alt="image" src="https://user-images.githubusercontent.com/95595378/154207358-2141e075-c8cc-47f6-99fb-d8431afd89e6.png">
<img width="783" alt="image" src="https://user-images.githubusercontent.com/95595378/154207515-912425af-4908-4b08-836f-c859b4ccf8d0.png">


the analysis was rerun. Since all of the ninth graders from Thomas High School had their scores replaced the particular focus of the analysis re-run was the focus on how this adjustment affected the school district analysis was altered. Primary areas of focus were:

Average math and reading scores at Thomas High School
Percentage of students passing according to math scores
Percentage of students passing according to reading scores
Overall percentage of students who passed both math and reading
Percentage passing math, reading, and overall by budget per student
Percentage passing math, reading, and overall by school size
Placement of schools overall by score values relative to each other

#### Reference metrics:

These are the screenshot images of the metrics before and after the Thomas High School alterations.

![image](https://user-images.githubusercontent.com/95595378/154209075-b6975037-033f-43b1-92a9-475093ecdc5e.png)

![image](https://user-images.githubusercontent.com/95595378/154208619-40719fdb-9b1d-4a81-bdb9-f73fb0e55739.png)

#### Total Students:

As the data adjustment affected the scores of the ninth-graders but did not remove them from the count of the school students, the total number of students in the district should not have been altered.

#### Total Budget:
As the data adjustment dealt with the scores of students and did not alter the budgets of schools, the total budget value remained unaffected by the data adjustment.

#### Average math and reading scores:

By effectively removing the ninth graders' scores, in should be noted that the average math exam score for the district dropped by one-tenth of a percentage point. The average score for the district on the reading exam was not altered.

#### Percentage of students passing according to math scores:

Following the data adjustment, it can be noted that the percentage of students passing the math exam was lowered by two-tenths of a percentage point following the adjustment.

#### Percentage of students passing according to reading scores:

Following the data adjustment, the resulting percentage of students in the district who passed the reading exam was dropped by three-tenths of a percentage point.

#### Overall percentage of students who passed both math and reading:

Due to the data adjustment of replacing the ninth graders' scores from Thomas High School with "NaN" values, the overall percentage of students who passed both the reading and math exam in the district dropped by one-tenth of a percentage point.

#### Summary:

Reviewing the analysis of the school district metrics after replacing the Thomas High School ninth-graders' scores with the value "NaN" yielded four noteable changes to the district metrics:

- The average math exam score for the district was one-tenth of a percentage point lower.

- The percentage of students who passed the math exam was lowered by two-tenths of a percentage point.

- The percentage of students who passed the reading exam was lowered by three-tenths of a percentage point.

- The percentage of students who passed both the math and reading exams for the districts was lowered by one-tenth of a percentage point.
