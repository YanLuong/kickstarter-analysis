# An Analysis of Kickstarter Campaigns.

This report provides insight on data covering several thousand crowdfunding projects through analysis and data visualisation.

---
## Overview of Project

This project attempts to generate insights and trends from analysing several thousand crowdfunding projects on behalf of Louise, who is keen to start a number of fundraising campaign projects. The analysis will focus on attributes that lead to higher success rates in campaigns achieving their fundraising goals. This research will allow Louise to optimise her future theatre fundraising campaigns and increase their chances of success.

### Purpose

Louise would like to investigate whether certain factors determine or influence the outcome of campaigns. With this in mind, this report will analyse and discuss how campaign launch dates and their funding goals correlate to a campaign's potential success or failure.

## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date

##### Method

To analyse how the launch dates impacted the campaign outcome, the data was formatted in a pivot table. This allows us to filter in data of interest (outcomes) and omit the unnecessary information. Since Louise is interested in the theatre category and launch dates, the parent category and year (year of when campaign was created) were selected in the filters and plotted against outcomes ("successful", "failed", and "cancelled"). A line chart was created to visualise the information.

##### Analysis

When looking at the line chart below, we can see at face value campaigns that launched in May were significantly more successful which is closely followed by June and July. The number of failed campaigns throughout the year remained relatively stable which suggests other factors are at play in influencing a campaign's overall outcome as it is not showing a correlation between successful and failed outcomes.




![Outcome Vs Launch date chart](https://github.com/YanLuong/kickstarter-analysis/blob/main/Theater_Outcomes_vs_Launch.png)





##### Challenges



Possible challenges are present in this analysis. For example, when only looking at the line chart the story is quite clear in that May, June and July were the successful performing months. However, the data does not take into account the success rate as a percentage of total campaigns launched. When taking into account the percentage of successful campaigns out of the total campaigns, it shows only a slight increase in the success rate instead (highlighted in yellow on table, below). It does show that between May and July, the highest number of campaigns were launched which has contributed directly to the higher number of successful campaigns based on launch date. 




![Outcome vs Launch date table](https://github.com/YanLuong/kickstarter-analysis/blob/main/Pivot_table_outcome_vsLaunchDate.png)





### Analysis of Outcomes Based on Goals

##### Method

A table was created in excel to populate the number of successful, failed and canceled outcomes using a  ***countifs()*** function. The countifs() function will only count if all the conditions are met. The conditions that had to be met before they were tallied to the relevant cell by goal amount were:

- by outcome ("successful,"failed" and "canceled")
- range based on grouped amounts
- subcategory containing "plays" 

Once all data were counted using the countifs() statement, the percentages was calculated for the successful, failed and canceled projects. Next, a line chart was created to visualise the relationship between goal amount ranges vs the percentage successful, failed and canceled.





##### Analysis



### Challenges and Difficulties Encountered

## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?

- What can you conclude about the Outcomes based on Goals?

- What are some limitations of this dataset?

- What are some other possible tables and/or graphs that we could create?

