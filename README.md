# School_District_Analysis
Analyzing school district data

## Overview: 
The school board was notified that the reading and math grades for Thomas High School ninth graders appear to have been altered showing evidence of academic dishonesty. In order to uphold state-testing standards, this project has replaced the math and reading scores for Thomas High School with NaNs while keeping the rest of the data intact. The school district analysis was then repeated with the updated data set. The following analysis describes the results and how the replacement of Thomas High School 9th graders scores with NaNs affected the overall school distric analysis.

## Results: 

### How is the district summary affected?
  - Original District Summary
  
  ![OG_district_summary.png](https://github.com/ashleycvirga/School_District_Analysis/blob/66098b866d201f14665b1c82aa5e1785e3c7fc0e/Resources/OG_district_summary.png)
  
  - Updated Distric Summary
  
  ![update_district_summary.png](https://github.com/ashleycvirga/School_District_Analysis/blob/66098b866d201f14665b1c82aa5e1785e3c7fc0e/Resources/update_district_summary.png)
  
#### Replacing the THS 9th grader's scores with NaN values resulted in:
* 0.2% drop in the percentage of students passing math
* 0.1% drop in the percentage of students passing reading
* 0.3% drop in the school districts overall passing rate.
* average math and reading scores for all district students remained unchanged

### How is the school summary affected?
  - Original School Summary
  
  ![OG_Summary_Stats.png](https://github.com/ashleycvirga/School_District_Analysis/blob/e18ef213945aee4d1e9cc5973766611f65a4e1be/Resources/OG_Summary_Stats.png)
  
  - Updated School Summary
  
  ![Updated_Summary_Stats.png](https://github.com/ashleycvirga/School_District_Analysis/blob/66098b866d201f14665b1c82aa5e1785e3c7fc0e/Resources/Updated_Summary_Stats.png)
  
  - Thomas High School Summary without dishonest data or NaN values
  
  ![THS_OG_summary.png](https://github.com/ashleycvirga/School_District_Analysis/blob/838ab7f9faec4d17535df4864e49d295f6415463/Resources/THS_OG_summary.png)

#### Differences Observed
* THS shows a 0.1% drop in the percentage of students passing math, a 0.3% drop in the percentage of students passing reading, and a 0.3% drop in the school districts overall passing rate by replacing dishonest 9th grade scores with NaN values.
* Had we replaced the dishonest data with "0" values:
    * The percentage of THS students passing math would have decreased from 93.2% to 66.9% (-26.3% change)
    * The percentage of THS students passing reading would have decreased from 97% to 69.7% (-27.3% change)
    * The overall passing rate of THS students would have decreased from 90.6% to 65.1% (-25.5% change)
* average math and reading scores of THS students remained unchanged 

### How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?
  - Original School Ranking
  
  ![OG_top_schools.png](https://github.com/ashleycvirga/School_District_Analysis/blob/f31e1817dba4e5106b08496f57ab285f6c5edddc/Resources/OG_top_schools.png)
  
  - Updated School Ranking
  
  ![top_five_schools.png](https://github.com/ashleycvirga/School_District_Analysis/blob/66098b866d201f14665b1c82aa5e1785e3c7fc0e/Resources/top_five_schools.png)

  - Thomas High School's #2 position in the district remained unchanged. 

### How does replacing the ninth-grade scores affect the following:

  - Math and reading scores by grade
  
    * Original Average Math & Reading Scores by Grade
    
    ![OG_math_by_grade.png](https://github.com/ashleycvirga/School_District_Analysis/blob/838ab7f9faec4d17535df4864e49d295f6415463/Resources/OG_math_by_grade.png)
    ![OG_reading_by_grade.png](https://github.com/ashleycvirga/School_District_Analysis/blob/838ab7f9faec4d17535df4864e49d295f6415463/Resources/OG_reading_by_grade.png)
    
    * Updated Average Math & Reading Scores by Grade
    
    ![avg_math_scores_by_grade.png](https://github.com/ashleycvirga/School_District_Analysis/blob/f31e1817dba4e5106b08496f57ab285f6c5edddc/Resources/avg_math_scores_by_grade.png)
    ![avg_reading_scores_by_grade.png](https://github.com/ashleycvirga/School_District_Analysis/blob/f31e1817dba4e5106b08496f57ab285f6c5edddc/Resources/avg_reading_scores_by_grade.png)

    * Average Math & Reading Scores by grade were not affected by removing dishonest data --Albeit the THS 9th grade score now replaced by a "NaN" value.
   
  - Scores by school spending
    * Original Scores by school spending
    
    ![OG_spending.png](https://github.com/ashleycvirga/School_District_Analysis/blob/9b2a40d4bdb12b1ca88fab05418d06142d2ca01c/Resources/OG_spending.png)
    
    * Updated Scores by school spending
    
    ![spending_summary.png](https://github.com/ashleycvirga/School_District_Analysis/blob/f31e1817dba4e5106b08496f57ab285f6c5edddc/Resources/spending_summary.png)
    
    * Scores by school spending remains unchanged.
    
  - Scores by school size
    * Original Scores by school size
    
    ![OG_school_size.png](https://github.com/ashleycvirga/School_District_Analysis/blob/9b2a40d4bdb12b1ca88fab05418d06142d2ca01c/Resources/OG_school_size.png)
    
    * Updated Scores by school size
    
    ![school_size_summary.png](https://github.com/ashleycvirga/School_District_Analysis/blob/f31e1817dba4e5106b08496f57ab285f6c5edddc/Resources/school_size_summary.png)

    * Scores by school size was not significantly affected.

- Scores by school type
    * Original Scores by school type
    
    ![OG_school_type.png](https://github.com/ashleycvirga/School_District_Analysis/blob/9b2a40d4bdb12b1ca88fab05418d06142d2ca01c/Resources/OG_school_type.png)
    
    * Updated Scores by school type
    
    ![school_type_summary.png](https://github.com/ashleycvirga/School_District_Analysis/blob/f31e1817dba4e5106b08496f57ab285f6c5edddc/Resources/school_type_summary.png)

    * Scores by school type was entirely unaffected.
    
## Summary: 
In summary, there were four main changes observed when the dishonest date for Thomas High School 9th Graders was removed and replaced with NaN values.

  1. The District Summary was most affected by the changes made. We observed a 0.2% drop in the percentage of students passing math, a 0.1% drop in the percentage of students passing reading, and a 0.3% drop in the school districts overall passing rate.

  2. The updated school summary for Thomas High School saw only minor drops in passing percentages when compared to the drops in passing percentages we would have seen if we had replaced the dishonest data with "0" values instead of "NaN" values. We observed a 0.1% drop in the percentage of students passing math, a 0.3% drop in the percentage of students passing reading, and a 0.3% drop in the school districts overall passing rate. Without the NaN values, THS would have seen a 25-27% drop in all three passing percentage values. 

  3. Thomas High School's ranking came in at #2 both before and after the updated changes to the student data set. It appears that the scores for THS 10th, 11th and 12th graders were still high enough to maintain their school's status on the district leaderboard.

  4. There were no significant changes observed to Average Math & Reading Scores by Grade, Scores by School Spending, Scores by School Size or Scores by School Type.


