# Kickstarting with Excel

## Overview of Project

Data Analysis of the play fundraising campaigns based on the correlation of campaigns’ launch dates and fundraising goals as recorded in the Kickstarter dataset.  

### Purpose

Analysis and visual feedback of the Kickstarter campaign outcomes based on the launch dates and funding goals.

## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date

A pivot table and a line chart were created based on the number of theater campaigns and their respective launch dates obtained from the Parent Category and Years columns in the Kickstarter dataset. Based on the data displayed in the pivot table and reflected on the line chart, we can conclude that the theater campaigns launched during May and June have a higher chance to succeed and reach their fundraising goals, then the campaigns launched the rest of the year. 

![Theater_Outcomes_vs_Launch](path/to/resource/Theater_Outcomes_vs_Launch).

### Analysis of Outcomes Based on Goals

A line chart, Outcomes Based on Goals, was created based on the data derived from the funding goal amounts for the campaigns in the ‘play’ subcategory. Based on the visual information presented in the chart below, we can conclude that there is a correlation between the fundraising goal amount and the outcome of a given campaign. The analysis of the chart shows the higher the campaign’s funding goal is, the less likely it is to have a successful outcome. In other words, if the people are required to give less money, they are more willing to participate. 

![Outcomes_vs_Goals](Resources/Outcomes_vs_Goals).

### Challenges and Difficulties Encountered

The biggest challenge I had was constantly monitoring I entered the numbers and formulas correctly, otherwise, I was getting wrong values or #n/a. For example, while entering goal amount ranges in the Outcomes Based on Goals sheet, I missed 35000-39999 range and it took me time to find a mistake. 

## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?

The time of the year when the campaign is launched is important for success. A good time for a fundraising theater campaign based on Kickstarter dataset is during summer, primarily May and June.  It should be noted that higher number of failed theater campaigns was also seen during the summer months. December appears to be the month when the number of people contributing to the campaigns is the lowest. We can possibly speculate that people have higher personal expenses around winter holidays. 

- What can you conclude about the Outcomes based on Goals?

The lower the goal amount of the campaign, the higher the chance the people would be contributing to the campaign. 

- What are some limitations of this dataset?

If we look at the “Outcome Based on Goals” chart, we can see there is another spike of successful campaigns in the range of $35,000 to $45,000. However, the total number of projects in this group is insignificant and the data included in the Kickstarter dataset does not contain enough information to account for this discrepancy. 

There is no demographic information available on campaign participants. Age group, gender, educational level, socio-economic status, and city/state of residency can all play an important part in the outcomes of the campaign. There is also no data available on the marketing strategies of each of the campaigns.

- What are some other possible tables and/or graphs that we could create?

We could create pivot table/chart based on the genre in the play subcategory, to see if people contributed more actively to specific genres. 

We could also create a chart on the average donation per each contributor. 
