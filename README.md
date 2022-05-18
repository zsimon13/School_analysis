# School District Analysis

## Overview
Maria, a school district employee, was working on analysis to understand trends among high schools in the district. After completeing the inintial analyis, it was determined that the 9th grade calss at Thomas High Schoool had unrealiable data due to potential academic dishonesty. In order to make sure that the results of the analyis were not skewed, we were asked to rerun the analysis. Thomas Highschool's 9th grade class math and reading scores were replaced with null values and the analysis ran again to determine how different it was from the initial analysis.


## Results
### District Summary
As you can see in the figures below, the school district summary did in fact change when  the Thomas High School 9th grade class scores were replaced. The change however was not substantial. The "District Summary Original" contains all the data from the original analysis, where the "District Summary Updated" figure takes the null values into account. The changes are as follows:
- Average Math Score: *Dropped by 0.1 points*
- Average Reading Score: *No change from original data*
- Percentage Passing Math: *Dropped by 0.2%*
- Percentage Passing Reading: *Dropped by 0.3%*
- Percentage Passing Overall: *Dropped by 0.1%*

#### District Summary Original
![district summary OG](https://user-images.githubusercontent.com/102814578/168504458-612f780d-4933-4fc6-b6ba-f9a8256a5651.png)
#### District Summary Updataed
![district summary updated](https://user-images.githubusercontent.com/102814578/168504321-3d9a0358-abd7-4998-9055-2eac11a331dd.png)

### School Summary
Unlike the District summary, the School Summary did show a substantial change in the "% Passing Reading" category after replacing the Thomas High Schools 9th grade class grades. The rest of the categories showed little to no change. The changes to Thomas High School's metrics are as follows:
- Average Math Score: *Dropped by 0.1 points*
- Average Reading Score: *No change*
- Percentage Passing Math: *Dropped 0.1%*
- Percentage Passing Reading: *Increased by 13.1%*
- Percentage Passing Overall: *Dropped 0.3%*

#### School Summary Original
![School Summary OG](https://user-images.githubusercontent.com/102814578/168927963-8cccf86e-188c-4526-a06b-9af37e9bfc60.png)
#### School Summary Updated
![School Summary updated](https://user-images.githubusercontent.com/102814578/168927972-3ea09331-9db6-40db-9498-0a9dc94a3532.png)

### School Performance
Replacing the scores for the Thomas High School 9th grade class did not change their performance compared to other schools. Thomas High School's overall passing percentage only dropped 0.3% and it remained the 2nd highest performing school over all. The top 5 performing schools based on overall passing percentage are shown below. "Top Performing Schools Original" shows the data before scores were replaced, "Top Performing Schools Updated" shows the data after the scores were replaced.
#### Top Performing Schools Original
![top og](https://user-images.githubusercontent.com/102814578/168945680-22ae6b61-691c-4b4e-8b3d-729747e726b7.png)
#### Top Performing Schools Updated
![top updated](https://user-images.githubusercontent.com/102814578/168945691-aef962a4-6e8e-424f-b1f0-dab7d73defb2.png)


### Effect of Replacing Scores
#### Scores by Grade
The scores by grade were not affected by the replaced of grades for the Thomas High School 9th Grade class. This is because the script was written to only replace those particular grades, and not touch the grades of any other students from any other schools. As you can see below, only the 9th Graders at Thomas High School recieved a "nan" (not a number) value in the analysis.
#### Math by grade
![Math by grade](https://user-images.githubusercontent.com/102814578/168506059-58ca9985-3bac-4dc5-a55c-62f11ffdc16b.png)
#### Reading by grade
![Reading By grade](https://user-images.githubusercontent.com/102814578/168506065-2627e700-4a01-4cc9-9089-b3056f0fa947.png)

#### Scores By Spending
Replacing the grades for the Thomas High School 9th Grade class did affect the scores by spending per student in one category. The "% Passing Reading" increased in the ranges for "<$585", "$586-$630", and "$631-$645" spent per student. All three groupings increased by: 13%, 10% and 2% respectively. This can be seen in the figures below:  
#### Scores by Spending Orignial
![Spending og](https://user-images.githubusercontent.com/102814578/168506223-ba81eb46-35bd-4a76-b85a-423f921874b6.png)
#### Scores by Spending updated
![spending updated](https://user-images.githubusercontent.com/102814578/168506232-061f367b-4897-4495-9e44-8a7dfd92daa4.png)

#### Scores By School Size
Similarly to the "Scores by Spending", the Scores by School Size" saw an increase in all three groupings of the "% Passing Reading" category. "Small", "Medium", and "Large" schools saw an increase of: 12%, 13% and 2% respectively. This can be seen in the figures below: 
#### Scores by School Size Original
![size OG](https://user-images.githubusercontent.com/102814578/168506532-42048ee5-aabd-4620-b679-ab355c7e5834.png)
#### Scores by School Size Updated
![size Updated](https://user-images.githubusercontent.com/102814578/168506540-d7de5457-a30c-46cc-8b8a-3b3c44c6313f.png)

#### Scores By School Type
Replacing the scores affected the "% Passing Reading" category of school types as well. Charter Schools rates went up 13%. No other metrics were affected. This can be seen in the figures below: 
#### Sores by School Type Original
![type OG](https://user-images.githubusercontent.com/102814578/168506697-31e7492f-6e9f-445e-a5a6-f6e0258b593f.png)
#### Scores by School Type Updated
![type updated](https://user-images.githubusercontent.com/102814578/168506702-a2564543-e7c4-4d5a-8252-fdd34031ca14.png)

### Summary
After completing the review, it was determined not much was drastically altered by replacing the Math and Reading Grades for the Thomas High School 9th grade class. Overall scores and percentages did have some variation, though it by a small margin. The performance of Thomas High School was not affected overall, neither were the scores by grade. The most noticeable changes came in the "% Passing Reading" category when analyzing the amount of money spent per student, the size of the schools and the school types. These changes did see some substantial variation, some of over 10%.
