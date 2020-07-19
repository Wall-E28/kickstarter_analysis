# Kickstarter Analysis

## Overview of Project

This project looks into Kickstarter data to uncover trends relating to campaign launch dates and goal amounts within the "plays" subcategory. 

### Purpose

The purpose of this project is to offer insights to a past kickstart campaign manager to see how her project stacked up compared to others. This would help her excute future campaigns that will yeild successful results. 

## Analysis and Challenges

The analysis completed for this project fell into two main deliverables: outcomes based on launch date and outcomes based on goals.

### Analysis of Outcomes Based on Launch Date

This analysis looked at the outcomes of the parent category "theater"'s campaigns, which the subcategory "plays" is apart of, based on the month that each campaign started in. To complete this analysis, I created a pivot table using all of the data on kickstarter to looked specifically at the 'theater' category, the launch date of each campaign, and the outcome of those campaigns. To do this, I used "parent category" and "years" as filters, the "launch date" as rows, and "outcomes" as values and columns. After compiling the data in the pivot table, I created a line chart to show the outcomes based on the month that each campaign was started. See chart below.

![Outcomes_vs_Goals.png](/Users/rileybrowne/Documents/UCB Data Analytics Course/Module 1 - Excel/Excel Projects /Resources/Outcomes_vs_Goals.png)

### Analysis of Outcomes Based on Goals

This analysis looked at the outcomes of the subcategory "plays"'s campaigns based on the total goal amounts. To complete this analysis, I used the COUNTIFS() function to pull the number of successful, failed, and canceled campaigns for 12 different dollar-amount ranges. For there, I found the total amount of campaigns for each dollar-amount range by using the SUM(). Then I calculated the percentage of successful, failed, and cancelled campaigns per dollar-amount range. After that, I created a line chart to show those percentages as they changed between the different dollar-amount ranges. See chart below.

![Theater_Outcomes_vs_Launch.png](/Users/rileybrowne/Documents/UCB Data Analytics Course/Module 1 - Excel/Excel Projects /Resources/Theater_Outcomes_vs_Launch.png)

### Challenges and Difficulties Encountered

Some of the challenges that occured along the way were making sure that the charts had the right labels on the axis, making sure the COUNTIFS() functions included all of the "plays" campaigns, and making sure that the pivot table rows were months and not individual dates. All three of these challenges were overcome by simple google searches to figure out the best way to fix each challenge. 

## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?

The main conclusion from this analysis is that May and June are the best months of the year to start a theater based campaign. This is because May and June have 25.1% (211/839) of total successful campaigns while only making up 23.3% (319/1369) of total campaigns. The secondary conclusion is that October, November, and December are the worst months of the year to start a theater based campaign. This is becasue they make up 18.6% (156/839) of successful campaign while making up 20.3% (278/1369) of total campaigns. 

- What can you conclude about the Outcomes based on Goals?

The main conclusion from this analysis is that campaigns that are under under $5000 have the best chance of being successful. These campaigns averaged a 73.4% (528/719) success rate while more expensive campaigns averaged a 50.5% (165/327) success rate. 

- What are some limitations of this dataset?

One of the large limitions is the data set size. With regard to the outcomes based on goals analysis, I only looked at the campaigns in the "plays" subcategory and for some dollar-amount ranges there were less than 10 total campaigns. With such small numbers in some ranges, it makes it hard to know if the data is an accurate reflection of the outcomes or if it skewed. Another limition was only looking at the "plays" subcategory. While I wanted specific insights from the "plays" campaigns, it also would be helpful to compare that information to all campaigns on kickstarter. This analysis could show if kickstarter is a good place to raise money for a play or if it would be better to look else where. 

- What are some other possible tables and/or graphs that we could create?

Other possible tables/charts would include looking at outcomes based on duration of campaigns for "plays" and outcomes based on all three metrics for all campaigns.
