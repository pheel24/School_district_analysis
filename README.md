# School District Analysis
## Overview
The purpose of this analysis is to verifty the veracity of the claims of impropriety on the part of Thomas High School 9th grade test scores. By removing the scores in question and comparing the new data to the overall analysis, any statistical discrepancies should be clearer (for the duration of the analysis, the data with the Thomas High scores included will be referred to as the "null" data, with the null figures coming before the updated figures for comparison). This will allow the district authorities to act with the utmost clarity in their handling of the situation with respect to Thomas High School and maintain confidence in the reliablity of the testing system.

## Results
The broader metrics under consideration in this analysis are as follows: district level summary, school-wise summary, test scores by grade, test scores by school spending, test scores by school size, and test scores by school type. The resulting comparisons with and without the Thomas High scores are discussed below (all figures used in the analysis are available in the "Figures" folder within the "resources" folder).
* District-wide summary: On a district level, the change is not very significant with average math scores only varying by fractions of percentage points.

![district_summary_null](https://user-images.githubusercontent.com/95315957/150703361-161aa2ea-f021-458f-afed-8bed4a811225.PNG)
![district_summary_NaN](https://user-images.githubusercontent.com/95315957/150703363-95842ed8-5f48-44a0-be10-9c0a2e1c12e1.PNG)

* School-wise summary: Leaving out 9th grade test scores had little impact on the overall metrics aswell, with the average reading score increasing slightly. 

![per_school_summary_null](https://user-images.githubusercontent.com/95315957/150704645-7d8a5baf-f662-4eb9-a015-9350048f1270.PNG)
![per_school_summary_NaN](https://user-images.githubusercontent.com/95315957/150704649-231b1236-8f55-4ae4-a715-296e5534624d.PNG)

* Test Scores by Grade: For comparison purposes, these are grade level test scores for reading and math respectively.

Reading:

![grade_rscore_null](https://user-images.githubusercontent.com/95315957/150706948-0646bc8c-9cfa-48ed-85fd-621f78136515.PNG)
![grade_rscore_NaN](https://user-images.githubusercontent.com/95315957/150707004-71510ba1-97cb-464e-b9ca-7ba91721727a.PNG)

Math:

![grade_mscore_null](https://user-images.githubusercontent.com/95315957/150707011-20e0e8d6-6811-43bb-952e-cfe5363cc85e.PNG)
![grade_mscore_NaN](https://user-images.githubusercontent.com/95315957/150707021-00cecc57-e7eb-41cc-b67a-2c52d0d5c945.PNG)

* Test Scores by School Spending: The differences of the scores by school budget yielded little difference, with a slight difference in the overall passing rate. Note that Thomas High School is in the '630-644' dollar range per student. 

![spending_summary_null](https://user-images.githubusercontent.com/95315957/150705514-cc24c10e-80a2-4910-955b-18d8790555ae.PNG)
![spending_summary_NaN](https://user-images.githubusercontent.com/95315957/150705525-14510876-d420-4aed-a00f-3db33dd350f3.PNG)

* Test Scores by School Size: Focusing on the 'medium (1k-2k)' row, there is no significant difference in testing outcomes. 

![size_summary_null](https://user-images.githubusercontent.com/95315957/150705929-713d88ea-ad63-43ef-a523-78babfb2b21a.PNG)
![size_summary_NaN](https://user-images.githubusercontent.com/95315957/150705937-0f8119f6-593f-45d2-9053-9cb734f90c0f.PNG)

* Test Scores by School Type: There is litle difference in testing outcomes when viewed by school type, of which Thomas High School is a charter school. 

![type_summary_null](https://user-images.githubusercontent.com/95315957/150706264-8f377d58-7289-449d-a9bf-82861c35ee18.PNG)
![type_summary_NaN](https://user-images.githubusercontent.com/95315957/150706278-56fda99d-8e78-4309-8d9c-9f1e90b7ed3e.PNG)

## Summary
On a district level, our experiment resulted in a negative change to the average math scores for Thomas HS with a concurrent decrease in the overall passing rate, on a school level the change increased the average reading score. When focusing on the level of spending per student, the overall passing rate decreased. 
