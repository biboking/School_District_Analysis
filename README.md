# School_District_Analysis

## Overview of the Project
This project is to help Maria, a chief data scientist for a city school district, who was tasked with preparing all standard test data for analysis, reporting and presentation to provide insights about performance trends and patterns. The school board found some acdemic dishonesty in the students grades in this report, and they wanted Maria to update this report to uphold state-testing standards. 

We used panda in Python to help Maria audit this report. In the new report, we replaced the reading and Maths score of 9th Grade of Thomas High School to NaN. This change affected some of the results that were previously presented, with details listed below.

## Results: 

## The School District Summary

- Updated Summary
![districtsummaryafter](challenge_district_summary_after.png)

- Previous Summary
![districtsummarybefore](challenge_district_summary_before.png)
 
 - We can see from the two tables that the updated district summary has a slightly drop for Math, reading and overall passing rate. The Math passing rate dropped from 75.0% to 74.8%. The reading passing rate dropped from 85.8% to 85.7%. The overall passing rate dropped from 65.2% to 64.9%.
  - 
## The school summary 
- Previous school Summary
![schoolsummarybefore](challenge_per_school_summary_before.png)

- New School Summary
![schoolsummaryafter](challenge_per_school_summary_after.png)

- We can see from the comparison that Thomas High School's (THS) reading and math passing percentages had altered significantly after we took out the  (THS)'s 9th grade's scores

## Thomas High School VS other Schools
- How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?
- How does replacing the ninth-grade scores affect the following:
  - Math and reading scores by grade
  - Scores by school spending
  - Scores by school size
  - Scores by school type

## Summary: 

Summarize four changes in the updated school district analysis after reading and math scores for the ninth grade at Thomas High School have been replaced with NaNs.

- The replacement of the scores of the ninth grade of Thomas High School(THS) led to a decrease in the passing student number. So while the total student number has not changed, the percentage for math, reading and overall rate decreased. Although it did not change the average math and reading score, as NaNs will not be caculated.

