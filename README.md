# Mod3_Project
GradesAnalysis
Statistical analysis and hypothesis testing. 
We will start with a given hypothesis, and create three others on our own.

Process:
Engineer the data
Explore data to form three other hypotheses
Review our process to confirm conformity to proper experimental design
Select audience
Accept/Reject hypotheses
Create Jupyter-Notebook for presentation of our findings
Edit README to include explanation of the process, methodology and findings
Create presentation slides including original hypotheses, results and relevance to the audience
Present
Source
Grades data

Hypotheses (TBD)
Does time of day have a statistically significant correlation with the number of As earned in a course?
Do STEM fields have a statistically significant difference in the number of As earned when compared to the humanities?
Does your teacher have a statistically significant correlation with the number of As earned in a course?
Do your teachers' grading outcomes change over time?

Assignments
(Engineer/ETL) AND (Proper Experimental Design)
(Select Audience) - Data Scientist Trainees
Accept/Reject (Hyp. 1, Hyp. 2) AND (Hyp. 3, Hyp. 4)
Presentations (Jupyter) AND (README) AND (Slides)

Work Split/Schedule
Noah _ MaryJo ( Thursday)
Noah/MaryJo ( Friday_AM )
Noah _ MaryJo ( Friday_PM )

Data Science Module 3 Project involves the assessment of a data set from the University of Wisconsin at Madison, including courses and grades covering 2006 to 2017.

There are more than 9,000 courses in this dataset. There are nearly 200,000 course sections with grades, with 3 million grades reported in total. 18,000 instructors are also included in this dataset.

The objective of this study is statistical analysis and hypothesis testing. 

Question 1:  Do STEM fields have a statistically significant difference in the number of A's earned when compared to the humanities?
To assess whether there is a difference in the number of A's earned in STEM courses vs Humanities courses, we tested the "A ratio," which was the number of A's divided by the number of total grades for each class. Our STEM courses included 37,390 classes and our Humanities courses included 49,819 classes.

Our Null Hypothesis (H0) was: There is no difference in the A's earned in STEM classes vs. Humanities (Not STEM) classes.
Our Alternative Hypothesis (HA) was: There is a difference in the A's earned in these populations.

Our analysis returned a t-statistic of -10.9 and a pvalue of 1.285e-27, given 87207 degrees of freedom.

Negative t-value: The sign of a t-value tells us the direction of the difference in sample means. The mean of our STEM population was less than the mean of our Humanities population. In other words, on average, the A Ratio of STEM classes was lower than that of Humanities courses by 2.3%.

Question 2: Do STEM fields have a statistically significant difference in the number of A's earned when compared to the humanities?

To assess whether there is a difference in the number of A's earned in morning (AM) courses vs afternoon/evening (PM) courses, we tested the "A ratio," which was the number of A's divided by the number of total grades for each class. Our AM courses included 45,281 classes and our PM courses included 55,811 classes.

Our Null Hypothesis (H0) was: There is no difference in the A's earned in AM classes (before 12:00) vs. PM (after 12:00) classes.
Our Alternative Hypothesis (HA) was: There is a difference in the A's earned in these populations.

Our analysis returned a t-statistic of -41.9 with a pvalue of 0, given 101,090 degrees of freedom.

Negative t-value: The sign of a t-value tells us the direction of the difference in sample means. The mean of our AM population was less than the mean of our PM population. In other words, on average, the A Ratio of AM classes was lower than that of PM courses by 7.9%.


Given the p-value of 0, and an alpha of 0.05, the data show we can reject the Null Hypothesis.
Conclusion:  these data show there is a significant difference in the number of A's earned in AM classes vs. PM classes.


Given the p-value of 1.285e-27, and an alpha of 0.05, the data show we can reject the Null Hypothesis.
Conclusion:  these data show there is a significant difference in the number of A's earned in STEM classes vs. Humanities classes.


