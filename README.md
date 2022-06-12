# An Analysis of Kickstarter Campaigns
Performing analysis on Kickstarter data to uncover trends

# Kickstarting with Excel

## Overview of Project

For this project, we were approached by an up-and-coming playwright named Louise. She had written a new play titled *Fever* but needed to acquire the $10,000 of funding required to get it produced. Louise had an interest in utilizing the online platform Kickstarter as a method to crowdfund her project and wanted to work with a data analyst proficient in Excel to explore some of the available Kickstarter data in order to maximize success. 

### Purpose

The general purpose of our analysis was to look at fundraisng campaigns that were similar in focus to the project that Louise was considering. In addition to looking at trends in all of our Kickstarter data, we would do a deeper dive into theater campaigns, specifically plays and projects that originated in both the United States and Great Britain. We thought that if we could identify some characteristics of successfully funded campaigns, we could perhaps apply that knowledge to Louise’s Kickstarter launch.

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

Of the nine general categories of fundraising campaigns, the theater category had the highest number of projects during this time period (1393), almost twice the number of the next most popular project (music – 700). When looking at only the US based projects, this trend continued, with 912 campaigns categorized as “theater”. 

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

No major challenegs were encountered during this analysis. However, there could potentially be issues with similar datasets in the future. The primary issue here is with the relatively larger number of fields and the myriad of ways that the data could be approached. For some, there may be so many potential variables to look at, that it could be quite paralyzing and one may be unsure where to begin. This can be remedied by setting out a course of action early on and solid communication with Louise about what her expectations are.

## Results

### Launch Date Conclusions

Based on our anaylsis of campaign launch dates, we could draw a couple of conclusions and make two recommendations to Louise. Ideally, she should look to launch her campaign in May, or in early summer at the very least. Based on the eight years of data that we have in this dataset, this is the time of year that is associated with the highest success rates. Our other suggestion would be to not, under any circumstances, launch her campaign in December, where the number of projects that have succeeded are almost identical to the number that have failed.

### Goal Amount Conclusions

As mentioned above, we can conclude that the most successful play campaigns were those with modest goals of under $5,000 OR those with goals above $35,000, but below $45,000. Because Louise does not require funding in the amount of the latter category, she should be looking to set a funding goal that is much lower than her current idea of $10,000. Plays with goals at that amount *do* get funded, just at much lower proportions as those with lower expectations. 

### Limitations of the Dataset

Despite our dataset being extremely comprehensive and containing important, high level information, there are still two primary limitations that could be rectified. Primarily, it would be helpful if the set included a few more years of data. Information as recent as 2017 may be sufficient for some analysis projects, but when looking at economic and financial trends, it is critical to have the most up to date dataset possible. Downturns in the economy, inflation, unemployment and changing consumer behavior can have significant effects on how people spend their disposible income and how donations are viewed. A lot has changed in the global economic arena in the five years since this dataset was released and to make recommendations in 2022 using older data could lead to some less than accurate advice.

The other limitation would be the relatively small number of subcategories in the "theater" parent category. Or rather, the lack of more granular data in the "plays" category. A quick read through the blurbs for play campaigns reveals a diverse group of people and organizations seeking funding. There are solo playwrights, like Louise, but there are also theater troupes, playhouses, non-profit organizations, theater societies, and combinations of entities sponsoring campaigns. Additionally, some plays are intended for a single festival, others will be short runs of a few shows and others appear to be longer term commitments. All of these separate factors play a part in determining if funding goals will untimately be met and it would help the analysis if there were additional categories to explore. To most effectivley guide Louise, we should be looking at the campaigns that most closely resemble hers. 

### Suggestions for Future Analysis

Moving forward, there is the potential to create additional tables and graphs for this analysis, or to update or existing work by adding or removing complicating fields. In addtion to the analysis that we have done above, there could be a few other helpful areas of future exploration. 

The first is related to the limitation expressed above. It may be beneficial to look specifially at plays that are similar to *Fever*, or plays that Louise liked personally. A little of this type of analysis was done earlier with five plays from the Edinburgh Festival Fringe that Lousie enjoyed. We discovered that all five plays were successful in meeting their funding goal. They each had a relatively modest goal, with the highest being just $4,000 and the average being $2,100. They each had a good number of backers (mean = 62.4), with each person contributing an average of $40.50. These suggest some good numbers for Louise to emulate and looking in depth at even more similar plays could help round out the overall project.

The other suggestion would be to look at the effect of the Kickstarter Staff Pick status. Staff Pick was a feature where projects were selected by Kickstarter staff to receive extra exposure through newsletters and the website. These projects had their profile significantly boosted and were seen by many more potential backers than those not selected. The Staff Pick program no longer exists, but it was active during the time period of our dataset and certainly contributed to the success rate of projects. A quick glance at the play campaigns confirms this suspicion. In the dataset, 114 plays were Staff Picks and 103 (90.4%) of these were successful in being funded. Conversely, of the 941 campaigns that were not Staff Picks, only 591 (62.8%) were successful. Because the Staff Picks feature is no longer active, Louise's play has no chance to be included in this prestigious cohort. Because of it's significant impact on campaign outcome historically, one could make a case for eliminating campaigns that were Staff Picks from future analysis.
