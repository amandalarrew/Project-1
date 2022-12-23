# ![](https://ga-dash.s3.amazonaws.com/production/assets/logo-9f88ae6c9c3871690e33280fcf557f33.png) Which Scores Have the Most Earning Potential? A University Recruitment Analysis Based on SAT Scores and Intended College Major.

### Overview

In this project I examined the most lucrative college undergraduate majors. With this information, I then examined trends in 2017-2019 SAT data by intended college major and by average scores per U.S. state. Scores and participation rates were analyzed to uncover underlying patterns between SAT scores and undergraduate major choice in an effort to provide suitable recommendations on which states to recruit prospective students, and where to allocate university program funding.

The data used for this project are from the following sources: [Wall Street Journal](https://www.wsj.com/public/resources/documents/info-Degrees_that_Pay_you_Back-sort.html), [2019 SAT by College Major](http://localhost:8889/files/project_1/data/sat_2019_by_intended_college_major.csv?_xsrf=2%7C4a6b3cac%7Cfeba3ecee7ec64ff988cd860a0ed4f4c%7C1665416297), [2017 SAT by State](http://localhost:8889/files/project_1/data/sat_2017.csv?_xsrf=2%7C4a6b3cac%7Cfeba3ecee7ec64ff988cd860a0ed4f4c%7C1665416297), [2018 SAT by State](http://localhost:8889/files/project_1/data/sat_2018.csv?_xsrf=2%7C4a6b3cac%7Cfeba3ecee7ec64ff988cd860a0ed4f4c%7C1665416297), [2019 SAT by State](http://localhost:8889/files/project_1/data/sat_2019.csv?_xsrf=2%7C4a6b3cac%7Cfeba3ecee7ec64ff988cd860a0ed4f4c%7C1665416297)

---

### Summary of Findings and Recommendations 

The highest earning majors are Engineering, Computer Science, Physics and Economics. Those who intend to pursue these majors tend to score higher on all portions of the SAT than those who do not. The SAT math section has the largest score difference between the highest earning majors and all other majors. The states that had favorable Total, EBRW and Math SAT scores were consistent across 2017-2019. Finally, states with higher participation rates have lower test scores. 

Based on the data examined, it is recommended that funding and scholarships be allocated to the Engineering, Computer Science, Physics and Economics departments, as they are the most lucrative majors. Students who intend to pursue one of the above degrees score on average 6-8% higher in all areas of the SAT, with the biggest discrepancy being math. While there are key states to recruit that have favorable test scores (Iowa, Kansas, Kentucky, Louisiana, Minnesota, Mississippi, Missouri, Montana, Nebraska, North Dakota, South Dakota, Tennessee, Wisconsin and Wyoming), this data fails to provide an accurate representation of high performing students among states with higher participation rates. More data would be required to make fair recruitment recommendations. Finally, it is recommended that to grow the above programs, a portion of the department funding goes toward programs that give high-school students access to math education, as this is a barrier of entry for pursuing one of the highest earning degrees.

---

### Data Dictionary 

|Feature|Type|Dataset|Description|
|---|---|---|---|
|**states**|*object*|2017-2019 SAT|State names for all 50 states in the United States, including District of Columbia| 
|**2017_participation_rate**|*float*|2017-2019 SAT|The percent of SAT participation in each state for 2017|
|**2017_ebrw_score**|*integer*|2017-2019 SAT| State average score for SAT 'Evidence Based Reading and Writing" section in 2017|
|**2017_math_score**|*integer*|2017-2019 SAT| State average score for SAT 'Math' section in 2017|
|**2017_total_score**|*integer*|2017-2019 SAT| State average total score for SAT in 2017|
|**2018_participation_rate**|*float*|2017-2019 SAT|The percent of SAT participation in each state for 2018|
|**2018_ebrw_score**|*integer*|2017-2019 SAT| State average score for SAT 'Evidence Based Reading and Writing" section in 2018|
|**2018_math_score**|*integer*|2017-2019 SAT| State average score for SAT 'Math' section in 2018|
|**2018_total_score**|*integer*|2017-2019 SAT| State average total score for SAT in 2018|
|**2019_participation_rate**|*float*|2017-2019 SAT|The percent of SAT participation in each state for 2019|
|**2019_ebrw_score**|*integer*|2017-2019 SAT| State average score for SAT 'Evidence Based Reading and Writing" section in 2019|
|**2019_math_score**|*integer*|2017-2019 SAT| State average score for SAT 'Math' section in 2019|
|**2019_total_score**|*integer*|2017-2019 SAT| State average total score for SAT in 2019|
|**total_mean**|*float*|2017-2019 SAT|State average total score over time calculated from 2017-2019|
|**total_median**|*float*|2017-2019 SAT|State median total score over time calculated from 2017-2019|
|**ebrw_mean**|*float*|2017-2019 SAT|State average ebrw score over time calculated from 2017-2019|
|**ebrw_median**|*float*|2017-2019 SAT|State median ebrw score over time calculated from 2017-2019|
|**math_mean**|*float*|2017-2019 SAT|State average math score over time calculated from 2017-2019|
|**math_median**|*float*|2017-2019 SAT|State median math score over time calculated from 2017-2019|
|**rate_mean**|*float*|2017-2019 SAT|State average participation rate over time calculated from 2017-2019|
|**rate_median**|*float*|2017-2019 SAT|State median participation rate over time calculated from 2017-2019|
|**indended_college_major**|*object*|SAT by Indended College Major 2019| Undergraduate major names that SAT/ACT test takers selected as their intended college major|
|**num_test_takers**|*integer*| SAT by Inteneded College Major 2019| Number of SAT test takers that selected the specific major as their intended college major in 2019|
|**total_percent**|*float*| SAT by Intended College Major 2019| Percent(%) of overall test takers that selected the specific major as their intended college major in 2019|
|**total_score**|*integer*| SAT by Intended College Major 2019| Average total SAT score by intended college major in 2019|
|**ebrw_score**|*integer*| SAT by Intended College Major 2019| Average 'Evidence Based Reading and Writing' SAT score by intended college major in 2019|
|**math_score**|*integer*| SAT by Intended College Major 2019| Average 'Mathematics' SAT score by intended college major in 2019|
|**undergraduate_major**|*object*| Degrees that Pay| Undergraduate major names used to identify the most lucrative careers post-graduation|
|**starting_median_salary**|*float*|Degrees that Pay| Graduates median starting salary by undergraduate major|
|**mid_career_median_salary**|*float*|Degrees that Pay| Graduates median mid career salary by undergraduate major|
|**percent_delta_starting_to_mid_career**|*float*| Degrees that Pay| Percent(%) difference between graduates median mid career salary and median starting salary by undergraduate major|
|**mid_career_10th_percentile**|*float*| Degrees that Pay| Graduates mid-career salary within the 10th percentile by undergraduate major (Ie. 10% of graduates with the specified major are making less mid career, while 90% are making more)|
|**mid_career_25th_percentile**|*float*| Degrees that Pay| Graduates mid-career salary within the 25th percentile by undergraduate major (Ie. 25% of graduates with the specified major are making less mid career, while 75% are making more)|
|**mid_career_75th_percentile**|*float*| Degrees that Pay| Graduates mid-career salary within the 75th percentile by undergraduate major (Ie. 75% of graduates with the specified major are making less mid career, while 25% are making more)|
|**mid_career_90th_percentile**|*float*| Degrees that Pay| Graduates mid-career salary within the 90th percentile by undergraduate major (Ie. 90% of graduates with the specified major are making less mid career, while 10% are making more)|

---

