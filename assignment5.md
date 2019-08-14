# Assignment 5 #

## "Interview" a dataset with three specific, interesting questions that you can find answers to. This can be related to your final project, but doesn't have to be. If you need a good starting point, I recommend CDC data. ##

**Submit a link to the dataset you found, your three questions, as well as the answers to those questions.**

[Chicago Public Schools - School Progress Reports SY1819](https://data.cityofchicago.org/Education/Chicago-Public-Schools-School-Progress-Reports-SY1/dw27-rash/data)

**Keep a data diary: write down all steps used to clean and analyze the data, including any Excel formulas. Excel formulas should be submitted using markdown language (between grave accent marks, also known as a backtick, commonly used to indicate code vs. text).**

CLEANING 

1. I deleted School_ID column

2. I deleted short_name column

3. I replaced “long_name” column header with “School_name”

4. I deleted primary_category column 

5. I combined city and state
-	 replaced “Illinois” with “IL”
-	Inserted a new colum and then used the formula =cell&”, “&cell

6. I formatted the phone number column (000) 000-000

7. I deleted CPS_School_Profile column

8. I deleted Website column

9. I deleted Progress_Report_Year column (it’s 2018)

10. I deleted Culture_Climate_Description column

11. I deleted Healthy_School_Certification_Description column

12. I deleted student_growth_description column 

13. I deleted student_atainment_description column

14. I deleted Creative_School_Certification_Description column 

15. I deleted Empty_Progress_Report_Message column

16. I deleted School_Survey_Rating_Description column

17. I deleted Supportive_School_Award_Desc column

18. I deleted State_School_Report_Card_URL column

**Interview questions:**

1. Does the type of neighborhood a school is in dictate the growth rate of its students?

3. How does culture climate affect a the attainment rate of its students? Do schools need to be more creative or ambitious?

4. How does a school obtain a healthy school certification? What is it's significance with a schools progress report with regards to its students?

5. Do school surveys and reports that involve the parents or families of students encourage changed or improvement (for the school and/or students)? 

6. Does the attainment rate of its students reliant on supportive schools (or schools that win awards)?

7. What is the intersection of supportive environment and culture climate?

**Write a sample headline and nut graf based on the most interesting answer among your three questions.**

IN THE GREATER CHICAGO AREA, ONLY 20 PUBLIC SCHOOLS PROVE TO HAVE A SUPPORTIVE ENVIRONMET AND AN ORGANIZED CULTURE CLIMATE

In the greater Chicago area, public schools are one of the main institutions where students can find an education. For the 2018-2019 school, 213,651 elementary students and 105,867 secondary students were enrolled in public schools in Chicago. In early August of 2017, $217 million of state funding was awarded to public schools by the then governer, Bruce Rauner. This assessment looks at the 655 CPS and the intersection of supportive environments and culture climate, and their affect on the attaintment rate and success students. 
 
**A drawing, mockup or sketch of at least one potential visualization. This can be electronic or on paper.**

[CPSchool's Culture Climate Rating](https://github.com/thomasilalaole/digitalframeworks-summer2019/blob/master/Screen%20Shot%202019-08-14%20at%2011.15.37%20AM.png)

[CPSchool's Supportive Environment Rating](https://github.com/thomasilalaole/digitalframeworks-summer2019/blob/master/Screen%20Shot%202019-08-14%20at%2010.48.20%20AM.png)

