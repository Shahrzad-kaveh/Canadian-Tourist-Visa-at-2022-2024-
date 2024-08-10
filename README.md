Canadian-Tourist-Visa-at-2022-2024-
Project Overview:
Title:
Canadian Tourist Visa at (2022-2024)
Summery:
I was a member of a Persian Telegram group. The members of this group were Canadian tourist visa applicants who were in the process of receiving their visas. These people put the result of visa acceptance or refuse in the group by mentioning their conditions. I collected data related to 150 cases and 1303 visa applicants and put them in an Excel file. The time frame for this data was from January 2022 to January 2024. If people announced their results before and after this date, they are not included in this statistic.
Applicants had features that affected whether or not they received a visa. They were stressed about how much these features affect the result of getting a visa?
The table I designed is based on these features: having an invitation, having a Schengen visa, a history of Canadian visa refusal. Also, I collected the information of applicants' conditions in terms of gender and the number of visa applications in one file. Which were:
Man, Woman, Couple, Man and Child, Woman and Child, Family.
To create this table, I checked different forms in several sheets and finally I found table Pic 1 suitable for analysis, in which I entered the details of the applicants month by month from January 2022 to January 2024. All numbers are numerical variables and represent numbers.
In this project, the dependent variables are visa results (approve or refuse) and I initially considered the independent variables as invitation, Schengen, and previous refusal to check the effect of each factor on receiving or not receiving a visa.
In addition, to check how the conditions of the applicants in terms of gender and the number of applicants have an effect on receiving a positive or negative result, in the second stage; I considered gender and number of applicants as independent variables.
Also, according to the information on Approved visa in this period of time, is it possible to predict how the process of receiving or not receiving a visa will be in the following months?
Dependent variable (Y) = Approve, Refuse
First stage: Independent variable (X) = Invitation, Schengen, and Previous Refusal
Second stage: Independent variable (X) = Man, Woman, Couple, Man and Child, Woman and Child, Family
This project has five parts:
1-Data cleaning
2-The first part: Investigation and influence of features on Visa results.
3-The second part: Investigation and influence of gender and number on Visa results.
4-Dashboard & Pivot
5-Forecast
Database:
I created the database in three separate sheets and in different tables. The contents of fields and records are the same, but columns have been added or subtracted and the shape of the tables is different.
Categorized 3: The table of this sheet has 176 columns and 8 rows.
Categorized 4: The table of this sheet has 21 columns and 8 rows.
Categorized 5: The table of this sheet has 6 columns and 151 rows.
Features: Characteristics of applicants.
Man: Number of male applicants.
Woman: Number of female applicants.
Couple: The number of applicants who applied as husband and wife.
Man & Child: The number of applicants who applied as father and child.
Woman & Child: The number of applicants who applied as mother and child.
Family: The number of applicants who applied as a family.
Total (Vertical): Sum of the number of each column or field.
Date: Month and year of visa result.
Invitation: Number of invitations per applicant.
Schengen: Number of Schengen visas per applicant.
Previous Refusal: The number of times a visa is refused for each applicant.
Approve: Positive visa result.
Refuse: Negative visa result.
Total (Horizontal): The number of approved or refused people in each record.
Approve 2022: Total number of approved visas in 2022.
Refuse 2022: Total number of Refused visas in 2022.
Approve 2023: Total number of approved visas in 2023.
Refuse 2023: Total number of Refused visas in 2023.
Change% Approve: Percentage of changes in the number of approved visas.
Change% Refuse: Percentage of changes in the number of Refused visas.
Total Approve%2022: Percentage of approved visas in 2022.
Total Refuse%2022: Percentage of Refused visas in 2022.
Total Approve%2023: Percentage of approved visas in 2023.
Total Refuse%2023: Percentage of Refused visas in 2023.
Features Approve%2022: The percentage of approved visas of a Feature divided by the total number of the same Feature in 2022.
Features Refuse%2022: The percentage of Refused visas of a Feature divided by the total number of the same Feature in 2022.
Features Approve%2023: The percentage of approved visas of a Feature divided by the total number of the same Feature in 2023.
Features Refuse%2023: The percentage of Refused visas of a Feature divided by the total number of the same Feature in 2023.
Invitation 2022: Number of invitations applicants in 2022.
Schengen2022: The number of Schengen visa applicants in 2022.
Previous Refusal 2022: The number of previously refused visas of applicants in 2022
Invitation 2023: Number of invitations applicants in 2023.
Schengen2023: The number of Schengen visa applicants in 2023.
Previous Refusal 2023: The number of previously refused visas of applicants in 2023.
According to Pic 2, the two yellow columns under the main table are the total number of approved and refused visas in each record in 2022 and 2023.
Questions & Goals:
1-According to the data available in January three years in a row, how have the results of Canadian tourist visa application changed?
2-How is the examination of positive and negative results in two consecutive years?
3-To what extent did each of the conditions and characteristics of people have an effect on receiving a positive visa result? 
4-If this process continues, to what extent will people be confident in obtaining visas in the coming months?
5-Can you show the minimum and maximum for this process?
Steps:
1-Data cleaning:
At first, because the data was raw and scattered and needed to be cleaned and organized, I first created different types of tables in different sheets and finally designed a table categorized 3 sheet Categorized 3: According to Pic 1, I showed the information of the years 2022 and 2023 month by month. As of 2024, only January data was available.
Categorized 4: According to Pic 2, I added the calculation fields in which the percentage of approved and refused visas in 2022 and 2023 are shown. In addition, I calculated the percentage of changes in receiving visas in these two consecutive years.
Categorized 5: According to Pic 3, In order to check the visa process and predict the future, in this sheet I placed the date column vertically and below from January 2022 to January 2024, and I also created the previous invitation, Schengen and Previous Refusal fields vertically in the same order and the results I entered next to them.
2-Regression: Categorized 6, According to Pic 4, I created a model and checked the effect of independent variables (invitation letter, Schengen, history of refusal) on the dependent variable of the result of receiving a visa through regression. I will fully analyze this model in the analysis section.
3-Conditional Formatting: Using this tool, the factors that have a greater impact on Result of visa are displayed in green and the factors that have less impact on Result of visa are displayed in red.
4-Dashboard 1 & Dashboard 2: First, I compared different variables through a pivot table, and after drawing the corresponding graphs, I created two dashboards, the full explanation of which is available in the analysis section.
5-Forecast: According to Pic 5, in this sheet, I checked the process of receiving positive or negative results in the months after January 2024. Its complete analysis is available in the analysis section.
Analysis:
Result of Regression:
R-Square = 83%: If R-Square be greater than 0.7, it is considered a good result. It means that independent variables or effective factors in Results of visa can explain up to 83% of the dependent variable or Results of visa.
F Significance = 1.002: If the value of the F Significance test is above 5%, the coefficient is not zero. If the coefficient be zero, the independent variable will be zero. This result shows us that there is a linear relationship between our variables.
Standard Error = 2.85: This means that the predicted average is 2.85 away from the actual value. If the sample size increases, the average will be closer to the true value.
Intercept = 0.92: I did not consider the width from the origin or the constant value to be zero. Because the process of getting a visa is a continuous process and it has existed since the years before this project was reviewed. That's why the created graph is placed above the symmetry line of the center.
P-Value = (0.001, 1.107, 0.0002 and 0.25): If it is less than 5%, the coefficient is significant. When F Significance and P-Value are equal, there is only one independent variable. This model shows that the probability of these results is not zero. But since the P-value in the case of Schengen visa is less than 5%, it can be concluded that this coefficient is significant and the probability of it being a chance is very low or close to zero.
Dashboards:
Using categorized 3 and 4, I designed two dashboards to use the pivot tool to create charts and illustrations.
According to Pic 5 and Dashboard 1, I put together the number of approved and refused visas in January and in the consecutive years of 2022, 2023 and 2024 in three graphs. As it is known, the number of refused visas in January 2022 is very low, it has increased in January 2023. However, for the “Man” group, the number of approved and refused visas is equal. As of January 2024, the number of visas refused has increased dramatically, exceeding approved visas in almost all categories. In the “Woman” group, the number of approved visas is almost equal, and in the group of “Man & Child” and “Woman & Child”, the number of approved visas is higher. This is despite the fact that by using the slicers of Invitations and Schengen in each year, it can be seen that these people mostly had invitations and Schengen visas.
The average of approved and refused visas in three consecutive years shows that the number of refused visas has almost quadrupled. But the number of applicants has also increased.
Considering that our information in 2024 is only for the month of January, we can make this comparison for the number of applicants in 2022 and 2023.
As it is known, in all groups except for “Man & Child, we see an increase in the number in 2023 compared to 2022. Thus, in the group of “Man” and “Family”, these number are almost tripled, in the group of “Women’, there are quadrupled, and in the group of “Women & Child”, there are a double increase of applicants.
Now if we compare the average of approved visas in three consecutive years along with the conditions of the applicants, we will see that the number of invitations has increased the most.
	The history of refutation in the first half of 2024 has been increasing, and it seems that these people are applicants who have applied again in 2022 and 2023.
With the timeline in the dashboard, you can see the details of changes in the time period.
According to Pic 6 and Dashboard 2, I compared different groups of applicants in 2022 and 2023. As shown in the graph, the number of approved visas has increased in all groups, except for “Couple” group, which has a decreasing trend. Also, the number of refused requests has increased in all groups except for “Man & Child” and “Family”. In fact, due to the increase of applicants in 2023, there is an increase in both cases. The question that was in the minds of many members of the Telegram group was whether the applicant's being a man or a woman has anything to do with getting a visa or not?
To investigate this question, I drew a number of “Man” and “Woman” visas as separate and side by side graphs. There seems to be a slight difference. In the “Woman” group, the number of processed visas is higher. But it should be noted that the number of “Woman” applicants is more than “Man”.
Now, if we look at the graph of the percentage of changes in approved visas in 2023 compared to 2022, it can be seen that in all groups, the percentage of changes in approved visas has increased, except for the group of “Woman” & Child” and “Couple”, where we see a negative percentage of changes. And children, we see a greater percentage increase than other groups. Slicers of features can show us more details in the changes of charts.
Forecast:
To predict the Canadian tourist visa issuance process for the months after January 2024, using Categorized 5, I selected the Timeline as the Date column and considered the Approved column for the Value Range.
I set Aggregate Duplicates to Average and put the forecast for 7 months after January 2024. The result can be seen in Pic 7.
According to this chart, it is predicted that: in February 2024, the process of approved visas will decrease drastically, and then we will have an increasing process from March. In fact, the slope of the graph is decreasing sharply, and gradually we will have an increasing trend from March to August.
The bold part of the graph shows the past and present time, and the three parallel lines shown in light color are future predictions with 70% accuracy. The lowest line of the lower Confidence Bound has a value of 8.69, the highest line of the upper Confidence Bound has a value of 15.43 and the middle line of the normal forecast has a value of 12.06.
Key points:
	The most influential factor on obtaining a visa is related to having an invitation letter with a coefficient of +0.44 and the least effect is related to Previous Refusal with a coefficient of -0.18.
	The highest value of the standard error in the factors affecting the receipt of a visa is related to Previous Refusal and is equal to +0.161, and the lowest value of the standard error is related to having an invitation and is equal to +0.043.
	The highest P-value in the factors influencing the receipt of a visa is related to having an invitation and is equal to +1.107, and the lowest P-value is related to the Schengen visa and is equal to +0.0002.
	The highest request in 2022 was for the couple group and in 2023 for the “Woman” group, and the lowest request in 2022 and 2023 was for the “Man & Child” group.
	The highest number of approved visas in 2022 and 2023 are related to the “Couple” group, which made up 89% and 75% of the entire group, respectively, and the lowest number of approved visas in 2022 and 2023 are related to the “Man & Child” groups, which are respectively zero percent and they made up 0.4% of the whole group.
	The highest percentage of approved visas in 2023 compared to 2022 is related to the “Family” group, which has increased by 11%, and the lowest percentage of approved visas in 2023 compared to 2022 is related to the group of “Man & Child”, which has increased by 0.4%. Also, the highest percentage of refused applications in 2023 compared to 2022 was related to the group of “Woman & Child” and is equal 4%, and the lowest percentage of refused applications in 2023 compared to 2022 was related to the group of “Man & Child” and was -1%.
	The highest percentage of approved visa changes is related to the group of “Man & Child”, which has increased by almost 40%, and the lowest percentage of changes is related to the group of “Women & Child”, and “Couple”, each of which has decreased by approximately 14%.
	In 2022, the upper Confidence Bound is related to May and has a value of 7.5, and the lower Confidence Bound is related to August and has a value of 0.33. In 2023, the upper Confidence Bound is related to November and is equal to 16.5, and the lower Confidence Bound is related to April and has a value of 1.5.
Results & Recommendations:
1-The analysis shows that having an invitation from a credible and justified person had the greatest impact on receiving a Canadian tourist visa. Having a Schengen visa history is second in importance, and according to the P-value, the probability of the result being real is higher than having an invitation. Also, according to the obtained coefficients, having a history of refusal does not have much effect on receiving a visa and it is possible to apply again by improving the case. But due to having the highest error standard in this part, it can be concluded that the distance of the statistics of this part from the actual result is more than other parts and its effect should not be ignored.
It is suggested to prepare a larger statistical population of applicants who have had a history of refusing for one or more times as well as more people who have a Schengen visa, and check the new result of their visa for a detailed investigation of this issue.
2-Although it seems that the number of refused visas has increased, the total chart shows that the number of visa applicants has increased at the same time. In other words, the policy of Iranians has caused an increase in visa requests, but there has always been a specific algorithm and capacity to maintain the appropriateness of approved and refused visas.
3-What is clear is that the gender of the applicants and their characteristics do not have much effect on the result of the visa and only the conditions of the case can have an effect.
4-Considering that the existing statistical population is small and the information related to 2024 is only available for one month, it is suggested to conduct the analysis again with a larger statistical population with more information from the applicant groups.
5-In the review of Canadian tourist files, other factors such as: Thai, Bank statement, account Activity and the purpose of the travel are also taken into consideration, each of them are the determining factors in the result of the visa. These factors were not investigated in this project and it is suggested to investigate their impact in a more complete project.
6-Canada is suitable for tourists due to its cold weather from the end of spring and summer. For this reason, the forecast of the increasing process of issuing visas in the first months of the year can be close to reality. But there are also some unpredictable conditions that are influential in this process, which are out of the scope of our project.


