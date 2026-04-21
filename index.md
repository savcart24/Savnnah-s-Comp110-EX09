---
# Do not edit the text between these lines!
layout: default
---

# Comp 110 Exercise 09 Results

## main question

I wanted to investigate if spending more time learning to navigate VS Code would be beneficial to first time coders. To do this I looked if less experinced coders found the course more difficult and went to office hours more frequently to establish is a need to spending more time on the basics would be needed.

## Analysis

In order to do this I needed to combine the data from both classes into one dictionary so that all data was avaliable to use. I used the concat function here in order to combine both classes. Next I isolated the columns which were useful to my research question which were "prior_exp", "ap_principles", "ap_a", "other_comp", "languages", "difficulty", "pace", "oh_visits". These were questions from the survey that inquired aboue prior experience in coding and difficulty of the course. I used the select function to chose data based on the column header.

From here I counted up the number of students in the prior_exp column based on the 5 categories which could be selected to see how many students of each type there were. The majority of students (478) has little experience and only 50 had more than a year of experience.

From here I used a custom function which acts as a row filter that filters a column based table to only include rows where a specified column matches a given value. This was useful in isolating students with no coding experience. I used this function to filter the prior_exp column to only answers that are "None to less than one month" and filter to students with lots of coding experience "1-2 years" and "Over 2 years".

With that done I was able to create 3 graphs. 

The first is bar chart of coding experience and average difficulty ranking of the course. This graphed showed that students with little coding experience found the course harder. 

<img src="/barchart1.png" alt="bar_chart1. "  width="500"/>

The second is a bar chart showing visits to office hours by experience level with less experienced students having higher office hour visitation.

<img src="/barplot2.png" alt="bar_chart2. "  width="500"/>

The third is a scatterplot of pace versus difficulty where less experienced students reported the course being more difficult and the pace being too fast compared to the other experience levels.

<img src="/scatterplot.png" alt="bar_chart2. "  width="500"/>

## Conclusions
Based on the results above, more inexperienced students do find the course harder. This is showcased in chart1 where the less experienced students had the highest difficulty rating and in the 3rd chart where the less experienced students showed clustering in the upper right coner which is where they felt that the pace was fast and that the course was difficult. In additon, less experienced students also go to office hours more frequently compared to more experienced students (chart2). While this doesnt exactly showcase the need to go over more VS code in more detail, it does show that less exerience students seek help more often and find the course more difficult overall. This could indicate the need to potentially give more instruction on the coding software so that students don't need to seek additional help to complete assignments. 

One solution could be to offer optional VS coding orientation videos that walk students through the program, its basic tools, and how to run code.

I would still recommend adding a question to the survey such as "Do you think that more time should be spent on going over the software at the beginning of the course?" to see true concensus though. 

The trade offs to consider include that adding additional material at the beginning could slow down the overall course and be reduandant for those with prior coding experience which was approximately 286 out of the 764 students enrolled in the course. 
