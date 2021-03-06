# Kickstarting with Excel

## Overview of Project

### Purpose

Data Analysis and visual feedback of the fundraising campaigns based on the correlation of campaigns’ launch dates and fundraising goals as recorded in the Kickstarter dataset.

## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date

A pivot table and a line chart were created based on the number of theater campaigns and their respective launch dates obtained from the Parent Category and Years columns in the Kickstarter dataset. Based on the data displayed in the pivot table and reflected on the line chart, we can conclude that the theater campaigns launched during May and June have a higher chance to succeed and reach their fundraising goals, then the campaigns launched the rest of the year. 

![Theater_Outcomes_vs_Launch](resources/Theater_Outcomes_vs_Launch.png).

### Analysis of Outcomes Based on Goals

A line chart, Outcomes Based on Goals, was created based on the data derived from the funding goal amounts for the campaigns in the ‘play’ subcategory. We utilized =COUNTIFS() and =SUM() formulas to calculate the number of successful, failed, canceled campaigns, and total number of projects for each range. Then, we found the percentage of successful and failed campaigns. Based on the visual information presented in the chart below, we can conclude that there is a correlation between the fundraising goal amount and the outcome of a given campaign. The analysis of the chart shows the higher the campaign’s funding goal is, the less likely it is to have a successful outcome. In other words, if the people are required to give less money, they are more willing to participate. 

![Outcomes_vs_Goals](resources/Outcomes_vs_Goals.png).

### Challenges and Difficulties Encountered

The biggest challenge I had was constantly monitoring I entered the numbers and formulas correctly, otherwise, I was getting wrong values or #n/a. For example, while entering goal amount ranges in the Outcomes Based on Goals sheet, I missed 35000-39999 range and it took me time to find my mistake. 

Another difficulty I had was figuring out what the best chart was to use that would give me the best visual feedback and help me in answering the established goals. 

## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?

The time of the year when the campaign is launched is important for success. A good time for a fundraising theater campaign based on Kickstarter dataset is during summer, primarily May and June.  It should be noted that higher number of failed theater campaigns was also seen during the summer months. December appears to be the month when the number of people contributing to the campaigns is the lowest. We can possibly speculate that people have higher personal expenses around winter holidays. 

- What can you conclude about the Outcomes based on Goals?

The lower the goal amount of the campaign, the higher the chance the people would be contributing to the campaign. 

- What are some limitations of this dataset?

If we look at the “Outcome Based on Goals” chart, we can see there is another spike of successful campaigns in the range of $35,000 to $45,000. However, the total number of projects in this group is insignificant and the data included in the Kickstarter dataset does not contain enough information to account for this discrepancy. 

There is no demographic information available on campaign participants. Age group, gender, educational level, socio-economic status, and city/state of residency can all play an important part in the outcomes of the campaign. 

There is also no data available on the marketing strategies of each of the campaigns.

There is no data available on the genre of the play campaigns. If we had this information available, then we could create pivot table/chart to see if people contributed more actively to specific genres. 

Finally, some kickstarter campaigns are local and some are worldwide.  

- What are some other possible tables and/or graphs that we could create?

We could create several line graphs to analyze the relationship between successful and failed campaign subcategories and to see in what subcategories the Kickstarter campaigns perform better. 

We could create a line graph for total number of projects to visualize the amount of participants in each campaign to see if it is large enough to be of a significant value. 
