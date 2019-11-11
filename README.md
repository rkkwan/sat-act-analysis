# ![](https://ga-dash.s3.amazonaws.com/production/assets/logo-9f88ae6c9c3871690e33280fcf557f33.png) Project 1: Standardized Testing, Statistical Summaries and Inference

## Overview

### Problem Statement
The new format for the SAT was released in March 2016. The College Board has tracked statewide participation and recommends where money is best spent to improve SAT participation rates. Recent statewide policy changes in Illinois and Colorado now require all high school juniors to take the SAT starting 2017. While this type of initiative effectively increases SAT participation to 100%, students taking the test out of requirement will not perform well. This negates the whole purpose of the SAT, which is to help students gain admission to higher education. We will observe how changes in SAT and ACT participation rates are correlated with statewide SAT and ACT average scores.

### Executive Summary
SAT and ACT Participation rates are negatively correlated with their corresponding test scores. States with high participation rates tend to have two bimodal test scores distributions: One peak from high performing students, and another peak from students taking the test out of requirement. States that implemented policies to require the SAT witnessed a decrease in average SAT scores. If the purpose of increasing SAT participation is to increase student admissions to college, the College Board must address how to better prepare students to take the test. Otherwise, students taking the test out of requirement tend to perform poorly.

---


## Presentation
[Link to Google Slide](https://docs.google.com/presentation/d/1CJIE51WJYrGBKDXoJ-pu0a4tYqTH6xCtenxbg-QcPiA/edit?usp=sharing)

---

## Datasets

### Provided data
- [2017 SAT Scores](./data/sat_2017.csv)
- [2017 ACT Scores](./data/act_2017.csv)


### Manually collected data
- [2018 SAT Scores](./data/sat_2018.csv)
- [2018 ACT Scores](./data/act_2018.csv)


### Combined data
- [final](./data/final.csv)

These data give average SAT and ACT scores by state, as well as participation rates, for the graduating class of 2017 and 2018.


### Sources
[2017 SAT Scores](https://blog.collegevine.com/here-are-the-average-sat-scores-by-state/)  
[2017 ACT Scores](https://blog.prepscholar.com/act-scores-by-state-averages-highs-and-lows)
[2018 SAT Scores](https://reports.collegeboard.org/sat-suite-program-results/state-results)
[2018 ACT Scores](http://www.act.org/content/dam/act/unsecured/documents/cccr2018/Average-Scores-by-State.pdf)

## Data Dictionary

|Feature|Type|Dataset|Description|
|---|---|---|---|
|state|_object_|ACT 2017|U.S. State, region or district|
|act_2017_participation|_int_|ACT 2017|Percentage of students who participated in taking the test|
|act_2017_english|_float_|ACT 2017|Average score in the English test|
|act_2017_math|_float_|ACT 2017|Average score in the Math test|
|act_2017_reading|_float_|ACT 2017|Average score in the Reading test|
|act_2017_science|_float_|ACT 2017|Average score in the Science test|
|act_2017_composite|_float_|ACT 2017|Average score of all subject-area tests|
|state|_object_|SAT 2017|U.S. State, region or district|
|sat_2017_participation|_int_|SAT 2017|Percentage of students who participated in taking the test|
|sat_2017_ebrw|_int_|SAT 2017|Average score in the Evidence-Based Reading & Writing section|
|sat_2017_math|_int_|SAT 2017|Average score in the Math section|
|sat_2017_total|_int_|SAT 2017|Total score of both sections|
|state|_object_|ACT 2018|U.S. State, region or district|
|act_2018_participation|_int_|ACT 2018|Percentage of students who participated in taking the test|
|act_2018_composite|_float_|ACT 2018|Average score of all subject-area tests|
|state|_object_|SAT 2018|U.S. State, region or district|
|sat_2018_participation|_int_|SAT 2018|Percentage of students who participated in taking the test|
|sat_2018_ebrw|_int_|SAT 2018|Average score in the Evidence-Based Reading & Writing section|
|sat_2018_math|_int_|SAT 2018|Average score in the Math section|
|sat_2018_total|_int_|SAT 2018|Total score of both sections|

The ```final``` dataset contains all of the above, with only one ```state``` column.






