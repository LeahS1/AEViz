'''
# AEViz
---INTRODUCTION---
This dataset is comprised of adverse events reported by sites participating in a clinical trial. This dataset only contains those subjects who have either completed or withdrawn from the clinical trial and reported an adverse event. This notebook was created for the purpose of demonstrating various visualizations of the data that may provide useful insight to data managers. General questions answered in this analysis include:

1)How many subjects experienced AEs?
There were 22 unique subjects who experienced adverse events. These subjects experienced a total of 55 adverse events to date.

2)How many events did each subject experience?
About 59% of subjects experienced 1 or 2 adverse events. Out of the 22 subjects that experienced adverse events, 8 subjects (36.36%) experienced one adverse event and 5 subjects (22.73%) experienced two adverse events. One subject experienced 6 (max) adverse events.

3) How long did these adverse events last?
We see that many adverse events resolved the same day. Most adverse events (52.7%) resolved within 3 days. The average duration was 6.3 days. There are 9 ongoing events.

4)What adverse events are being reported?
We see that most reported adverse event terms are related to the right or left knee with edema occurrence. Taking a closer look at the most common bigrams and trigrams, we see that many of the adverse events are related to elevated blood pressure and edema around the right or left knee. There also seems to be many occurrences of nausea and urinary tract infections. The reports are coded into higher level terms, with Nausea and vomiting symptoms referenced the most (8 occurrences), followed by Coronavirus infections (5), Joint related signs and symptoms (5), and Injection site reactions (5). Given that this trial was carried out during the pandemic, it's possible that the reports of coronavirus infection are not related to the study treatment, but the other three high level terms may be.

5)Taking a deeper look at individual subjects: 
Taking a closer look at the subject with 6 adverse events reported, we see that this subject has a concomitant health condition (hypertension) that could potentially lead to one of the other reported adverse events (headache). Two of their reported adverse events were related to the left knee. If we look at all reported occurrences of edema, 4 reports resolved within a day, 2 were ongoing, and the remaining 3 resolved in 6 days. Looking at the Lowest Level Term, we see that 5 of the reports are related to the injection site, so the edema might be a short term side effect of the injection.

---CONCLUSION---
This analysis of adverse event data from this clinical trial suggests that the study treatment, relating to an injection in or around the knees, may be leading to edema, nausea, and elevated blood pressure in subjects. Twenty two subjects experienced 55 adverse events, 9 of which were ongoing (possibly long  term health conditions). While most subjects experienced 2 adverse events over the course of the study, some experienced up to 6. Most of the adverse events resolved within 3 days, with many resolving the same day.

Further analysis of the dataset should not only consider the severity of adverse events but also explore potential relationships and associations between events. By reviewing subjects who experienced multiple adverse events, researchers can gain a better understanding of potential concomitant events that may be contributing to the observed effects. Additionally, external data such as injection timepoints and locations can provide valuable insights into the onset and distribution of adverse events. By taking a comprehensive approach to analyzing the data, researchers can uncover important patterns and trends that may have significant implications for future studies and clinical practice.
'''
