# School_Distric_Analysis

We help Maria create a summary data frame in which we calculate the total number of students in each school, we also analyze by type, budget, reading score and math score. Then we were able to understand what is the highest performance by school, how much money goes to each school, the average score in math and reading by grade, among other analyzes. To complete this process, we needed to clean the data and make sure everything was without any error so that our analysis could be reliable.

Unfortunately, Maria received a request from the School Board to replace the 9th grade Thomas High School scores for "Math" and "Reading" with NaN. While keeping the rest of the data intact and repeat the same analysis as previously done.

## Results

### 1. How is the district summary affected?
   
With the replacement of 9th grade scores to "NaN" for Thomas High School, the District Summary overall passing % was affected by a slightly changes in the % Passing of Math, Reading & Overall. See details in next images:
   
- Old Dictric Summary
![old_Distric_Summary](https://user-images.githubusercontent.com/87447639/132947847-610ca4de-c62f-4f6c-bd84-39cafa8974c5.PNG)

- New Distric summary 

![New_Distric_Summary](https://user-images.githubusercontent.com/87447639/132947415-78cf0901-57a7-4415-b9e2-ea758777e30c.PNG)

% Overall Passing changed from 65.17% to 64.9%

### 2. How is the school summary affected?
   
The school summary was affected in Thomas High School with a slighly changes in the % Passing of Math, Reading & Overall.  See details in next images:
   
- Old School Summary
![old_per_school_summary](https://user-images.githubusercontent.com/87447639/132947855-e7ba4d2a-3e0f-48c4-b8ae-d46596b1019a.PNG)



- New School summary 
![new_per_school_summary](https://user-images.githubusercontent.com/87447639/132948159-15ae8d07-f028-455e-b62d-3cde62763008.PNG)


### 3. How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?
  
  With the replacemente of 9th grade scores in Thomas Hight School, the school summary overrall passing %  was affected by:
 - % Passing Math from 93.27% to 93.18% 
  
 - % Passing Reading 97.30% to 97.01 % 
  
 - % Overall Passing from 90.94% to 90.63%

We can conclude that replacing the data for those 9th graders altered the performance of the THS data very little, since the changes in the percentages were minimal.

### 4. How does replacing the ninth-grade scores affect the following:
  
- Math and reading scores with the 9th replacing will now affect the average passing % for math, reading, and overall, because we need to calculate a new % based on the new number of students at Thomas Hight School. The code we used was:  

![new_student_count _9thTHS](https://user-images.githubusercontent.com/87447639/132948496-06ae4724-b875-486e-ae8f-5ec7c8212222.PNG)
![new_passing_perc_new_student_count](https://user-images.githubusercontent.com/87447639/132948488-00a8ceef-2cf1-40af-a236-884271e37e14.PNG)
![new_overall_passing_perc_new_count](https://user-images.githubusercontent.com/87447639/132948495-132d433d-8332-4c9c-b813-b142d7f88a20.PNG)

- Math scores replace in 9th grade for Thomas High School NaN for ninth grade and the rest of the data remained exactly the same
![new_math_scores](https://user-images.githubusercontent.com/87447639/132948414-0eecf8e5-b831-450b-98c9-c492fcd1941f.PNG)

Results for Thomas High School: % Passing Math changed from 93.27% to 93.18% 

- Reading scores replace in 9th grade for Thomas High School NaN for ninth grade and the rest of the data remained exactly the same

 ![new_reading_scores](https://user-images.githubusercontent.com/87447639/132948418-b2131403-fd5b-4382-8ef7-7dab93f4cad7.PNG)

Results for Thomas High School: % Passing Reading changed 97.30% to 97.01 % 

- Scores by school spending

![code_spending](https://user-images.githubusercontent.com/87447639/132988249-cf36965f-92fd-4a96-85cb-59f345c7a715.PNG)

   
![old_score_school_spending](https://user-images.githubusercontent.com/87447639/132948379-0467f4f0-3df0-40ba-be86-9e87d0581f86.PNG)

The changes in ninth-grade scores did not affect the scores by school spending. 

- Scores by school size
![code_schoolsize](https://user-images.githubusercontent.com/87447639/132988243-5ef5ada5-c7fa-4106-aeb0-fc8916ce1d9c.PNG)

    
![old_score_school_size](https://user-images.githubusercontent.com/87447639/132948386-41663a5f-ba58-4f28-87eb-1da2f1ac39bf.PNG)

The changes in ninth-grade scores did not affect the scores by school size. 


- Scores by school type

![code_schooltype](https://user-images.githubusercontent.com/87447639/132988246-21e88657-fc93-461d-ac32-da79a12d68be.PNG)


![old_score_school_type](https://user-images.githubusercontent.com/87447639/132948389-f7be55b0-1304-4f10-be41-d2c35a9304f6.PNG)


The changes in ninth-grade scores did not affect the scores by school type.


## Summary

 After we help Maria, we can summarize four changes in the updated school district analysis after reading and math scores for the ninth grade at Thomas High School have been replaced with NaNs.

- In the Dictrict Summary performance the total % Overall Passing changed from 65.17% to 64.9%
- Fot Thomas High School the overall percentage changed from 90.94% to 90.63%, has decreased slighty. 
- We had to calculate the new passing percentages (for math & reading in THS) with the new total count of students.
   - Results for Thomas High School: % Passing Math changed from 93.27% to 93.18%. 
   - Results for Thomas High School: % Passing Reading changed 97.30% to 97.01 % 
- The scores by school spending, school size and school type remained the same, becasuse we need to calculate thems with the same amount of total studend regardless their scores in math and reading. 
