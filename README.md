# School_District_Analysis
Analysis of School grading data to make informed decisions for the budget.

## Overview of the school district analysis:
An analysis of the schools grading data was done to make informed decisions with respect to the budget by the PyCity School board. But, it was discovered that there was academic dishonesty with respect to reading and math grades of 9th grade students from Thomas High School. So, the board wants this data replaced with NaNs and have the analysis done again to see how this affects the overall analysis.

## Results: Using bulleted lists and images of DataFrames as support, address the following questions.
### 1. How is the district summary affected?
   Generally, grade averages are usually formatted to one decimal place because averages taken to the hundredths (range: 0.01–0.09) or lower do not impact an average as much as tenths of a grade point, (range: 0.1–0.9). Similarly, grade percentages are formatted to the whole percentage because the tenths of a percent is equivalent to thousandths of a value, or grade. This is because, like averages, thousandths of a grade don't have an impact on the overall percentage because they are so small.
   
   Looking the output summary below, it looks there is **very small** change between the two outputs.
    
   **District Summary for complete Dataset:**
   ![District Summary Complete Dataset](Resources/District_Summary_Complete_Dataset.PNG)
   
   **District Summary after replacing Thomas High School's 9th grade students scores with NaNs:**
   ![District Summary with NaNs](Resources/District_Summary_with_NaNs.PNG)

### 2. How is the school summary affected?
   As you can see below, only Thomas High School's data is affected by replacing the 9th grade scores with NaNs. The percentages are heavly impacted but the averages are affected only to the tenth decimal place.
   
   **School Summary Complete Dataset:**
   ![School Summary Complete Dataset](Resources/School_Summary_Complete_Dataset.PNG)
   
   **School Summary after replacing Thomas High School's 9th grade students scores with NaNs:**
   ![School Summary with NaNs](Resources/School_Summary_with_NaNs.PNG)
   
   But, the percentages improve once the 9th grade students' scores are excluded from the calculations as seen in the below screenshot.
   
   **School Summary after ignoring Thomas High School's 9th grade students scores:**
   ![THS School Summary without 9thGradeData.PNG](Resources/THS_School_Summary_without_9thGradeData.PNG) 
   

3. How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?
    As seen in the above screenshot the performance of Thomas High School **goes down significantly** when we include the 9th grade students data with the scores replaced with NaNs. But, if we ignore the 9th grade students records completely then the performance is not 


5. How does replacing the ninth-grade scores affect the following:
   - Math and reading scores by grade
   - Scores by school spending
   - Scores by school size
   - Scores by school type

# Summary: 
Summarize four changes in the updated school district analysis after reading and math scores for the ninth grade at Thomas High School have been replaced with NaNs.
