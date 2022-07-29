# School_District_Analysis
## Overview of the school district analysis: 
The purpose of this analysis was to cobine data regarding the schools, students, scores and budget. Through varios equations and syntax formats, the average scores for different schools and grade levels were inspected and manipulated in this case. 
### Deliverable 1 Purpose:
##### The purpose of this part of the assignment was to replace the ninth grade math and reading score data with NAN oonly for a single highschool. This would impact the data and as we dive deeper we are able to get a better veiw of the affect the impact of changing that data has on the rest of the datasets.
### Deliverable 2 Purpose:
##### This part of the assignment allows us to see the impact of the first deliverable on the school district level and allows us to compare ther schools data to the high school with replacement data.
---
## Results: Using bulleted lists and images of DataFrames as support, address the following questions.
### The District Summary
* The district summary affected is effected beacuse now it's list of student scores has students with "Nan" as there score because it was replaced in deliverable 1. This will impact the averages and calculations of scores from here on because we now do not know the true scores of those students. Below in a snippet of how the School District list was impacted and the new score averages of the overall school district because the NaN replaced the math and reading scores. 

![image](https://user-images.githubusercontent.com/105329532/181684302-e9dc7815-c585-45d1-acd0-4aa2a80dcdb0.png)

![image](https://user-images.githubusercontent.com/105329532/181683817-9674aeb6-58fa-46c9-809e-fac658b2c03d.png)
---
### The School Summary
* The school summary involves data relating to the school and per student budget which does not seem to have been largely impacted by the replacement of the score values from Thomas High School, however, both of the math, reading and overall passing percentages are relatively low and around the same range.
![image](https://user-images.githubusercontent.com/105329532/181685113-4c09be07-dd89-4cf0-a882-800ff6dea973.png)
---
### School Score Performance
* Replacing the ninth graders’ math and reading scores affected Thomas High School’s performance relative to the other school. Thomas High does not appear in the high performing school list like it did before the replaced data. Although it is not in the low performing, the performance record of the school has beeen impacted.
![image](https://user-images.githubusercontent.com/105329532/181687334-74574a61-e9db-420c-b98d-fc2618560031.png)
---
### Replacing the ninth-grade scores affect the following:
    * Math and reading scores by grade: The 9th grade score for reading and math is presented as        NaN in the list of math and reading score averges for each high schools level 9 students.
   
   ![image](https://user-images.githubusercontent.com/105329532/181687813-2d900c28-145f-4081-90d8-fd676b2e063e.png)
    
![image](https://user-images.githubusercontent.com/105329532/181688338-e7d22012-ad78-48de-8f05-95b6c6fdbb51.png)

![image](https://user-images.githubusercontent.com/105329532/181687835-c168d8bd-ee1a-4b5a-947e-76d5756666c0.png)

    * Scores by school spending: 
      Thomas Jefferson is at the bottom of the list for spending budget per student.
      
      ![image](https://user-images.githubusercontent.com/105329532/181690839-824bc48b-a2d4-420b-8c4b-7f435cca0080.png)

      ![image](https://user-images.githubusercontent.com/105329532/181689073-18aa70bf-2b2a-49f4-9948-13664725de38.png)
      
    * Scores by school size:
      ![image](https://user-images.githubusercontent.com/105329532/181691147-df61fdce-84a4-4678-bb5d-b06043d97259.png)
      ![image](https://user-images.githubusercontent.com/105329532/181691821-916df920-fd3d-4968-a825-ec53d7fb2942.png)

    * Scores by school type:
    ![image](https://user-images.githubusercontent.com/105329532/181691749-cd4d020c-07b6-4466-8a02-0196f100f408.png)

  ---
  ## Summary: 
  ### Four changes in the updated school district analysis after reading and math scores for the ninth grade at Thomas High School have been replaced with NaNs:
  
  * Thomas High School was no longer a top performing school like it was before the NaNs were in place.
  * The ninth grade students data could no longer really be compared to the other school's ninth graders by reading score because all of the the ninth graders at Thomas High School no longer had numerical data to use.
  * The ninth grade students data could no longer really be compared to the other school's ninth graders by math score for the same reasons due to them being replaced.
  * There are no ninth grade students within that are in the list of student who are passing math and readiing within Thomas High School because noe of them have a numerical grade. If the score was not replaced, there would be ninth graders in the passing list for Thomas High School.
