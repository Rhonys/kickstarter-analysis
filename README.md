# **Kickstarter Campaigns Success Analysis**
## Overview
The purpose of this analysis is to provide the client, Louise, with data on past kickstarter campaigns in order to identify the attributes of successful kickstarters, so that they may increase the likelihood of success on a Kickstarter campaign.
##Analysis and Challenges
I performed this analysis by filtering the data set for successful, domestic, theater campaigns by date and goal amount. I created more granular columns to further detail column statistics by:
1. Segregating category and subcategory 
2. Converting unix data into a readable standard date ![Unix translate](https://user-images.githubusercontent.com/95246572/147137968-1ada1065-0b58-4e4d-b0ee-32b069bc8c52.png)
3. Identifying average donations ![AvgDonate](https://user-images.githubusercontent.com/95246572/147138652-dfa3d404-0d18-4afe-be2f-d0e4424cac52.png)
4. and percentage funded.![percentfunded](https://user-images.githubusercontent.com/95246572/147138514-c0c11688-60dc-4e6c-8593-84efe04ff0a1.png)

 The biggest difficulty was in identifying the percentage successful or failed given the goal amount. This required creating ranges from 1000 to 50000 with increments of 4999 and creating a countif formula to populate the correct information. Once the ranges were established, I was able to graph the data to show the percent successful vs. the goal amount. ![countif](https://user-images.githubusercontent.com/95246572/147138898-8452cfd2-f9eb-4928-83a9-cacc6576c222.png)


