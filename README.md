# ![](https://ga-dash.s3.amazonaws.com/production/assets/logo-9f88ae6c9c3871690e33280fcf557f33.png) Project 1: Standardized Testing, Statistical Summaries and Inference

## Overview


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






