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



### Challenges and Difficulties Encountered

## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?

- What can you conclude about the Outcomes based on Goals?

- What are some limitations of this dataset?

- What are some other possible tables and/or graphs that we could create?




## Timing Your Campaign Launch



## Analysis of *Foresight*

Because Louise had an interest in the British play *Foresight*, we looked at it specifically to see how successful its campaign was. It was fully funded, despite only having seventeen backers, leading to a high average donation of $117.88 per person. Additionally, the campaign ran for just under a month, less than the dataset average of 33 days. 

## Edinburgh Festival 
 
Louise was inspired by five specific plays that she saw at the Edinburgh Festival Fringe, so we looked in detail to see if they could provide any insights into creating a successful crowdfunding campaign. All five plays were successful in meeting their funding goal. They each had a relatively modest goal, with the highest goal being just $4000 and the average being $2100. They each had a good number of backers (mean = 62.4), with each person contributing an average of $40.5.


 
 
