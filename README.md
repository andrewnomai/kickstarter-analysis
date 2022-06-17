# KickStarter Analysis
## Project Overview
##### Background
We are conducting an analysis of crowdfunding campaigns to help Louise conduct her own as an upcoming playwright. She needs help in regards to establishing what works and what doesn't and is eager to start her own crowdfunding site to fund her new play, "*Fever*". 

##### Purpose
We want to do an analysis of crowdfunding campaigns and sort which ones were successful and which were not. Among those, we want to uncover trends of successful crowdfunding campaigns and mirror specific factors that make certain campaigns successful.

## Analysis
##### Theater Outcomes Based on Launch Date
This analysis was performed by creating a pivot table using crowdfunding Kickstarter raw data of Parent Categories against the dates the campaigns were created. We placed filters on the two to specifically measure the data among theater campaigns against the months through out the year. We took outcome count values of the Kickstarter raw data and filtered them accordingly in the pivot table to show the number of campaigns in that specific filter that were successful, failed, or canceled, as well as a grand total. We then created a line chart according to the data from the pivot table to outline the trend across the months in the year. Our findings were that a high number of campaigns were rose to success during the month of April and peaked during May. The trend slows down as the summer comes, with winter following the same downtrend suite.

![Theater_Outcomes__vs_Launch](https://user-images.githubusercontent.com/107603065/174233184-0d58efa9-7fde-4909-bd7c-bfcb614d1365.png)

##### Outcomes based on Goals
This anaylsis was performed by creating a pivot table using the crowdfunding Kickstarter raw data as well. For this particular pivot table, the data set was sorted through a "Countifs()" formula, in which would filter and count specific values within the Kickstarter raw data set. We specifically set the pivot table to filter and count out values according to the outcomes of plays. We then sorted each count by ranges of crowdfunding goals and plotted a line graph according to the percentage of each outcome against the total number of projects inputted. What we start to uncover from this data is that successful and failed plays have an inverse relationship with regard to the crowdfunding goal. As the goal value increases, the number of succesful plays start to decrease, while the number of failed plays start to increase. 

![Outcomes_vs_Goals](https://user-images.githubusercontent.com/107603065/174234326-eaaa421c-a96f-4ce6-b309-165f4ad955be.png)

## Challenges and Limitations
##### Challenges
There were some challenges with regard to the properly creating the "CountIfs()" formula to properly reflect data that we needed to see. This was due to difficultly figuring out the proper ways to nest the appropriate arrays within the formula so that we would filter out the uneccessary data and keep the vital ones needed to demonstrate the picture we wanted. 

##### Limitations & Other Possibilities
A limitation with regard to this particular dataset might be the period of time in which the data was collected. The data is fixed between 2009 to 2017 and there isn't any data dating further back or forward, closer to the present. Trends change every year. As technology evolves over time, there could be a drastic change in trends of society in which can alter the success factors to Louise's crowdfunding campaign, such as ease of fund, mass marketing possibilities, or even the end of theater all together. One could say that another possible graph to look at would be the trend of outcomes for different categories across different years. Not only could we uncover a potential trend across the years through a line graph or we could use a bar graph to show different categories and the success rate across the board. We could use the data uncovered from these new tables to mirror specific factors that were successful in other categories in the appriate era of the decade and possibly make predictions on the appropriate time the play wshould be launched based in this information to mirror similar success. 
