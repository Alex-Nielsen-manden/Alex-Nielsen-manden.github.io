---
layout: default
title: Narrative
permalink: /narrative/
---

# Introduction

This dataset includes course information for MSc Design and Innovation students at the Technical University of Denmark, covering the period from 2020 to the 2024. It shows how many students from the program have taken each course, what their average grades were, and how they rated the courses overall.

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

To start out with, why don't we look at those categories to see how they compare amongst each other.

<img src="/Data load/elective_grades_evaluation.png" alt="Time series" style="display: block; width: 800px; margin-left: 0; margin-right: auto;" />

This plot consists of data from data from the entire dataset and thus represents an average over the years. By a first quick glance we see that the average course rating over all categories are relatively similar, the outliers here are supply chain that scores the lowest and medtech that scores the highest. 
Since the axis are normalized in terms of course rating and grades the plot would make it easy to see if there is a correlation between high average grades and high scores. Which actually looks like the case with the exeption of Circularity & Sustainability, MedTech, Manufacturing & Materials and Technical Competences which are all rated relatively higher than than the average grade. 
One very notable issue with the data here is however that the course rating is based on data from all students while the average grade only pulls data from Design & Innovation students.
This prompts the question of whether those before mentioned categories are amongst the least popular amongst D&I students since their average grade is lower relative to the course rating.

<img src="/Data load/popularity_by_category.png" alt="Time series" style="display: block; width: 800px; margin-left: 0; margin-right: auto;" />

