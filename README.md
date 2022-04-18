# School District Analysis

## Overview

The following analysis was done in a school district to help in allocating funds appropriately and see ways to help improve perfomance throught the district. A report was finalized and presented to a group of stakeholders and school board and it is fully deatiled in this document with relevant suggestions and helpful observations to further improve the perfomance of this particular district. However, this analysis is comporomised as one grade from a particular high school is believed to have manipulated their results. 

## Results

* After the rectifying the data that was believed to be altered, the district summary was not affected as much as there were very slight differences. After correcting the data, the highest negative difference was in the region of 0.3% which was in the percentage that passed in reading as before the cleanup there was 86% and after it was 85.7% which can show that there was not much of a difference which is shown as follows:  
 <img width="977" alt="District Summary DF" src="https://user-images.githubusercontent.com/101376325/163746154-d0ca40f3-e85e-423d-abe6-9b2bf2720687.png">

* After cleaning up the data, the overall passing of Thomas High School dropped from 91% all the way to 65% which was a massive drop. The differences in position can be seen as follows: ![Top Schools](https://user-images.githubusercontent.com/101376325/163747072-eb459849-2591-47f3-b821-ae0ca2125ce6.png)
   


<img width="971" alt="Screen Shot 2022-04-17 at 9 58 28 PM" src="https://user-images.githubusercontent.com/101376325/163747594-709b7852-3228-4d32-8061-7fc97cc2d693.png">

* By replacing the 9th grade scores, the grades were masssively hurt since they were set to NaN which results in zero that is expected to cause a massive negative difference which caused the drop from 91% TO 65%. A total of 461 students being taken out was always going to cause major problems to the final audit which can be displayed below: ![NaN](https://user-images.githubusercontent.com/101376325/163748230-b3ecedc8-a9e2-4e88-994b-ce4f85554355.png)

* In addition, 461 students of 1635 students brings a missing 28% which could possib;ly have hindered the accuracy of the analysis. 

* According to this analysis, major differences were not noticed in the school type, school size and school spending parameters as shown by the images below: 

![School by type](https://user-images.githubusercontent.com/101376325/163748894-3e3960b7-b82c-4be5-aecb-8add151a02d4.png)


![School by spending](https://user-images.githubusercontent.com/101376325/163748929-3813e915-8d0f-4930-9006-12f49c8ed37d.png)


![School by size](https://user-images.githubusercontent.com/101376325/163748974-9dcbd03e-eea2-4c28-a7d3-2a8fb09ff701.png)

## Summary

Changes after updating the school district analysis include: 
 
 * The replaced numbers were fairly determined.
 * Altering such a high number of students' results is costly as seeen by the 26% drop by Thomas High School.
 * When determining averages,  NaN are not so significant since the numbers that replace them are roughly an average of the whole dataset which on the other hand can be not so useful as the real data is way different which can lead to misinterpretation of data.
 * The differences in funding between the original data set and the one believed to be crooked is not that big. 




