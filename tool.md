---
layout: default
title: Tool
permalink: /tool/
---

# Course Selection Tool
Selecting courses can be like navigating a jungle, especially the electives. For this reason, we now introduce a tool that can help you with:
- Filtering courses to only see your specific learning interests by using the legend.
- Navigating between courses based on their evaluation score and the amount of D&I students attending the course, which may act as an indicator to how relevant the course is.
- Inspecting other valuable course data by clicking the course dots.

<small>Hint: *Click the reset button ![reset](/Data%20load/reset.png) in the upper right corner to reset the navigation.*</small>

<iframe src="/Data load/Evaluation_plot.html" style="width: 1000px; height: 950px; border: none;"></iframe>

## Secondary tool
Selecting semi-elective courses can be a challenge too. To help the process, this tool only displays those.
<iframe src="/Data load/Semi-Elective_Evaluation_plot.html" style="width: 1000px; height: 950px; border: none;"></iframe>

### Disclaimer
- Only courses that have been passed by D&I Msc. students in the period 2020-2024 are included.
- The data related to any datapoint is taken from the course passed the latest by a D&I Msc. student.
- The evaluation score is the mean value of the evaluation data: 1.1, 1.2, 1.3, 1.4, 1.5, obtained from the DTU course base.
- Multiple categories may apply to a course, but in the name of simplicity, only one category has been assigned per course.
- All courses that are only passed by <=5 D&I students are anonymized data. In order to calculate the percentage of D&I students in a course, the number of D&I students have been set to 5.0 in these cases. This means that it is likely that courses with few students and <=5 D&I students have a higher percentage of D&I than in reality.

Want to read more about the trends of Design & Innovation students? Click the narrative button below, you can also click the home button to take you back to the landing page.

<div style="display: flex; justify-content: center; gap: 3rem; margin-top: 2rem;">
  <a href="/" style="
    background-color: #15717F;
    color: white;
    width: 150px;
    height: 150px;
    display: flex;
    align-items: center;
    justify-content: center;
    text-decoration: none;
    font-weight: bold;
    font-size: 1.2rem;
    border-radius: 0px;
    box-shadow: 0 4px 8px rgba(0,0,0,0.2);
    transition: transform 0.2s ease;
  ">
    Home
  </a>

  <a href="/narrative/" style="
    background-color: #15836D;
    color: white;
    width: 150px;
    height: 150px;
    display: flex;
    align-items: center;
    justify-content: center;
    text-decoration: none;
    font-weight: bold;
    font-size: 1.2rem;
    border-radius: 0px;
    box-shadow: 0 4px 8px rgba(0,0,0,0.2);
    transition: transform 0.2s ease;
  ">
    Narrative
  </a>
</div>