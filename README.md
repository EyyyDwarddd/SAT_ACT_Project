# SAT/ACT Project


 ## Contents:
 
- [Problem Statement](#Problem-Statement)  
- [Data](#Data)
- [Outside Research](#Research)
- [Data Analysis](#Data-Analysis)
- [Conclusions and Recommendations](#Conclusions-and-Recommendations)


## Problem Statement:

I, as an aspiring data scientist, have been hired by the great State of California to identify its counties who have high participation rates for these tests, low participation rates for these tests, find plausible explanations why this is the case, as well as figure out solutions on how the state can allocate their budget/resources to provide students the program(s) necessary to ace this exam.



## Background:

College preparatory exams such as the SAT’s and ACT’s have played a huge determining factor for the success of California high school students throughout their college career; where high school faculty and parents alike have poured millions of dollars collectively in ensuring young adults achieve the best score possible. 
Although there have been massive backlash against college preparatory testing, (i.e. if they truly measure intelligence, the unfair advantage that students with a higher socio-economic background can spend hundreds, even thousands of dollars for SAT tutors and prep classes, there are still beneficial reasons why California should invest in, such as: 

1. Being exempt from certain remedial courses in college/university
2. A High SAT/ACT score can offset a lower GPA
3. SAT/ACT scores can help enhance a sparse resume
4. Increase access to scholarship opportunities

## Data

* [datafile 1](/Users/edwardmendoza/Documents/GA/project_1/act19_ca_df_final_cleaned): Final ACT Data
* [datafile 2](/Users/edwardmendoza/Documents/GA/project_1/sat19_ca_df_cleaned_final ): Final SAT Data


## Data Dictionary

|Feature|Type|Dataset|Description|
|---|---|---|---|
|rtype|object|ACT|Record Type: C=County, D=District, S=School, X=State|
|school_name|object|ACT|County code for California counties|
|district_name|object|ACT|Name of School District, i.e. YCUSD|
|county_name|object|ACT|County name, i.e. Sutter|
|students_enrolled|int64|ACT|Number of students enrolled|
|avg_reading_score|float64|ACT|Average Reading Score|
|avg_english_score|float64|ACT|Average English Score|
|avg_math_score|float64|ACT|Average Math Score|
|avg_science_score|float64|ACT|Average Science Score|
|scores_over_20|float64|ACT|Number of Test Takers whose ACT Composite Scores are greater or equal to 21|
|pct_scores_over_20|int64|ACT|Percent of test takers whose ACT composite scores are greater or equal to 21|

|Feature|Type|Dataset|Description|
|---|---|---|---|
|rtype|object|SAT|R|
|school_name|object|SAT|CA school name|
|district_name|object|SAT|CA district name|
|county|object|SAT|CA county name|
|enroll_12|float64|SAT|# of Seniors Enrolled|
|num_of_senior_test_takers|float64|SAT|Seniors taking the SAT|
|12th_grade_english_benchmark_passed|int64|SAT|12th graders who passed the English benchmark|
|12th_grade_english_benchmark_percent|float64|SAT|Percent of 12th graders who passed the English benchmark|
|12th_grade_math_benchmark_passed|int64|SAT|Seniors who passed the math benchmark|
|12th_math_percent|float64|SAT|Percent of Seniors who passed the Math benchmark|
|11th_graders_enrolled|float64|SAT|# of Juniors Enrolled|
|11th_grade_test_takers|float64|SAT|Juniors who took the test|
|11th_grade_english_benchmark_passed|float64|SAT|Juniors who passed the English benchmark|
|11th_grade_english_benchmark_percent|float64|SAT|Percent of Juniors who passed the English benchmark|
|11th_grade_math_benchmark_passed|float64|SAT|Juniors who passed the Math benchmark|
|11th_grade_math_benchmark_percent|float64|SAT|Percent of Juniors who passed the Math benchmark|
|total_12th_graders_passed|float64|SAT|Total number of Seniors who passed both benchmarks|
|total_12_graders_passed_%|float64|SAT|Percent of Seniors who passed both benchmarks|
|total_11th_graders_passed|float64|SAT|Total Juniors who passed both benchmarks|
|total_11th_graders_passed_%|float64|SAT|Percent of Juniors who passed both benchmarks|
|total_highschoolers_passed|float64|SAT|Total Number of Juniors and Seniors who passed|
|total_eligible_students_enrolled|float64|SAT|Total Number of Juniors and Seniors enrolled in high school|
|total_test_takers|float64|SAT|Total number of Juniors and Seniors who enrolled for an exam|
|pct_test_takers_to_enrolled|float64|SAT|Percentage of students who took the test to the number of students enrolled|

## Outside Research:

This is where you would want to talk about any outside research or resources you've brought into the project. Why are they relevant? Where did you get these resources? How did you use them? What did you find? How does it relate to your problem statement?
    

## Data Analysis:

What I was aiming towards for in my data analysis was to identify the counties with the lowest and highest participation rates and consider the factors that might play a role with the reasons why this is. 

What was striking to me was that in terms of the ACT, I noticed that several small counties in terms of population had the highest percentage in terms of participation, which are Tehama, Modoc, and Siskiyou county. I believe the reason why this was the case was that since there was already a smaller pool of high school students to begin with. 

    
## Conclusions and Recommendations:

It appears that some societal forces are at play in terms of secondary education attainment. It appears that counties that are considered more rural have lower participation rates than ones that are less rural. This might be due to how education is being funded in the state of California. A sizable portion is is funded through property taxes, and home prices tend to be more expensive in counties near the Bay Area or are touching the coastline. I recommend some legislative action to have SAT prep courses be an elective in high school, almost like how foreign language and art courses are electives. 

This would ensure that every high school student in California would have access to these SAT prep courses as an elective. This would benefit students in lower participating counties by giving them access to SAT prep courses as an elective in school, and this would also benefit high school students from upper middle-class backgrounds because it would save their parents/legal guardians exorbitant sums of money to pay for SAT tutors when their child could gain the same benefit from their high school. 
