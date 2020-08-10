# Project 1: SAT & ACT Analysis


## Problem Statement
Since 2012, SAT lost leadership to ACT as the most widely used college admission test in the US.  College Board released the new format in March 2016, and would like to identify priority state(s) to focus the efforts and resources in driving SAT participation rates going forward.  


## Executive Summary

To address our problem statement, we analyse average SAT and ACT scores by state, as well as the participation rates, for the graduating class of 2017 and 2018.  Topics covered are outlined below:  

  ### Key Contents
  - 2017 Data Import & Cleaning
  - 2018 Data Import and Cleaning
  - Exploratory Data Analysis
  - Data Visualization
  - Descriptive and Inferential Statistics
  - Outside Research
  - Conclusions and Recommendations


## Data Dictionary:

|Feature|Type|Dataset|Description|
|---|---|---|---|
|**state**|*string*|sat_2017, act_2017, sat_2018, act_2018|US States (50 States + District of Columbia).| 
|**sat17_participation**|*float*|sat_2017|The percent participation on SAT test for students in the class of 2017.|
|**sat17_erw**|*integer*|sat_2017|The average Evidence-Based Reading and Writing (ERW) scores of the SAT in 2017.|
|**sat17_math**|*integer*|sat_2017|The average Math scores of the SAT in 2017.|
|**sat17_total**|*integer*|sat_2017|The average Total scores of the SAT in 2017.|
|**act17_participation**|*float*|act_2017|The percent participation on ACT test for students in the class of 2017.|
|**act17_english**|*float*|act_2017|The average Engligh scores of the ACT in 2017.|
|**act17_math**|*float*|act_2017|The average Math scores of the ACT in 2017.|
|**act17_reading**|*float*|act_2017|The average Reading scores of the ACT in 2017.|
|**act17_science**|*float*|act_2017|The average Science scores of the ACT in 2017.|
|**act17_composite**|*float*|act_2017|The average Composite scores of the ACT in 2017.|
|**sat18_participation**|*float*|sat_2018|The percent participation on SAT test for students in the class of 2018.|
|**sat18_erw**|*integer*|sat_2018|The average Evidence-Based Reading and Writing (ERW) scores of the SAT in 2018.|
|**sat18_math**|*integer*|sat_2018|The average Math scores of the SAT in 2018.|
|**sat18_total**|*integer*|sat_2018|The average Total scores of the SAT in 2018.|
|**act18_participation**|*float*|act_2018|The percent participation on ACT test for students in the class of 2018.|
|**act18_english**|*float*|act_2018|The average Engligh scores of the ACT in 2018.|
|**act18_math**|*float*|act_2018|The average Math scores of the ACT in 2018.|
|**act18_reading**|*float*|act_2018|The average Reading scores of the ACT in 2018.|
|**act18_science**|*float*|act_2018|The average Science scores of the ACT in 2018.|
|**act18_composite**|*float*|act_2018|The average Composite scores of the ACT in 2018.|




## Conclusions:

From the EDA, Visualizations, and outside research, **there are 3 states of interest** for College Board to increase SAT participations.  These are states that ranked lowest in SAT participation rates, while they are not mandatory states for ACT (100% participation). 

- Iowa
- Kansas
- South Dakota


**Out of the 3 states of interest, IOWA has the highest potential.**

- **Highest population among the 3 states.**  Gaining state participation in Iowa (3.96 Million Population) will have higher impact on the National average particiation.  Second priority is Kansas (2.9 Million), while South Dakota is as smaller opportunity (884 Thousand).

- **Opportunity to replace the current state assessment tests.**. 
  - All 3 states are using non SAT/ACT for high school tests, providing an opportunity for SAT.  For students looking to apply for college, switching to SAT will take the burden of their time to prepare for college admissions, while also encouraging those who may not consider apply for college to do so given less barrier on time and resources (as seen in the case of Illinois).
  - Greater opportunity for Iowa and Kansas as they are currently using local tests (Iowa State-wide Assessment - ISASP) and Kansas Assessment Program - KAP, while South Dakota is currently using Smarter Balanced, a standardized high school test used in many states, i.e. California, Connecticut).
  - Source: https://www.edweek.org/ew/section/multimedia/states-require-students-take-sat-or-act.html
  
- **Additional research show supporting information for Iowa.**
  - **Relatively stronger financials vs. Kansas:** With higher tax revenue (USD 9.5 vs. 8 Billion), higher federal aid (USD 6 vs. 3.9 Billion), and relatively lower debt USD 6.12 Billion in fiscal year 2015 (ranked 37th among the states in debt).  (Source: https://ballotpedia.org/Iowa_state_budget_and_finances)
  - **Focus on education:** Education accounted for 41.6 percent of state expenditures in fiscal year 2015.
  - **Need for change with support from legislators:**
    - Based on the article Money is the key to education in Iowa, there is a sentiment around need for a change for Iowa regarding measures of education success for students, while the main constraint is money.  Iowa is ranked 25th in per-pupil spending (USD 13,531 vs. USD 14,273 National Average).  Fortunately, some advocates and legislators continue to push for higher funding.  Last session, the Iowa Legislature also increased funding by 2.1%.
    - A few quotes that implies "need for change":
      - "Iowa has lost its leadership position in national rankings," 
      - In recent years, some of the stats that have come to define educational success have changed, and not always for the better. Sometimes those numbers haven't changed, but other states have made gains that Iowa students aren't necessarily seeing. 
      - Source: Article: Money is the key to education in Iowa https://qctimes.com/news/local/education/the-numbers-money-is-the-key-to-education-in-iowa/article_1d1578dc-0050-5814-91f7-ef3a74da739d.html

  

**Prioritized list of states with high opportunity to target**


|Priority|State|2018 SAT Participation|Population|Current High School Test|
|---|---|---|---|---|
|1|**Iowa**|3%|3,962,077|Iowa State-wide Assessment(ISASP)|
|2|**Kansas**|4%|2,913,314|Kansas Assessment Program. (KAP)|
|3|**South Dakota**|3%|884,659|Smarter Balanced (standardized test)|

Sources: (State Population)
https://en.wikipedia.org/wiki/List_of_states_and_territories_of_the_United_States_by_population


## Recommendations:

**Adopt same strategy as for Colorado & Illinois with State Contracts (SAT School Day Program), focusing on Iowa, followed by Kansas.**  This may require changes in legislation for the particular state to allow competitive bidding.  
  
**Key message to convince legislators & Department of Education:**
  - Redirecting the funds spent on local high school tests to state-funded SAT will release the state's resources to on other matters, while ensuring that student's measurement of academic success is achieved and competitive with other states nationwide.
  - For parents and students, this will benefit students who are applying for college by putting less time and burden on preparing for standardized tests, while also benefiting those who previously were not planning to apply for college by increasing their readiness and affordability as the test will be state-funded.
  

















