# Analysis of Kickstarter Campaigns with Excel

## Overview of Project

### Purpose
  
The client's play Fever came close to its fundraising goal in a short amount of time, and the client further wants to know how different campaigns historically fared in relation to their launch dates and their funding goals. Using the Kickstarter dataset, we make the following recommendations regarding the outcomes of theater play projects collected from 19 countries  from years 2009 to 2017. See detailed analysis and explaination of the campaign outcomes based on their launch dates and their funding goals below. 
  
## Analysis and Challenges
  
### Analysis of Outcomes Based on Launch Date
  
Created a pivot table using the Kickstarter data to analyze the counts of outcomes for theater campaigns per launch months. This organization of data was demonstrated as a line graph.
  
![Outcomes_vs_Goals.png](Resources/Outcomes_vs_Goals.png)

### Analysis of Outcomes Based on Goals
  
Counted all the different outcomes of play campaigns depending on the range of goal amounts. Then I calculated the percentage of the outcomes per range as well, which was visualized into a line graph. 
  
![Theater_Outcomes_vs_Launch](Resources/Theater_Outcomes_vs_Launch.png)

### Challenges and Difficulties Encountered
  
I didn't encounter any difficulties, but I do think the goal ranges should be edited overall to cover the gaps between each range. For example, "1000 to 4999" should be edited to be "1000 <=, <5000"; and, "greater than 50000" should be edited to be "greater than or equal to 50000". You have the potential to lose datasets that fall outside the the conditions.
  
## Results
  
- Few conclusions about the Outcomes based on Launch Date
  
For all years, theater campaigns launched between May and June had the higher outcomes of success, and therefore we recommended the client to select a launch date within this time frame as you can see from the image. However, even July had moderate levels of success if the client is pushed a few days behind their schedule. Months from August to April appear to have have lower number of success outcomes.  
  
- Conclusion about the Outcomes based on Goals
  
As for setting the funding goals, we recommend an amount less than $5,000.00 for the highest rate of success to meeting the goal amounts. If the client is willing to take a little more risk in terms meeting the goal amount, setting a goal amount in the range $5,000.00 to $9,999.00 is recommended as well.
  
Note that the failure and success curve inverts from ranges $25,000.00 to $44,999.00 and creates an illusion that there would be a high outcome of success for goals between $35,000.00 to $44,999.00. It is important to notify the client that the data points in that ranges are fewer by more than 50-fold compared to that of range $5000.00 to $9999.00. Unless the client has higher confidence in their campaign and willingness to take risks, they are not recommended to set goals in that higher range.
  
- Limitations of this dataset
  
This dataset only considers data from years 2009 to 2017, which may have to be adjusted depending on the trends' volatically. If the majority of the theater data is from or near the 2009 year, I may want to recommend the client to reconsider selecting play campaigns at all after further analysis. If there are a lot more play campaigns in the recent years, I may refine my search for that data instead. 
  
Another thing to note is that the theater data is from 19 countries from around the world. From a quick glance, most of these countries appear to be from the Northern hemisphere with the exception of Australia and maybe a few others. The Outcomes based on Launch Date depended on months of a year and as the higher successful results appear to be the Summer months in the Northern Hemisphere, I might want to adjust the filters on the region depending on my client's specific interests. 
  
Also, this overall analysis was performed on collected/reported Kickstarter data that is limited in dataset by nature. 
  
- Other possible tables and/or graphs that could be created
  
We can create some tables and graphs adjusted as discussed in the previous question. For example, we can see the outcome of launch date table and graph by year and see how the data and outcome are distributed. We can also create tables and graphs depending on the geographic location like Europe, North America, Asia, Oceania, etc.
  
---
