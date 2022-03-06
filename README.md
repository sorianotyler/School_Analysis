# School_Analysis
Python program to analyze School Distric data

## Overview of Project
 The objective of this project is to help sumarize the School Distric data for our client Maria. We had already collected and summarized the entirety of the Data. However, there was academic dishonesty with one school in particular that would have sku'd the results. 
### Purpose
    The purpose of this challenge was to use python to remove the nulled scores while keeping the rest of the dataset intact and run a full analysis of the new results.

 
## Results 
- The District summary was changed very minimally by the omission of Thomas Highschool 9th graders. It looks like the overal passing might have dropped .3% points 

- Since we purged the Thomas High School data from all of the 9th grade scores, the percetages of passing math, reading, and overall passing were significantly lowered (66%, 69%, 65% repspectively). However, when we calculate the new total students(omitting all of the 9th graders) we end up with scores of 93%, 97%, and 90% respectively. This cleaned the data and gave a more accurate picture of thomas high. 

- Replacing the ninth graders' reading and math scores signficantly lowered their performace relative to other schools. Without the ommited 9th grade scores they would be placed in the top 5 schools. However, with the 9th grade score change, they were landing in the bottom 5

- Replacing the ninth-grade scores affect the following:
    - Math and reading scores for 9th grade were not present, and therefore we were not able to draw conclutions on it. However, all of the other data remained unchanged
    - Score by school spending decreases - with the change in new average scores came a change in their score by school spending ( Spending remained the same)
        - Score by school spending decreases after omitting 9th graders from the analysis increases
    - Score by school size decreases - with the change in new average scores came a change in their score by school size (size remained the same)
        - Score by school size after omitting 9th graders from the analysis increases
    - Score by school type decreses - with the change in new average scores came a change in their score by school size (size remained the same)
        -  - Score by school type after omitting 9th graders from the analysis increases
   
## Summary 
By replacing the ninth graders' reading and math scores you see a slight decrease in the overal pass percentage. You also see an substantial decrease in performance realtive to other schools, no average test scores for 9th graders, and overall lower test scores. If we were to omit the 9th graders from the anlysis completely we see a converse reaction where Thomas High is in the top 5 schools in the district. 


