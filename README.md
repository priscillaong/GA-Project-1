# GA Project 1

# Problem Statement
This project aims to <br>
(1) find the correlation of participation rate and SAT score to determine if a higher average SAT score constitutes to a State which performs better academically; and <br>
(2) find the trends of SAT participation rates in the US between 2017 and 2019 after a change in test format in 2016 and identify States with decreasing participation rates. <br>

This would allow the College Board to be informed on the correlation of SAT scores and participation rates and work on improving participation rates across the US.

# Data Dictionary
|Feature|Type|Dataset|Description|
|---|---|---|---|
|state|object|2017/2018/2019 SAT Scores by State|State/Capital City in the US|
|evidence_based_reading_and_writing_2017|integer|2017 SAT Scores by State|Average Evidence-Based Reading and Writing Score (between 200-800)|
|math_2017|integer|2017 SAT Scores by State|Average Math Score (between 200-800)|
|total_2017|integer|2017 SAT Scores by State|Total SAT Score - Summation of Average Evidence-Based Reading and Writing and Math Score (between 400-1600)|
|participation_rate_2017|float|2017 SAT Scores by State|SAT Participation Rate of the State/Capital City in the US as a decimal|
|evidence_based_reading_and_writing_2018|integer|2018 SAT Scores by State|Average Evidence-Based Reading and Writing Score (between 200-800)|
|math_2018|integer|2018 SAT Scores by State|Average Math Score (between 200-800)|
|total_2018|integer|2018 SAT Scores by State|Total SAT Score - Summation of Average Evidence-Based Reading and Writing and Math Score (between 400-1600)|
|participation_rate_2018|float|2018 SAT Scores by State|SAT Participation Rate of the State/Capital City in the US as a decimal|
|evidence_based_reading_and_writing_2019|integer|2019 SAT Scores by State|Average Evidence-Based Reading and Writing Score (between 200-800)|
|math_2019|integer|2019 SAT Scores by State|Average Math Score (between 200-800)|
|total_2019|integer|2019 SAT Scores by State|Total SAT Score - Summation of Average Evidence-Based Reading and Writing and Math Score (between 400-1600)|
|participation_rate_2019|float|2019 SAT Scores by State|SAT Participation Rate of the State/Capital City in the US as a decimal|

# Summary of Analysis
(1) There is a negative correlation between participation rate and SAT score <br>
(2) There is a increasing trend in SAT participation rates across the US States from 2017 - 2019. Some exceptions include DC, New Hampshire, Hawaii, Nevada and Montana.

# Conclusion and Recommendations
Based on the above EDA and Data Visualisation, we can conclude that there is a negative correlation between participation rates and SAT scores and a higher SAT score does not means that a State performs better academically. Most of the times, such States have higher SAT scores because it is not a high school graduation requirement and students who take such tests are probably those who perform well academically and are taking it as part as a college entrance requirement. TThe College Board can consider to educate the media and general public to prevent the spread of misinformation on the internet.

In general, there is a rising trend in participation rates for SAT in the US from 2017 to 2019 (with the exception of DC, New Hampshire, Hawaii, Nevada and Montana) as the SAT is still a high school graduating requirement in some of these States and SAT scores are a college entrance requirement. With a growing number of selective colleges and universities dropping out of admissions test requirement, the participation rates of SAT across the US have drop significantly in 2022 (1.7 million students as of 28 Sep 2022) as compared to pre-pandemic (2019) rates (2.2 million students in 2019) ([*source*](https://www.washingtonpost.com/education/2022/10/13/act-sat-testing-scores-2022/)). The 2020 and 2021 SAT Scores by State datasets can be analysed to further identify the States with decreased participation rates compared to pre-pandemic.

This project aimed to study how the change in 2016 SAT test format would affect the participation rates between 2017 - 2019. 2019 saw a 4% increase in students taking the SAT as compared to 2018. The increase was driven in large part by the growing number of states that allow schools to administer the test during the school day, typically free of charge ([*source*](https://www.usnews.com/news/education-news/articles/2019-09-24/more-students-are-taking-the-sat-than-ever-before)). The College Board can consider such initiatives to boost SAT participation rates in the States.
