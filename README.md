# Week 3 Project
Brianna Wilson Green  
June 26, 2021

This week I analyzed data from [Oregon's Department of Education](https://www.ode.state.or.us/data/reportcard/media.aspx) for the 2019-2020 school year. This data tracks metrics on a school district level, including: 

Race demographics of students and teachers
4-year graduation rates by socioeconomic status, disability status, and race
Teacher experience
The number of librarians, counselors, and administrators

Possible shortcomings of the data:
It was collected during the 2019-2020 school year, which was greatly affected by the pandemic and could have skewed several metrics in ways that hasn't happened in previous years
Many school districts in Oregon are tiny (the smallest have only 7 students!), so many school districts have redacted data that could be personally-identifiable for such a small population
Because of the wide disparity in school district sizes, it's not an apples-to-apples comparison, even when normalized

A summary of my analysis:
First, I narrowed down the columns from ~60 to ~15 of the ones I considered most relevant
Using those columns, I calculated ratios, such as librarians to students and counselors to students, and put them in new columns
I made ~20 plots and tables to get a sense of relationships in the data. Some things I found:

Though there is an increase in the percentage of Teachers of Color as the percent of Students of Color increases, it's not by much, and the teacher population remains mostly White despite widely varying racial demographics of students between districts

There is a relationship between higher % White students and more licensed librarians in those districts

For the subset of districts that do have licensed librarians, there is a relationship between more librarians & a higher % of economically disadvantaged students graduating on time. Perhaps this is because districts with more resources can afford more librarians, and have better resources for poorer students

There doesn't seem to be a relationship between more counselors per student and economically disadvantaged students graduating on time

There is a normal distribution of the number of districts where economically disadvanted students graduate on-time at varying rates
Same with disabled students, except the distribution shows that less students with disabilities graduate on-time

There are only 15 districts in the state with enough Black students to not redact the data on their Black students

In those districts, White students tend to graduate on-time at higher rates

There's a positive correlation between the proportion of White students and the on-time graduation rates of students with disabilities, suggesting that those districts have more resources

There's a slight negative correlation between the proportion of Students of Color and the student/teacher ratio






