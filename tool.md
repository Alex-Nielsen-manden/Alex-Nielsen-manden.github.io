---
layout: default
title: Tool
permalink: /tool/
---

# Course Selection Tool
Selecting courses can be like navigating a jungle, especially the electives. For this reason, we now introduce a tool that can help you with:
- Filtering courses to only see your specific learning interests by using the legend.
- Navigating between courses based on their evaluation score and the amount of D&I students attending the course, which may act as an indicator to how relevant the course is.
- Inspecting other valueable course data by clicking the course dots.

<small>Hint: *Click the reset button ![reset](/Data%20load/reset.png) in the upper right corner to reset the navigation.*</small>

<iframe src="/Data load/Evaluation_plot.html" style="width: 1000px; height: 1000px; border: none;"></iframe>

## Secondary tool
Selecting semi-elective courses can be a challenge too. To help the process, this tool only displays those.
<iframe src="/Data load/Semi-Elective_Evaluation_plot.html" style="width: 1000px; height: 800px; border: none;"></iframe>

### Disclaimer
- Only courses that have been passed by D&I Msc. students in the period 2020-2024 are included.
- The data related to any datapoint is taken from the course passed the latest by D&I Msc. students.
- The evaluation score is the mean value of the evaluation data: 1.1, 1.2, 1.3, 1.4, 1.5, obtaned from the DTU course base.
- If a course fits within multiple learning categories, the legend filter only applies the filter based on the first learning category.
- All courses that are only passed by <=5 D&I students are anonymized data and has been assigned 5.0 as the value in order to calculate the percentage of D&I students in a course. This means that it is likely that courses with few students have a higher percentage of D&I than in reality.