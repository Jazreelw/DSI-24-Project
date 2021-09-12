# Project 1: ACT/ SAT, 2017 and 2018

### Problem statement

The new format for the SAT was released in March 2016. The College Board seeks to track statewide participation and recommends where money is best spent to improve SAT participation rates.

How the College Board might work to increase the participation rate in Arkansas and Tennessee?

---
### Data Dictionary

|Feature|Type|Dataset|Description|
|---|---|---|---|
|e_act_2017|float|ACT 2017|English scores for ACT 2017| 
|m_act_2017|float|ACT 2017|Math scores for ACT 2017| 
|r_act_2017|float|ACT 2017|Reading scores for ACT 2017| 
|s_act_2017|float|ACT 2017|Science scores for ACT 2017| 
|comp_act_year|float|ACT 2017 and 2018|Composite scores for ACT 2017 and 2018 (provided)|
|tot_cal_diff_exam_year|integer|ACT/SAT 2017 and 2018|Difference in calculated total scores and total scores provided| ACT/SAT 2017 and 2018|
|e_sat_year|integer/float|SAT 2017 and 2018|English scores for SAT 2017 and 2018|
|m_sat_year|integer/float|SAT 2017 and 2018|Math scores for SAT 2017 and 2018|
|avg_act_year|float|ACT 2017 and 2018|The calculation for average of scores provided| 
|avg_sat_year|float|SAT 2017 and 2018|The calculation for average of scores provided| 
|tot_act_year|float|ACT 2017 and 2018|The total of scores provided (range: 1 - 36)| 
|tot_sat_year|integer|SAT 2017 and 2018|The total of scores provided (range: 400 - 1600)| 
|p_act_year|float|ACT 2017 and 2018|The participation rate of relevant examinations, 100 = 100%| 
|p_sat_year|float|SAT 2017 and 2018|The participation rate of relevant examinations, 100 = 100%| 


---
### Summary of analysis

We started off in the first section of the notebook by data cleaning. Duplicates of rows and alphabet in a column where there should only contain numbers were found in the datasets. Further data cleaning were done to ensure that the columns that were not used on the analysis were removed and columns renamed appropriately.

For ease of user's understanding of the data, 6 graphs were plotted to show the summary of contents in datasets, with focus on the SAT participation rates and also the average scores. 

---
### Conclusions and recommendations

### States with a big jump for participation rates from 2017 to 2018
#### Colorado
From April 11th, 2017 all Colorado high school juniors are required to take the SAT. In 2016, only 5500 Colorado students took the test. Besides, Khan Academy is teaming with the College Board, the makers of the SAT, to provide free and personalized SAT study courses for Colorado students. This saw Colorado participation rate increased from 11% in 2017 to 100% in 2018.

https://testive.com/colorado-sat-change-2017/

https://www.denverpost.com/2017/03/06/colorado-juniors-sat-college-exam/

#### Illinois
Similarly for Illinois, it has become mandatory statewide for high school juniors to take the SAT in order to enter a College from April 5th, 2017. Because of that, the participation rates saw a big jump from 9% in 2017 to 99% in 2018.

https://testive.com/illinois/

### States with low participation rates in 2017 and 2018
#### Arkansas
For years 2017 and 2018, participation rates for  SAT remains low at 3% and 5%. However, the participation rates for ACT for both years are high at 100%. This could be due to the State University, University of Arkansas, applicants are able to take the ACT exams on campus. 

https://admissions.uark.edu/apply/test-scores/index.php

#### Tennessee
The participation rates for SAT are 5% and 6% in 2017 and 2018, with ACT participation rates of 100% for both years.

The Tennessee education department has placed increased efforts on raising ACT scores over the past several years to ensure students are ready for college or a career. As well, more students scoring high on the ACT means that more are eligible for the HOPE scholarship, which provides college money for students reaching a 21 or higher on the ACT. To help aid improvements in scores, the state offered free retake opportunities for all students in 2017. Thus the high participation rates for ACT for both years.

https://www.tennessean.com/story/news/education/2017/10/10/tennessee-act-scores-improve-students-near-2020-goal/745996001/

### States with high participation rates for SAT participation rates
####  Connecticut and Delaware
The participation rates for Connecticut  and Delaware are at 100% for SAT for both 2017 and 2018. The is due to the change in State policy saying that all 11th graders in the state's public schools would soon be required to take the SAT college admissions tests. Because of the chnage in State policy, the ACT participation rates are lower in these States 2017 and 2018.

https://www.nytimes.com/2015/08/07/nyregion/connecticut-to-require-all-11th-graders-to-take-the-sat.html#:~:text=Connecticut%20announced%20on%20Thursday%20that,students%20are%20tested%20too%20much.

https://whyy.org/articles/ud-drops-satact-requirement-for-delaware-applicants/

### Recommendation
State which have a lower participation rate in SAT is Arkansas and Tennessee. They are one of the states which have yet to legistrate which test to adopt, it is recommend that the College Board to step up the following activities to enhance participation rates for SAT in states which do not have manadatory requirements to take ACT.

- Influence state school districts to include PSAT for high school juniors

- Bursary and Fee waivers to cover test costs: lower entry barrier for lower-income students

- Introduce PSAT(Preliminary SAT) for junior school students to prepare them for SAT examination

- Create more workshops and talks on sat to showcase success stories of SAT

https://www.safety.com/the-poorest-states-in-america/
