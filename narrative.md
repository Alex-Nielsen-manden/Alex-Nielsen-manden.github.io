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

That chart includes all courses, both mandatory and elective. Since students don’t have much choice in mandatory courses, let’s isolate the elective courses to see if the trend changes:

<img src="/Data load/average_grade_semester_electives.png" alt="Time series" style="display: block; width: 800px; margin-left: 0; margin-right: auto;" />

Here, we observe a more pronounced downward trend and generally lower grades, suggesting that D&I students tend to perform slightly worse in their electives compared to core subjects. To better understand this, we’ve grouped the electives into ten categories:

- *Circularity & Sustainability*
- *Design for People*
- *Management & Business*
- *MedTech*
- *Manufacturing & Materials*
- *Product Design*
- *Smart Products*
- *Supply Chain*
- *Systems Engineering*
- *Technical Competences*

Let’s compare these categories in terms of average grades and course evaluations:

<img src="/Data load/elective_grades_evaluation.png" alt="Time series" style="display: block; width: 1000px; margin-left: 0; margin-right: auto;" />


This plot is based on the full dataset and reflects average values across the years. At first glance, course ratings appear relatively consistent across categories, with a few exceptions: *Supply Chain* stands out with the lowest ratings, while *MedTech* receives the highest.

Because both axes are normalized, this chart also gives insight into the relationship between average grades and student evaluations. In general, higher course ratings seem to correlate with higher grades. However, some categories—such as *Circularity & Sustainability*, *MedTech*, *Manufacturing & Materials*, and *Technical Competences* receive higher than average ratings despite lower average grades from D&I students.

One important caveat: while course ratings are based on feedback from all students, the average grade data only reflects performance by D&I students. This discrepancy raises an interesting question—could these higher-rated but lower-performing categories be less popular among D&I students, leading to a lower average grade?

To explore that, let’s look at the popularity of each category among D&I students

<img src="/Data load/popularity_by_category.png" alt="Time series" style="display: block; width: 1000px; margin-left: 0; margin-right: auto;" />

From this plot, we can see that *Technical Competences*, which has the lowest average grade among D&I students, is also among the least popular categories. 

Let's take a look at the categories on a yearly basis to see if anything interesting appears there.

<img src="/Data load/popularity_by_category_yearly.png" alt="Time series" style="display: block; width: 1000px; margin-left: 0; margin-right: auto;" />

We immediately notice significant changes in the distribution of categories over the years. Notably, no single year includes all 10 categories, and most strikingly, *Design for People* the most popular category among D&I students—is completely absent from 2024.

This aligns with a major restructuring of the MSc Design and Innovation program that took place in the summer of 2023. Maybe some of the most popular electives has changed status to mandatory or program-specific courses (which we refer to here as semi-electives). 

To test this hypothesis, let’s take a look at the popularity of non-elective courses (mandatory and program-specific) in 2024


<img src="/Data load/popularity_by_category_2024_non_electives.png" alt="Time series" style="display: block; width: 1000px; margin-left: 0; margin-right: auto;" />

The data seems to confirm our suspicion: Design for People remains the most popular category among D&I students—it has simply shifted from being offered as an elective to being part of the core or semi-elective curriculum.

With this knowledge let's take look at the most popular elective courses over the years.

<img src="/Data load/top_10_electives.png" alt="Time series" style="display: block; width: 1000px; margin-left: 0; margin-right: auto;" />

A clear trend emerges: D&I students have been taking fewer electives over time, with the most dramatic drop occurring between 2023 and 2024. This aligns with the curriculum restructuring, which moved many previously elective courses into the program-specific core.

One illustrative example is *Holistic Design* course number 42090, a course that consistently ranked among the most popular electives but vanished from the elective list in 2024. That’s because it was reclassified as a mandatory course under the new structure.

This dramatic reduction could suggest that the current curriculum aligns well with students’ interests, as there appears to be little incentive to look beyond the program-specific offerings

Has this just made you even more confused regarding what courses to take? Try our course finding tool to help you find the right course for you by clicking the button below.
<div style="display: flex; justify-content: center; align-items: center; margin-top: 20px;">
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