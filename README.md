# **Kickstarter Campaigns Success Analysis**
##Overview
The purpose of this analysis is to provide the client, Louise, with data on past kickstarter campaigns in order to identify the attributes of successful kickstarters, so that they may increase the likelihood of success on a Kickstarter campaign.
##Analysis and Challenges
I performed this analysis by filtering the data set for successful, domestic, theater campaigns by date and goal amount. I created more granular columns to further detail column statistics by segregating category and subcategory, converting unix data into a readable standard date, ![image]![Unix translate](https://user-images.githubusercontent.com/95246572/147137968-1ada1065-0b58-4e4d-b0ee-32b069bc8c52.png)



identifying average donations and percentage funded. The biggest difficulty was in identifying the percentage successful or failed given the goal amount. This required creating ranges from 1000 to 50000 with increments of 4999 and creating a countif formula to populate the correct information. Once the ranges were established

