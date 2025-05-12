---
layout: default
title: Narrative
permalink: /narrative/
---

# Introduction

This dataset presents course information for MSc Design and Innovation students at the Technical University of Denmark (DTU) from 2020 to 2024. It details how many students from the program enrolled in each course, their average grades, and overall course ratings.

Just for fun, let’s explore how average grades have evolved over the past five years:

<img src="/Data load/average_grade_semester.png" alt="Time series" style="display: block; width: 800px; margin-left: 0; margin-right: auto;" />

Overall, the trend appears fairly stable, with only a slight downward slope—nothing too dramatic. However, there is a noticeable spike in grades during the fall semester of 2020, which directly followed the first COVID-19 lockdown. Interestingly, the exam period that semester coincided with Denmark’s second lockdown. This may have led to more lenient grading by examiners or, perhaps more plausibly, a decline in exam quality due to the sudden transition to remote assessments.

This however is a look at all courses including mandatory courses. Since the students has no say, so to speak regarding those, let's try to make the same plot only looking at elective courses. 

<img src="/Data load/average_grade_semester_electives.png" alt="Time series" style="display: block; width: 800px; margin-left: 0; margin-right: auto;" />

Here, we see a more noticeable downward trend and generally lower grades—suggesting that D&I students may not perform as well in their elective courses compared to core subjects. Let’s take a closer look at what might be driving this pattern.

To better get an overview of the different courses we have diveded them into 10 different catagories namely

- Circularity & Sustainability
- Design for People
- Management & Business
- MedTech
- Manufacturing & Materials
- Product Design
- Smart Products
- Supply Chain
- Systems Engineering
- Technical Competences

Let’s explore how these categories compare to one another in terms of student performance and course rating.

<img src="/Data load/elective_grades_evaluation.png" alt="Time series" style="display: block; width: 800px; margin-left: 0; margin-right: auto;" />

This plot consists of data from data from the entire dataset and thus represents an average over the years. By a first quick glance we see that the average course rating over all categories are relatively similar, the outliers here are supply chain that scores the lowest and medtech that scores the highest. 
Since the axis are normalized in terms of course rating and grades the plot would make it easy to see if there is a correlation between high average grades and high scores. Which actually looks like the case with the exeption of Circularity & Sustainability, MedTech, Manufacturing & Materials and Technical Competences which are all rated relatively higher than than the average grade. 
One very notable issue with the data here is however that the course rating is based on data from all students while the average grade only pulls data from Design & Innovation students.
This prompts the question of whether those before mentioned categories are amongst the least popular amongst D&I students since their average grade is lower relative to the course rating.

<img src="/Data load/popularity_by_category.png" alt="Time series" style="display: block; width: 800px; margin-left: 0; margin-right: auto;" />

By looking at this plot we can see that the category of Techinical competencies which has the lowest average grade amongst D&I student also is relatively 


<img src="/Data load/popularity_by_category_yearly.png" alt="Time series" style="display: block; width: 800px; margin-left: 0; margin-right: auto;" />





Has this just made you even more confused regarding what courses to take? Try our course finding tool to help you find the right course for you.
  <a href="/tool/" style="
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
    Tool
  </a>
</div>