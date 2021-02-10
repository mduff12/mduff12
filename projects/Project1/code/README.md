# Meryl Duff - Project 1: SAT & ACT and School Funding

**Executive Summary**

Many US colleges and universities have become "test optional" or "test blind" due to research that indicates the standardized tests (ACT & SAT) are highly correlated with "race and parental income" ([Gavin Newsom, Oct 2019](https://www.gov.ca.gov/wp-content/uploads/2019/10/AB-751-Veto-Message.pdf)). While this may be true, it is prudent to also explore any potential relationship between *government school funding* (per pupil current spending) and SAT/ACT average scores and participation rate, per state. 

The goal of this project is to explore the relationship between test performance and per pupil spending to inform future research on the impact of educational funding on standardized measures of success.

### Data Dictionary
| Feature | Type | DataSet | Description |
|-|-|-|-|
| geographic_area | obj | ppcs_2018 | state in the United States |
| 2018_ppcs | float | ppcs_2018 | Per pupil current spending, referring to the amount of money that is, on average, spend per pupil in the state for 2018 |
| state | obj | ppcs_2018,<br>act_2018, sat_2018 | state in the United States |
| participation | float | act_2018, sat_2018 | participation rate for schools in designated state |
| avg_composite_score | float | act_2018 | average total score for ACT-tested high school students in that state |
| avg_ebrw_score | float | sat_2018 | average evidence based reading and writing score for SAT-tested high school students in that state |
| avg_math_score | float | sat_2018 | average math score for SAT-tested high school students in that state |
| total | float | sat_2018 | average total score for SAT-tested high school students in that state |

### Brief Summary of Analysis

For this project, the data was broken down by state and by average score. Higher participation rates tend to show lower average scores, while lower participation tended to have higher average scores. The ACT show a slightly postive relationship to per pupil spending, while the SAT did not. Through analysis of descriptive statistics it is clear that some states are able to spend more per student than others, perhaps due to their spending models and proportion of funding that comes from federal government, state government, or local property taxes. Average funding spans over 16,000 dollars per pupil across all states, and it is difficult to know exactly which students are recieving that funding, and if those states are distributing wealth equitably. 


### Conclusion & Recommendations

In conclusion, the preliminary exploration of this data indicates there could be a slight relationship between school funding and standardized testing scores. While the ACT showed a stronger relationship between higher scores and per pupil spending, there was less of a case to be made for the SAT. 

This data proves a need to further explore the relationship between school funding (and by proxy socioeconomic status,due to many states' tendencies to draw school funding from property taxes) and standardized tests. While "race and parental income" ([Gavin Newsom, Oct 2019](https://www.gov.ca.gov/wp-content/uploads/2019/10/AB-751-Veto-Message.pdf)) may be strong correlating factors to higher performance on standardized tests, we must also examine the ways in which our schools provide support to students. 

[One study](https://www.future-ed.org/state-education-funding-concentration-matters/) suggests that some states would actually need to spend 3x more per pupil in districts with concentrated poverty, just to achieve average educational outcomes. This is due to the extra resources needed to combat the effects of students living in poverty.

If this were the case in our data, it might lead us to believe that there is *not* a relationship between funding and higher test scores, but it is necessary to understand external factors and bring in more data points to accurately understand if there is a relationship between these two elements. Until then, we will have to rely on insitutions of higher education to completely refuse to consider these test scores, in order to potentially even the playing field for students in poverty trying to learn and succeed. 