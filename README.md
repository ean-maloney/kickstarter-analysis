# Analysis of Kickstarter Campaigns for Plays

## Overview of Project
In this project, I examine the successfulness of Kickstarter campaigns in the category "theater" in relation to their launch dates and the success of campaings in the subcategory "plays" in relation to their fundraising goals.

### Purpose
The purpose of this project is to predict the launch date and goal amount at which a proposed campaign in the "theater"/"plays" category will have the greatest liklihood of success. 

## Analysis and Challenges
One analysis I performed using data from Kickstarter campaigns in the category "theater" concerns the relation between the start date of these campaigns and their eventual outcomes. This relation is depicted in the following graphic.

<img width="240" alt="Theater_Outcomes_vs_Launch" src="https://user-images.githubusercontent.com/80861610/115411577-970e7800-a1c1-11eb-9400-7daeccf29d1f.png">

A second analysis concerned the relation between the fundraising goals and outcomes of campaigns in the "plays" subcategory. Represented in the following chart are the percentages of campaigns in different goal ranges which were successful, failed, and canceled.

<img width="612" alt="Outcomes_vs_Goals" src="https://user-images.githubusercontent.com/80861610/115412167-1734dd80-a1c2-11eb-8370-c0c82c4fb806.png">

### Analysis of Outcomes Based on Launch Date

As the attached chart shows, the largest number of successful campaigns for theater projects began between April and August. Although there was also an increased number of failed campaigns during these months, the increase in failed campaigns appears to be relatively small compared to the increase in the number of successful campaigns.

### Analysis of Outcomes Based on Goals

The second line chart above shows that the best success rates for campaigns in the subcategory "plays" occur when the fundraising goal is set at less than $15,000 or in a "sweet spot" between $35,000 and $45,000, with success rate plummeting for projects with goals above the $40,000 to $45,000 range.

### Challenges and Difficulties Encountered

The main challenge with this project was to extract the relevant information from a large data set. This was accomplished using various features of Excel, including pivot charts and conditional formulas, to obtain relevant data from the original data set of Kickstarter campaigns.

## Results

- Two conclusions I draw from the analysis of outcomes based on launch date are that (1) the greatest success rates appear to occur around the summer, approximately April through August, with the largest number of successful campaigns starting in May and June and (2) the ratio of successful to failed campaigns appears in general to decrease after May, with the number of successful campaigns approaching the number of failed campaings at the end of the calendar year.

- From the analysis of outcomes based on goal amount, I conclude that the highest percentage of successful campaigns occurs in two ranges, less than $15,000 and between $35,000 and $45,000.

- The main limitation I see with the data set is that it only includes campaigns from 2009-2017. Trends concerning the successfulness of campaigns of the relevant kind may have changed in the last several years. Another possible limitation would be the arbitrariness of the "successful"/"failed" labels. It is almost certain that some "failed" campaigns raised more money than some "successful" ones since a "failed" campaign could just have a much larger fundraising goal. 

- Another graphical representation that would be helpful is a chart showing the relation between the rate of success of campaigns and launch date for campaigns in the "plays" subcategory in addition to the chart above showing this for campaigns in the larger "theater" category. I also think a very helpful graphic to have would be a scatter plot with start date (day/month) on one axis and fundraising goal on the other and to give each play campaign a point on the chart color coded based on the success. Though this chart would be hard to get quantitative data from, it would provide a good overview of the whole project and provide some helpful hints for making predictions.
