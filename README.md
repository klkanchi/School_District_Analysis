# School_District_Analysis
## Overview of the school district analysis:

The purpose of this project is to analyze the data of a School District, such as funding and student average matha and reading grades, to learn and visually provide clear results on each high school's performance and the overall passing percentages. Additionally, to uphold state-testing standards, this analysis was repeated twice due to potential academic dishonesty among a group of students. The implications of omitting the potentially dishonest data are also discussed.


## Results:

Due to potential academic dishonesty by the ninth grade students of Thomas High School, this analysis was conducted twice. The first trial of this analysis included the full set of student data. In the second trial of this analysis, the ninth grade students of Thomas High School had their scores omitted from the calculations. The entire ninth grade class of Thomas High School have had their scores replaced with NaN. The DataFrame below is a summary representing the District after replacing the ninth graders' scores with NaN. district_overview

![school_summary.png](https://github.com/klkanchi/School_District_Analysis/blob/main/school_summary.png)
    
- Replacing the ninth graders' math and reading scores with NaN resulted in the following changes for Thomas High School:
        The overall passing percentage for Thomas High School fell to 65%
        
        The overall passing percentage for the entire district fell to 64.9%
        
        Thomas High School was no longer included on the list of top five schools.

 - When the ninth graders' of Thomas High School had their scores omitted from the calculations, the following changes occured:
        The overall passing percentages of Thomas High School decreased by 0.11%
        
        The average scores of Thomas High School for math and reading increased by 0.06
        
        For the spending range of $630-644 per student, the overall passing percentage decreased by 0.1%
        
        School rankings are unchanged. Thomas High School is still the second best performing school in the district with an overall passing rate of 90.63%         among their tenth through twelfth graders.
        
 ## The Effects of School Budget
 
   It is found that Average Scores and Passing Percentages do not increase as spending per student increases. In fact, the top performing school in the     entire school district (Cabera High School) received $68 less per student than the lowest performing school (Johnson High School). This implies that there are more relevant factors than funding that decide average student scores.
   
![average_scores_by_spending.png](https://github.com/klkanchi/School_District_Analysis/blob/main/average_scores_by_spending.png)
   
 ## Effect of School Size  
 
   When considering School Sizes, "Large" Schools (Over 2,000 Students) have the lowest average scores and passing percentages. The difference in performance between "Small" and "Medium" Size Schools is negligible (approximately 1%). Interestingly, all District schools in this dataset are characterized as "Large" schools. This may be an indication that students in this district learn and perform better in smaller, more intimate settings.
   
 ![average_scores_by_schoolsize.png](https://github.com/klkanchi/School_District_Analysis/blob/main/average_scores_by_schoolsize.png)
   
  ## Charter vs. District Schools

Charter schools generally performed better than District schools in this analysis. The top five schools with the highest overall passing percentages are all Charter schools, whereas the bottom five are all District Schools. Charter schools in this dataset were typically characterized as "Small" and "Medium" size schools. As seen in the DataFrame below, Charter schools have a 36% higher overall passing percentage than District schools.

 ![average_scores_by_schooltype.png](https://github.com/klkanchi/School_District_Analysis/blob/main/average_schools_by_schooltype.format.png)


  ## Summary:
  
  After analyzing the average scores for math and reading by grade level for each school, it is found that a students grade level does not affect their scores as much as the school that they attend. The average scores within each school only varries by 1-2% depending on grade level. However, the difference in scores is more apparent when comparing different schools as shown.
  
 ![highest_performaing_schools.png](https://github.com/klkanchi/School_District_Analysis/blob/main/highest_performaing_schools.png)
 



