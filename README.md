# School_District_Analysis

## Overview of the School District Analysis
Maria the chief data scientist for a city school district is responsible for analyzing information from a variety of sources, and in a variety of formats. In this role she is tasked with preparing all standardized test data for analysis, reporting, and presentation to provide insights about performance trends and patterns. These insights are used to inform discussions and strategic descisions at the school and district level.

Later, Maria and her supervisor got notified about the evidence of academic dishonesty, specifically reading and math grades for Thomas High School ninth graders appear to have been altered. So, this analysis will assist the school board and superintendent in making decisions regarding the school budgets and priorities.

### Purpose
The pupose of this analysis is to help Maria analyze data on student funding and student's standardized test scores, and to aggregate the data and showcase trends in school performance. Also, to repeat the school district analysis to see how does replacing the math and reading scores for Thomas High School with NaNs while keeping the rest of the data intact affected the overall analysis.

## Results

After all the ninth-grade student data for Thomas High School was replaced with NaN, below are the affected results summmarized:

### The District Summary

As we can see below, for the district summary data, there are nominal changes in some of the values from the original analysis to the repeated analysis. Athough the average math score, average reading score, passing math percentage, passing reading percentage, and overall passing percentage show minute changes, the changes are less than 1% and can be round off easily. While rest of the data, total schools, total students, and total budget remains the same.
 
_Original Analysis_:

<img width="975" alt="district_summary_original" src="https://user-images.githubusercontent.com/95826875/150697059-af02501f-45e8-413f-a85c-4a4b03c75411.png">

_Repeated Analysis_:

<img width="950" alt="district_summary_adjusted" src="https://user-images.githubusercontent.com/95826875/150697195-1a5403d8-dbfd-429b-8569-5ab2499b5e04.png">

 
### The School Summary

For the school summary data, as we can see below, there's a significant drop of percentages from the original analysis to the repeated analysis. The passing math percentage dropped from 93% to 67%, passing reading percentage dropped from 97% to 69%, and the overall passing percentage dropped from 91% to 65%. So, replacing the 9th grade students and recalculating with 10th - 12th grade has a huge impact on the data set.

_Original Analysis_:

<img width="1017" alt="School_summary_original" src="https://user-images.githubusercontent.com/95826875/150666272-6d30d700-5cf0-45fc-b065-b5e9745fbf26.png">

_Repeated Analysis_:

<img width="1014" alt="School_summary_adjusted" src="https://user-images.githubusercontent.com/95826875/150667114-a7cdc613-30aa-4c6d-b41a-f13d2cf330da.png">

### How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?

After replacing the ninth graders' math and reading scores, the rank position of the Thomas High School's relative to the other schools got affected. In the original analysis, Thomas High School ranked 2nd position which dropped to 8th position from the bottom after the repeated analysis.

_Original Analysis_:

<img width="1013" alt="THS_Original" src="https://user-images.githubusercontent.com/95826875/150667677-86cdf22e-bd76-4450-affd-b23589b8d88c.png">

_Repeated Analysis_:

<img width="1021" alt="THS_Adjusted" src="https://user-images.githubusercontent.com/95826875/150667685-c65fab7b-9e5b-40c9-8139-73a61cd116ed.png">

### How does replacing the ninth-grade scores affect the following:

#### Math and Reading Scores by Grade

Thomas High School have math average 83.6 and reading average 83.7 for the 9th grade in the original analysis. After replacing the ninth-grade scores, the math average and reading average values got chnages to 'nan', which are null-values in python programming language.

_Original Analysis_:

Original Math Scores by Grade

<img width="338" alt="math_scores_original" src="https://user-images.githubusercontent.com/95826875/150668619-28e99a7c-c91b-4350-8e02-5b858d1bfe9f.png">

Original Reading Scores by Grade

<img width="315" alt="reading_scores_original" src="https://user-images.githubusercontent.com/95826875/150668624-233ec4f9-116e-4113-8f1a-31cef559a03f.png">

_Repeated Analysis_:

Adjusted Math Scores by Grade

<img width="330" alt="math_scores_adjusted" src="https://user-images.githubusercontent.com/95826875/150668679-31ddad17-7a5a-4a2e-9489-41ced538c4df.png">

Adjusted Reading Scores by Grade

<img width="320" alt="reading_scores_adjusted" src="https://user-images.githubusercontent.com/95826875/150668751-8b65cdc5-6145-46e2-976b-6f7dd4557d42.png">

#### Scores by School Spending

Thomas High School comes under the $630-$644 spending range. After replacing the 9th grade score, there was very minute impact on scores by school spending.

_Original Analysis_:

<img width="857" alt="spending_originated" src="https://user-images.githubusercontent.com/95826875/150669037-40f94810-d446-4c99-b4cf-e30206db775a.png">

_Repeated Analysis_:

<img width="855" alt="spending_adjusted" src="https://user-images.githubusercontent.com/95826875/150668836-31778e0e-1afc-49be-88f7-3a2296a098e7.png">

#### Scores by School Size

Thomas High School is a medium sized school. After replacing the 9th grade score, there was very minute impact on scores by school size.

_Original Analysis_:

<img width="783" alt="size_original" src="https://user-images.githubusercontent.com/95826875/150669149-1d5b9854-c39a-4ac9-b6dc-bae0bf7038f8.png">

_Repeated Analysis_:

<img width="780" alt="size_adjusted" src="https://user-images.githubusercontent.com/95826875/150669178-f86c7ddd-0c45-4ab8-bcd2-2e7aed6d81d1.png">

#### Scores by School Type

Thomas High School is a Charter school. After replacing the 9th grade score, there was very minute impact on scores by school type.

_Original Analysis_:

<img width="763" alt="type_original" src="https://user-images.githubusercontent.com/95826875/150669284-196a04d3-9dc8-42c0-8881-9176f6796796.png">

_Repeated Analysis_:

<img width="748" alt="type_adjusted" src="https://user-images.githubusercontent.com/95826875/150669319-26a211d7-349c-4030-8dea-6ed261b7bf6d.png">

## Summary

Four changes in the updated school district analysis after reading and math scores for the ninth grade at Thomas High School have been replaced with NaNs are as follows:
1. The district summary data shows minute changes, where as in the school summary data, the overall passing percentage significantly dropped from 91% to 65%.
2. Thomas High School's ranking dropped from 2nd to 8th relative to other schools.
3. Thomas High School's math and reading scores got replaced by 'nan' after replacing the 9th grade.
4. After replacing the 9th grade score, there were very minute impact on scores by school spending, school size, and school type.
