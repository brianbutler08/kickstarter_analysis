# An Analysis of Kickstarter Campaigns
Performing analysis on Kickstarter data to uncover trends

# Kickstarting with Excel

## Overview of Project

For this project, we were approached by an up-and-coming playwright named Louise. She had written a new play titled *Fever* but needed to acquire the $10,000 of funding to get it produced. Louise had an interest in utilizing the online platform Kickstarter as a method to crowdfund her project and wanted to work with a data analyst proficient in Excel to explore some of the available Kickstarter data in order to maximize success. 

### Purpose

The general purpose of our analysis was to look at fundraisng campaigns that were similar in focus to the project that Louise was considering. In addition to looking at trends in all of our Kickstarter data, we would do a deeper dive into theater campaigns, specifically plays and projects that originated in both the United States and Great Britain. W thought that if we could identify some characteristics of successfully funded campaigns, we could perhaps apply that knowledge to Louise’s Kickstarter launch.

## Analysis and Challenges

We acquired a dataset (n=4,114) of various Kickstarter campaigns from 2009 to 2017, which included the following fields:
- Project name
- Project blurb
- Funding goal
- Amount pledged
- Outcome of campaign
- Country of origin
- Currency
- Date that the campaign opened
- Date that the campaign closed
- Number of backers
- If the campaign was a staff pick or highlighted
- Campaign category and subcategory

Data analysis was done exclusively in Microsoft Excel. 

Of the nine general categories of fundraising campaigns, the theater category had the highest number of projects during this time period (1393), almost twice the number of the next most popular project (music – 700). When looking at only the US based projects, this trend continued, with 912 campaigns categorized as “theater”. Additionally, theater projects were the most successful during this time period, with 525 projects being successfully funded. And of those projects that were successful, 412 of them were plays, making “plays” the subcategory with the most successfully funded campaigns in the US.

![Parent Category Outcomes Bar chart](https://github.com/brianbutler08/kickstarter-analysis_Module1.6.1/blob/main/Parent%20Category%20Outcomes.png?raw=true)

Additionally, theater projects were the most successful during this time period, with 525 projects being successfully funded. And of those projects that were successful, 412 of them were plays, making “plays” the subcategory with the most successfully funded campaigns in the US.

![Theater Outcomes](https://github.com/brianbutler08/kickstarter-analysis_Module1.6.1/blob/main/Theater%20Subcategory%20Outcomes.png?raw=true)

In order to explore the possible differences in US campaigns that were successful versus those that failed, we looked at some basic descriptive statistics by campaign outcome. The mean goal for successful projects ($5,049) was less than half of the failed projects ($10,554). Additionally, the mean amount pledged to successful campaigns ($5,602) was ten times more than the mean for those campaigns that failed to meet their funding goals ($559). On the surface, it appears that the failed projects were generally setting their goals unrealistically high and they were unable to generate enough support to even come close to those meeting those goals. 

![Descriptive Statistics Table US](https://github.com/brianbutler08/kickstarter_analysis/blob/main/Kickstarter%20Table.png?raw=true)

### Analysis of Outcomes Based on Launch Date

The question of when to launch her campaign for *Fever* was important to Louise. Is there a certain month or specific time of year that are associated with higher rates of funding success? When we looked at the timing of when campaigns were launched, it appears that there were indeed some launch months that looked more favorable. We first looked at all campaigns in the dataset and, overall, May was the most successful launch month, with success rates gradually tapering downward over the summer. After a dip in success rates in the early fall, there was a rebound in October and November. This was followed by a significant decrease in December, when the number of failed projects exceeded those that were successful.

![Line graph of campaign launch months](https://github.com/brianbutler08/kickstarter-analysis_Module1.6.1/blob/main/Outcomes%20Based%20on%20Launch%20Date.png?raw=true)

Becuase we are primarily interested in theater projects, we ran the same anlysis for just that subcategory of campaigns. Generally, theater projects followed a similar pattern to the larger population, with May being the most successful launch month, followed by decreasing, but still relatively successful, rates in June and July. After a similar rebound in October, theater campaigns were much less successful if they were launched November and December. 

![Theater Outcomes Based on Launch Month](https://github.com/brianbutler08/kickstarter_analysis/blob/main/Theater_Outcomes_vs_Launch.png?raw=true)

### Analysis of Outcomes Based on Goals

In addition to looking at the timing of a campaign launch, we thought it would be important to investigate the relative success of a fundraising project based on the goal amount. Louise initially estimated a goal of $10,000, so we wanted to explore the success (or failure) rate of a project that size to provide her with guidance on how to proceed. For this step, we limited our analysis to plays only in order to eliminate other theater projects that would be much less comparable (i.e. acquiring physical spaces, theater renovations).

![Outcomes vs Goals](https://github.com/brianbutler08/kickstarter_analysis/blob/main/Outcomes_vs_Goals.png?raw=true)

Perhaps unsurprisingly, the campaigns with the highest rates of success were those that had the loweest goals. Seventy six percent of campaigns under $1,000 were successful, as were 73% of projects between $1,000 and $4,999. As the goal increases above $5,000, the proportion of successful projects decreases dramactically. Of campaigns with a goal of $25,000 to $29,999, only one in five was successfuly funded. Interestingly, two thirds of play campaigns with goals between $35,000 and $44,999 successfully met their funding goals, suggesting that high goal amounts didn't necessarily translate to failure. Looking specifically at Louise's goal of $10,000 - just over half (54%) of similar campaigns were successfully funded, suggesting that she may need to reconsider her budget.

### Challenges and Difficulties Encountered

## Results

# Launch Date Conclusions

Based on our anaylsis of campaign launch dates, we could draw a couple of conclusions and make two recommendations to Louise. Ideally, she should look to launch her campaign in May, or in early summer at the very least. Based on the eight year of data that we have in this dataset, this is the time of year that is associated with the highest success rates. Our other suggestion would be to not, under any circumstances, launch her campaign in December, where the number of projects that have succeeded are almost identical to the number that have failed.

# Goal Amount Conclusions

As mentioned above, we can conclude that the most successful play campaigns were those with modest goals of under $5,000 OR those with goals above $35,000, but below $45,000. Because Louise does not require funding in the amount of the latter category, she should be looking to set a funding goal that is much lower than her current idea of $10,000. Plays with goals at that amount *do* get funded, just at much lower proportions as those with lower expectations. 

# Limitations of the Dataset

- What are some limitations of this dataset?

- What are some other possible tables and/or graphs that we could create?




## Timing Your Campaign Launch



## Analysis of *Foresight*

Because Louise had an interest in the British play *Foresight*, we looked at it specifically to see how successful its campaign was. It was fully funded, despite only having seventeen backers, leading to a high average donation of $117.88 per person. Additionally, the campaign ran for just under a month, less than the dataset average of 33 days. 

## Edinburgh Festival 
 
Louise was inspired by five specific plays that she saw at the Edinburgh Festival Fringe, so we looked in detail to see if they could provide any insights into creating a successful crowdfunding campaign. All five plays were successful in meeting their funding goal. They each had a relatively modest goal, with the highest goal being just $4000 and the average being $2100. They each had a good number of backers (mean = 62.4), with each person contributing an average of $40.5.


 
 
