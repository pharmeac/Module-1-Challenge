# Kickstarting with Excel

## Overview of Project

### Purpose
The purpose of this report is to provide data and insights on campaigns that were similiar to Louise's play "Fever", based on launch date and fundraising goals.

## Analysis and Challenges

### Analysis of Outcomes by Launch Date
We first evaluated the outcomes of Theater campaigns based upon the date that the campaign launched. This showed us the trend of each of the outcomes throughout the year. In general, both failed and successful campaigns followed a similiar pattern, with May, June, and July having the most successful and the most failed Theater campaigns. Although June had more successful campaigns than failed campaigns, Louise's play failed. This tells us that there is more to the story in why Louise's campaigned failed.
![Theater_Outcomes_vs_Launch](https://user-images.githubusercontent.com/109913335/186743117-68e201bf-2369-49b5-8f7d-dc2498e4c452.png)

The analysis of Theater Outcomes by Launch Date was performed by creating a pivot table that showed each month of the year, and the number of successful, failed, and canceled campaigns for each. We sorted the outcomes so that successful campaigns were listed before failed and canceled campaigns. We also filtered for Theater campaigns. We then created a line chart of the pivot results so that Louise could easily visualize the results. 

### Analysis of Outcomes Based on Goals
The next analysis performed was an evaluation of Play campaigns based upon the goal fundraising amount and the end outcomes of each goal range. This analysis allows us to evaluate if the goal amount contributed to the outcome. In general, as the fundraising goal increased, the percentage of failure also increased, and the percentage of successful campaigns decreased. There was an exception to this in fundraising goals of $35,000 - $39,999 and $40,000 - $44,999. This may be due to the small number of campaigns for these fundraising goal ranges. Louise's campaign had a goal of $2,885 and only received $2,485 in pledges. When all plays with the same goal range ($1,000 - $4,999) were evaluated, 73% were successful and 27% failed. Like our first analysis, this also doesn't provide us insight into why Louise's campaigned failed.
![Outcomes_vs_Goals](https://user-images.githubusercontent.com/109913335/186743249-711bc34a-f4f0-477d-9294-19584c15bdc5.png)

The analysis of outcomes based on Goals was performed by gathering information on the success and failure of each goal range. We used COUNTIF functions to gather the number of successful, failed, and canceled Play campaigns. We used the SUM function to get the total number of projects for each goal range. Finally, we calculated the percentage of successful and failed campaigns by using a Cell A/Cell B calculation then changing the data type to Percent style. There were no canceled play campaigns.

### Challenges and Difficulties Encountered


## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?

- What can you conclude about the Outcomes based on Goals?

- What are some limitations of this dataset?

- What are some other possible tables and/or graphs that we could create?
