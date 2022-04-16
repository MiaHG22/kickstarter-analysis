# kickstarter-analysis
Performing analysis on kickstarter data to uncover trends
## Overview of Project
This Kickstar Project analyzes the global Kickstarter campaignes from 2009 to 2017 to uncover the trends to theater projects and plays.
### Purpose
The purpose of this project is to use the data from 2009 to 2017 to analyse how the different campaigns, specific event, their launch dates and fundig goals relate to the campaign outcomes.
## Analysis and Challenges
By just looking at the given spreadsheet, it's hard to delve into the analysis. The dataset needed to be broken down into smaller and more defined groups. After breaking down the "category and "subcategory" column and creating seperate columns for theater and plays, a more detailed analysis could be conducted.
### Analysis of Outcomes Based on Launch Date
To analyze the relationship between the outcomes (successful, failed and canceled) and their launch date, the following steps are needed to be taken. First, the "Years" column was created. Next, a pivot table for the entire dataset was created with "parent category and years" in the filters field,"Date Created Conversion" in the rows filed, and "outcomes" in the columns and values files. After filtering the "Parent Category" to show only the theater and the "Outcomes Labels" to exclude the live, a line chart was created to visualize the data from the pivot table. 
![Theater_Outcomes_vs_Launch](https://user-images.githubusercontent.com/102785000/163666926-ad2c5dbe-7ad0-40a9-8ac4-de442127f3e8.png)
### Analysis of Outcomes Based on Goals
To analyze the relationship between the percentage of successful, failed and canceled plays and their funding goal amount, the following steps are needed to be taken. First, a table was created in a new worksheet. There are 12 groupings ranging from less than $1,000 up to more than $50,000. Then the COUNTIFS function was used to distinguish the total number of successful, failed, and canceled based on their amount of goal. Then a SUM function was used to calculate the total projects. After the percentage of successful, failed and canceled projects was done, a line chart was created to visualize the data.
![Outcomes_vs_Goals](https://user-images.githubusercontent.com/102785000/163666916-1280ee44-8b81-429d-92e9-b3b7a638872b.png)
### Challenges and Difficulties Encountered
While working on this project, I've encounterted some challenges and difficulties. Firstly, it's hard for me to determine which was the most appropriate to put in the filter, column, and row for creating a pivot table. If the pivot table was made wrong, the chart would not make sense. I was able to overcome it by trying multiple times. Secondly, it's the COUNTIF function. I'd selected the wrong column for the reference. 
## Results
- What are two conclusions you can draw about the Outcomes based on Launch Date?
The highest rate of launching a theater campaign is in May, followed by June. From October to December, there's a steady decline on the succcess rate.
- What can you conclude about the Outcomes based on Goals?
In analyzing the data, it can be concluded that the goal of less than $1000 and $1000 up to $4999 had the highest success rate. The higher goals didn't have nearly as high of a success rate.The higher funding goals of $45,000 and up to $50,000 or more had the lowest success rate.

- What are some limitations of this dataset?
The dataset does not contain enough data points for theater/plays category. If this project needs us to focus on theater/plays, it should have provided the most of the data points for that catogory.

- What are some other possible tables and/or graphs that we could create?
We could create a pivot table and column chart to compare all the different categories with different success rate in different months.
