# School_District_Analysis

## Overview

  Maria has asked me to complete an analysis on the school district she currently works at, and wants me to demonstrate how replacing specific scores will affect the orginal analysis. There has been some academic dishonesty concerning Thomas High School 9th graders, so we were asked to replace some of the scores to provide a more accurate analysis of the overall school district. Below, I will demonstrate the changes before/after replacing the scores with the use of pandas and numpy libraries. Stay tuned for the comparisons.

## Results 

1: How is the district summary affected?
 
    Suprisingly, we only see a 0.1% drop in avg math scores between the two results.
   
   ![Image 12-13-20 at 10 23 PM](https://user-images.githubusercontent.com/74481469/102047309-e2d38f80-3d91-11eb-9457-001f7dbf1a8f.jpeg)

2: How is the school summary affected?

    Obviously, the only changes we see here are a drop off in Thomas High School statistics.
    
   ![Image 12-13-20 at 10 27 PM](https://user-images.githubusercontent.com/74481469/102047825-ce43c700-3d92-11eb-98b7-91e9d36b8f97.jpeg)
   
![Image 12-13-20 at 10 29 PM](https://user-images.githubusercontent.com/74481469/102047858-e3b8f100-3d92-11eb-85d7-9e630435d015.jpeg)

3: How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?

     As shown, Thomas High School's scores fell after replacement, dropping them from 4th overall in the district, to 7th.
    
4: How does replacing the ninth-grade scores affect the following:
  
  Math and reading scores by grade:
  
      Thomas High School 9th graders' scores were replaced with NaN, and this is the only change in data.
      
   ![Image 12-13-20 at 10 45 PM](https://user-images.githubusercontent.com/74481469/102049004-f2080c80-3d94-11eb-953b-ef5c2b2a324c.jpeg)
   ![Image 12-13-20 at 10 46 PM](https://user-images.githubusercontent.com/74481469/102049384-99853f00-3d95-11eb-8128-6b01fe087297.jpeg)


  Scores by school spending:
  
       Since Thomas High School falls in the ($630 to $644) bin, we saw a drop in overall passing percentage, as seen below.
       
   ![Image 12-13-20 at 10 49 PM](https://user-images.githubusercontent.com/74481469/102049331-83777e80-3d95-11eb-9b0e-bc1923bd8293.jpeg)

  Scores by school size:
  
      Since THS falls in the (1000 to 2000) school size bin, we saw a drop off from 91% to 85% in this specific bin.
      
   ![Image 12-13-20 at 10 54 PM](https://user-images.githubusercontent.com/74481469/102049663-292aed80-3d96-11eb-82fe-06a5c0068d7f.jpeg)
      

  Scores by school type:
  
      Since THS is a charter school, we saw a drop off in overall passing percentage in this category from 90% to 87%. 

   ![Image 12-13-20 at 10 56 PM](https://user-images.githubusercontent.com/74481469/102049801-6becc580-3d96-11eb-9777-6af93603db16.jpeg)

## Summary 

1: Clearly, there is a huge drop-off in competitiveness with Thomas High School, once the 9th grade scores are dropped, compared to other charter schools.

2: The 9th grade overall district scores decreased once we stripped the Thomas High School 9th grade data.

3: The District summary DF is pretty identical, other than when looking at Thomas High School.

4: The decrease in passing percentage wasn't as drastic as you would expect, as the 10th-12th graders maintained succesfull passing percentages, which helped with the overall school performance.
