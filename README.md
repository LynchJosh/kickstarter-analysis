# Kickstarter-analysis

## Overview of Project
The Kickstarter challenge is a collection of data from Kickstarter to help find trends and outcomes of campaigns that could provide insight into future campaigns.   

### Purpose
The purpose of this project is to help my client find useful data that can give her some insights into past funding ventures related to her category of Plays.

## Analysis and Challenges
To visualize the data two charts and two data sets were generated to simplify the abundance of information collected from Kickstarter. 
The data sets used for my analysis are Outcomes Based on Launch Date and Outcomes Based on Goals.

### Analysis of Outcomes Based on Launch Date
To sift through all the data I first had to filter out all of the irrelevant categories that my client did not need. 
Once I filtered out everything except for theatres I then made a pivot table that sorted years, months, successful, failed, cancelled, and total. 
The pivot table shows the best and worse outcomes based on months throughout the years. After the creation of the pivot table. 
I then created a line chart that better illustrates the numbers from the pivot table. (see below)   

![Theater_Outcomes_vs_Launch](https://user-images.githubusercontent.com/112728628/194617018-51f0d81a-cad7-4e41-828d-0dacaae8f5e9.png)

### Analysis of Outcomes Based on Goals
The second chart I made was based on dollar amount goals for funding. I started by gathering all the numbers of successful, failed, and cancelled monetary goals. 
To do this I used the COUNTIFS formula to gather information based on the goals column as well as subcategories. 
This information was then converted into a line graph to show a percentage of goals in successful, failed, and cancelled campaigns. (see below)   

![Outcomes_vs_Goals](https://user-images.githubusercontent.com/112728628/194617172-bf70d145-24ac-4551-9a29-81f6da24d885.png)

### Challenges and Difficulties Encountered
When I started this project everything seemed to make sense until I got to the COUNTIFS formula. 
That was my first time using the formula in Excel and needless to say I found the instructions a little confusing so I used google and a few tutorial videos I found that simplified the steps for me. 
On the Kickstarter page, I was using the filter tool to find the items instead of imputing them into the formula. 

## Results
- What are two conclusions you can draw about the Outcomes based on Launch Date?
Based on the data point on the line chart May has the highest success rate among launch dates. 
The line chart also shows the least successful month being December. 
So based on the chart my client should look for a launch date in May to have the greatest chance for success.    

- What can you conclude about the Outcomes based on Goals?
The data based on goals seems to indicate that as the dollar amount increases it is more likely the campaign will fail. 
When the dollar amount reaches around $25,000 amount the play has an 80% chance of failure. 
From the $35,000 - $45,000 mark there is an outlier that shows a successful result however after $45,000 that number falls to the 0% success rate. 

- What are some limitations of this dataset?
 After visualizing the data on a chart it is clear to me that there are outliers that skew some of the results. 
 This could be fixed with more data however there's enough to see trends which can give my client an edge. 

- What are some other possible tables and/or graphs that we could create?
Adding a chart that filters countries with categories could be useful to see if there's a market for my client rather than an across-the-board kind of approach. 
A scatter chart could be another way to visualize some of the information as well.  

