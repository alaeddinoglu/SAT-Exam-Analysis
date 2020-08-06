# Project 1: SAT & ACT Analysis
Our team was asked to analyze statewide participation and recommends where money is best spent to improve SAT participation rates. In our study we analyzed 2017 and 2018, SAT and ACT exam participation rates and scores. Our aim is to show the College Board which states prefer which exam.

The College Board develops and administers the SAT test. Board executive directors do not know if the SAT exam is preferred over the ACT exam.

## Executive Summary
The analysis relies on 4 datasets about 2017 and 2018 SAT and ACT exam scores and participation. The datasets are taken from related resources. Our team researched the general participation rates in each state, and sought for possible correlations between components of the each exam. General attendance in the SAT exam is low in comparison with the ACT exam and similar university entrance exams in other countries. In 2017, the SAT exam average participation rate was 39% in the Unites States. While there is only 1 state has lower than 15% average participation rate ACT exams, there are 18 states with lower than 15% average participation rate in the SAT exam. Seventeen states have 100% average participation in the ACT exam, while 5 states have 100% average participation in the SAT exam.

The correlation between the SAT and the ACT exam total/composite scores is weak. Similarly, the correlation rates between average math and reading scores are weak also. In our study, we found out that generally, states with higher participation in the ACT exam, tend to have lower participation in the SAT exam.

Our team suggests the College Board to to develop strategies for increasing participation in Florida, Ohio and Wisconsin. As described in detail in the report, those states have lower participation rates and higher scores and/or population.


Contents:
2017 Data Import & Cleaning
2018 Data Import and Cleaning
Exploratory Data Analysis
Data Visualization
Descriptive and Inferential Statistics
Outside Research
Conclusions and Recommendations


|Feature|Type|Dataset|Description|
|---|---|---|---|
|sat_17_state|object|sat_17|Each state names|
|sat_17_participation|float|sat_17| High school graduates who took the SAT test during high school over the total number of high school graduates in 2017 by each state. | 
|sat_17_evidence_based_reading_and_writing|int|sat_17|Average evidence-based reading and writing score in the particular state in SAT exam in 2017.| 
|sat_17_math|int|sat_17|Average math score in the particular state in SAT exam in 2017.| 
|sat_17_total|int|sat_17|Average total score in the particular state in SAT exam in 2017.|
|act_17_state|int|act_17|Each state names|
|act_17_participation|float|act_17|High school graduates who took the ACT test during high school over the total number of high school graduates in 2017 by each state.|
|act_17_english|float|act_17|Average English score in the particular state in ACT exam in 2017.|
|act_17_reading|float|act_17|Average reading score in the particular state in ACT exam in 2017.|
|act_17_math|float|act_17|Average math score in the particular state in ACT exam in 2017.|
|act_17_science|float|act_17|Average science score in the particular state in ACT exam in 2017.|
|act_17_composite|float|act_17|Average composite score in the particular state in ACT exam in 2017.|



## Conclusions and Recommendations
Based on your exploration of the data, what are you key takeaways and recommendations? Choose one state with a lower participation rate and provide a suggestion for how the College Board might increase participation amongst graduating seniors in this state. Are there additional data you desire that would better inform your investigations?

In general, the SAT exam average participation rates in 2017 and 2018 are low in comparison with the ACT exam, as well as other countries' equivalent exam participation rates. According to the European Parliament report (1); higher education entrance exam participation rates are following for some countries; Sweden 76%, South Korea 71%, UK 63% and Australia 96%. This shows that the SAT exam particiaption rate 45% in 2018 very low. Also, the ACT exam participation rate is 61% in 2018; that means 16% higher than the SAT participation rate.

Our recommendation for the College Board to develop strategies for increasing participation in Florida, Ohio and Wisconsin states. We recommend Florida to focus on; because, it has the 6th lowest score in SAT; but its participation rate is in the 10 highest with 83%. Florida is the most populated country in the first 10 countries.(2) The students do not prefer to participate to the SAT exam. The College Board local office in Florida can research the reasons why they do not want to participate. Any increase in participation would help to US general participation rate.

The second state we recommend the College Board to focus on is Ohio. Ohio's SAT average participation rates are 12% and 18% in 2017 and 2018. It has the eight lowest average participation rate in the SAT exams; but, Ohio is the 6th most populated country in the US. We see that there is big room for growing in Ohio. The students in Ohio do not prefer to attend SAT exam. In Ohio, participation could be increased to the level of Michigan due to social similarities in these 2 states. (3) Michigan participation rate is 100% in the SAT exam. Also, Ohio Department of Education pays students for taking the SAT and the ACT exams.(4) The College Board local office may collaborate with the Department of Education in Ohio to promote the SAT exam among the high school students.

Our last recommendation is to focus on Wisconsin; because, it has minimum average participation rate in the SAT exam in 2018 while having second highest average score in country. Students prefer to attend in the ACT exam rather than the SAT exam in Ohio, even though they are successful in SAT exam. Similar to Florida, general success in the SAT exam can be a useful tool to promote it among the target group.

Generally, while both the SAT and the ACT exam participation rates are lower than the similar tests participation rates around the world; the College Board is suggested to focus on promoting SAT exam in the US, particularly suggested states.

(1) http://www.lse.ac.uk/business-and-consultancy/consulting/assets/documents/higher-education-entrance-qualifications-and-exams-in-europe.pdf

(2) https://www.census.gov/popclock/

(3) https://www.indexmundi.com/facts/united-states/quick-facts/compare/ohio.michigan -This website refers to US Census Bureau as source

(4) http://education.ohio.gov/Topics/Testing/ACT-SAT-FAQs#FAQ2842

