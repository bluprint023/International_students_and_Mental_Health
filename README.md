# International_students_and_Mental_Health
This is an attempt to determine if studying in a foreign country affects one's mental health based on this information gathered from students in Japan
![image](https://github.com/user-attachments/assets/f4fa6d01-f1d6-4644-ad8c-8f616f98dd8f)


Does going to university in a different country affect your mental health? A Japanese international university surveyed its students in 2018 and published a study the following year that was approved by several ethical and regulatory boards.

The study found that international students have a higher risk of mental health difficulties than the general population, and that social connectedness (belonging to a social group) and acculturative stress (stress associated with joining a new culture) are predictive of depression.


Explore the `students` data using PostgreSQL to find out if you would come to a similar conclusion for international students and see if the length of stay is a contributing factor.

Here is a data description of the columns you may find helpful.
Field Name 	Description
inter_dom 	Types of students (international or domestic)
japanese_cate 	Japanese language proficiency
english_cate 	English language proficiency
academic 	Current academic level (undergraduate or graduate)
age 	Current age of student
stay 	Current length of stay in years
todep 	Total score of depression (PHQ-9 test)
tosc 	Total score of social connectedness (SCS test)
toas 	Total score of acculturative stress (ASISS test)



Key Findings:
1. Comparison: International vs. Domestic Students
Depression (PHQ-9): Contrary to the potential expectation of higher risk for international students, the average depression score was slightly lower for international students (Avg = 8.04) compared to domestic students (Avg = 8.61) in this dataset.
Social Connectedness (SCS): Average social connectedness scores were very similar between the two groups, with domestic students scoring marginally higher (Dom Avg = 37.64, Inter Avg = 37.42).
Acculturative Stress (ASISS): As anticipated, international students reported significantly higher average acculturative stress (Avg = 75.56) than domestic students (Avg = 62.84).
2. Analysis: International Students by Length of Stay
Sample Size: The number of students decreases significantly for longer stays. Findings for stays of 4 years or more are based on very small sample sizes (N=1 to N=14) and must be interpreted with extreme caution.
Depression (PHQ-9): There is no clear trend of decreasing depression with longer stays based on these averages. Scores appear to increase slightly from year 1 (Avg = 7.48) to year 3 (Avg = 9.09). The scores for years 4+ fluctuate significantly, likely due to the very small and potentially unrepresentative sample sizes.
Social Connectedness (SCS): No clear pattern of improvement emerges. Average scores slightly decrease from year 1 (Avg = 38.11) to year 4 (Avg = 33.93). The subsequent years show considerable variability influenced by the small N.
Acculturative Stress (ASISS): The average stress score seems to increase from year 1 (Avg = 72.80) up to year 4 (Avg = 87.71) and peaks dramatically in year 5 (Avg = 91.00, N=1), before dropping off in later years (based on very few students). This trend is contrary to the expectation that stress might decrease as students adapt over time.
Discussion:
This analysis, based purely on average scores, presents some nuances compared to the general findings often cited regarding international student mental health. While international students clearly experience higher acculturative stress, they did not show higher average depression scores than domestic students in this specific dataset sample.
Furthermore, the examination of length of stay does not clearly support the hypothesis that longer stays directly correlate with improved mental health indicators (lower depression/stress, higher connectedness) based on these averages. The data for the initial years (1-3, with larger samples) suggests depression and acculturative stress might actually increase slightly during this period. The significant drop-off in sample size for longer durations makes it difficult to draw reliable conclusions about long-term adaptation trends from this average-based analysis alone.
Conclusion:
Based on average scores from this dataset:
International students experience significantly higher acculturative stress but not higher average depression scores compared to domestic students.
There is no clear evidence from these averages that longer stays lead to progressively lower depression or acculturative stress, or higher social connectedness for international students. Some indicators appear to worsen slightly in the initial years.
It is crucial to remember that this report is based solely on group averages. The original study likely employed more sophisticated statistical methods (e.g., regression analysis) that could reveal predictive relationships between factors like social connectedness, stress, and depression, potentially controlling for other variables, which might explain the difference between these findings and the study's reported conclusions. The limitations, particularly the small sample sizes for longer stays, highlight the need for caution when interpreting the trends related to stay duration.
