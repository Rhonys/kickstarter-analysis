# **Kickstarter Campaigns Success Analysis**
## Overview
### Purpose
The purpose of this analysis is to provide the client, Louise, with data on past kickstarter campaigns in order to identify the attributes of successful kickstarters, so that they may implement these characteristics and increase the likelihood of success on a Kickstarter campaign they may conduct in the future. 
## Analysis and Challenges
### Analysis of Outcomes Based on Launch Date
This analysis is designed to identify the volume of successful campaigns against what month the campaign started. 
![Theater_Outcomes_vs_Launch](https://user-images.githubusercontent.com/95246572/147151695-1dee04c6-4e81-42da-8db9-44a2ed3a1e69.png)
The biggest challenge here was converting the unix code from the data set into a standard readable calendar date. Once this was done, the pivot table was created and a line graph was used to show distribution. 
I performed this analysis by:
1. Creating a pivot table to organize the success/fail rate according to its start date: 
![DatePivot](https://user-images.githubusercontent.com/95246572/147144362-ad9f2eab-849c-4bd4-a190-7930b2b7c974.png)
2. Converting unix data into a readable standard date ![Unix translate](https://user-images.githubusercontent.com/95246572/147137968-1ada1065-0b58-4e4d-b0ee-32b069bc8c52.png)
### Analysis of Outcomes Based on Goals
This analysis is intended to showcase the percentage of successful campaigns given the goal amount. ![image](https://user-images.githubusercontent.com/95246572/147150668-f93fe65c-d20f-4315-9fc9-608bb5af2eab.png)
The biggest difficulty was in identifying the percentage successful or failed given the goal amount. This required creating ranges from 1000 to 50000 with increments of 4999 and creating a countif formula to populate the correct information. Once the ranges were established, I was able to graph the data to show the percent successful vs. the goal amount.
I performed this analysis by:
1. Creating a goal range and utilizing a countif formula to calculate the percentages of success or failure. 
![GoalRange](https://user-images.githubusercontent.com/95246572/147145905-ea893bd2-7572-4087-ba62-e3caa154478b.png)
2. 





3. Identifying average donations ![AvgDonate](https://user-images.githubusercontent.com/95246572/147138652-dfa3d404-0d18-4afe-be2f-d0e4424cac52.png)
4. and percentage funded.![percentfunded](https://user-images.githubusercontent.com/95246572/147138514-c0c11688-60dc-4e6c-8593-84efe04ff0a1.png)

  ![countif](https://user-images.githubusercontent.com/95246572/147138898-8452cfd2-f9eb-4928-83a9-cacc6576c222.png)

According to the results of this graph and table, it tells us two things:
1. The most successful months to launch a Kickstarter campaign are May and June.
2. The length of time most associated with success is a 1 month campaign. 
![Theater_Outcomes_vs_Launch](https://user-images.githubusercontent.com/95246572/147142987-8b21e684-aad5-4e21-824a-2617e273c446.png)

### Analysis of Outcomes Based on Goals
The most successful goal ranges were less than $5000, which also had the highest volume of kickstarter campaigns. 
![Outcomes_vs_Goals](https://user-images.githubusercontent.com/95246572/147142998-464f390f-5d8b-4e17-8857-c6ae62fb3c92.png)

## Results

