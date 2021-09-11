# School_Distric_Analysis

We help Maria create a summary data frame in which we calculate the total number of students in each school, we also analyze by type, budget, reading score and math score. Then we were able to understand what is the highest performance by school, how much money goes to each school, the average score in math and reading by grade, among other analyzes. To complete this process, we needed to clean the data and make sure everything was without any error so that our analysis could be reliable.

Unfortunately, Maria received a request from the School Board to replace the 9th grade Thomas High School scores for "Math" and "Reading" with NaN. While keeping the rest of the data intact and repeat the same analysis as previously done.

## Results

### 1. How is the district summary affected?
   
With the replacement of 9th grade scores to "NaN" for Thomas High School, the District Summary overall passing % was affected by a slight changes in the % Passing of Math, Reading & Overall. See details in next images:
   
- Old Dictric Summary
![old_Distric_Summary](https://user-images.githubusercontent.com/87447639/132947847-610ca4de-c62f-4f6c-bd84-39cafa8974c5.PNG)

- New Distric summary 

![New_Distric_Summary](https://user-images.githubusercontent.com/87447639/132947415-78cf0901-57a7-4415-b9e2-ea758777e30c.PNG)


### 2. How is the school summary affected?
   
The school summary was affected in Thomas High School with a slighly changes in the % Passing of Math, Reading & Overall. See details in next images:
   
- Old School Summary
![old_per_school_summary](https://user-images.githubusercontent.com/87447639/132947855-e7ba4d2a-3e0f-48c4-b8ae-d46596b1019a.PNG)



- New School summary 
![new_per_school_summary](https://user-images.githubusercontent.com/87447639/132948159-15ae8d07-f028-455e-b62d-3cde62763008.PNG)


### 3. How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?
  
  With the replacemente of 9th grade scores in Thomas Hight School, the school summary overrall passing %  was affected by:
 - % Passing Math from 93.27% to 93.18% 
  
 - % Passing Reading 97.30% to 97.01 % 
  
 - % Overall Passing from 90.94% to 90.63%

We can conclude that the replacement of the data of those 9th grade students did not alter the performance of the THS data since the changes in percentages were minimal. Decreased very little.

### 4. How does replacing the ninth-grade scores affect the following:
  
- Math and reading scores with the 9th replacing will now affect the average passing% for math, reading, and overall, because we need to calculate a new% based on the new number of students at Thomas Hight School. The code we used was:  

![new_student_count _9thTHS](https://user-images.githubusercontent.com/87447639/132948496-06ae4724-b875-486e-ae8f-5ec7c8212222.PNG)
![new_passing_perc_new_student_count](https://user-images.githubusercontent.com/87447639/132948488-00a8ceef-2cf1-40af-a236-884271e37e14.PNG)
![new_overall_passing_perc_new_count](https://user-images.githubusercontent.com/87447639/132948495-132d433d-8332-4c9c-b813-b142d7f88a20.PNG)

- Math scores replace in 9th grade for Thomas High School

![new_math_scores](https://user-images.githubusercontent.com/87447639/132948414-0eecf8e5-b831-450b-98c9-c492fcd1941f.PNG)

% Passing Math from 93.27% to 93.18% 

- Reading scores replace in 9th grade for Thomas High School

 ![new_reading_scores](https://user-images.githubusercontent.com/87447639/132948418-b2131403-fd5b-4382-8ef7-7dab93f4cad7.PNG)

% Passing Reading 97.30% to 97.01 % 

- Scores by school spending
  
  New Scores
  
  Old Scores
  
![old_score_school_spending](https://user-images.githubusercontent.com/87447639/132948379-0467f4f0-3df0-40ba-be86-9e87d0581f86.PNG)


- Scores by school size

  New Scores

  Old Scores
  
![old_score_school_size](https://user-images.githubusercontent.com/87447639/132948386-41663a5f-ba58-4f28-87eb-1da2f1ac39bf.PNG)

- Scores by school type

  New Scores

  Old Scores
  
 ![old_score_school_type](https://user-images.githubusercontent.com/87447639/132948389-f7be55b0-1304-4f10-be41-d2c35a9304f6.PNG)



## Summary

 Summarize four changes in the updated school district analysis after reading and math scores for the ninth grade at Thomas High School have been replaced with NaNs.

- 1 The overall percentage for Thosmas Hight school change from 90.94% to 90.63%
- 2 We had to calculate the passing percentages (for math & reading) with the new total count of students
- 3 
