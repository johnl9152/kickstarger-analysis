# An Analysis of Kickstarter Campaigns
## Overview of Project
In this challenge, Louise needed assistance in organizing a spreadsheet for Kickstarter campaign. A specific data that Louise required was the trends of theatrical projects, like plays.

The purpose of this challenge is to fully incorporate the excel skills learned from Module 1 and analyze if performance of plays had any relationship with the launch dates and the funding goal.

## Analysis and Challenges
When the excel spreasheet was first given, there was a necessity for more analysis because the spreadsheet was still too broad to analyze so the process of breaking down the data. For example, the column for category and subcategory had to be broken down to two separate columns through "Convert Text to Column Wizard".

The end goal for this challenge was to see if there was any relationship between funding goals and the plays' launch date. Before going deeper into this challenge, further organization was needed in the Kickstarter spreadsheet because it did not have enough detailed data to show the relationship of time and funding goals. In order to organize the spreadsheet, the "years" column was created from the "date created conversion" column made by outputting years only by "=years()" formula. Afterward, a pivot table was created, titled "Theater Outcomes Based on Launch Date", to further sort the spreadsheet. In the pivot table field, "parent category" and "years" were placed in filter, "outcomes" was placed in columns, "date created conversion" was placed in rows, and "count of outcome" was placed in values. In addition, the pivot table was further sorted by showing only "theater" numbers through filtering the "parent category" and the "count of outcomes" was organized through ascedning from January to December. Lastly, a line graph created to showed the pivot table's relationship between the launch date and the campaign's outcomes through individual months in a year.
![Theater_Outcomes_vs_Launch](https://user-images.githubusercontent.com/92328984/138562580-421b8c41-e5c4-4f92-bf63-b271bf4b486b.png)

The next step was to see if each campaign reached the funding goal and to see if the funding goal had to do with the percentage outcomes. After adding a new spreadsheet, a table was created with columns of goal amount between less than 1000 and greater than 50000 but divided into 12 rows. Furthermore, the table was organized between numbers of success, fail, or cancel, which could be converted into percentages success, fail, or cancel. The major command that was used "=countifs" to eliminate needless data according to the goal column. After inputting all "countifs" command in the number successful, failed, and canceled columns, the sum of the total projects are calculated. Lastly, each success, failed, and canceled were multiplied to the total sums in order to find out the percentages of all results. To see the trend between many different ranges of the goals, a line graph was appropriate for this situation to see the difference between all ranges from less than $1000 to greater than $50000. As shown below, most plays less than 1000 goal was more successful and the trend slowly began to decrease. On the other hand, the plays began to fail when the goal for the money slowly increased and there was a 100% fail with the range of 45000 to 49999.
![Outcomes_vs_Goals](https://user-images.githubusercontent.com/92328984/138601308-41ab034e-9c6a-497b-888a-6284d51364a4.png)

There were many moments of difficulties and challenges in this project. I think one of the biggest challenge I faced was when I was trying to determine which field was appropriate to plug in. As this was my first time encountering the pivot table, I am still trying to understand why each field belonged to the categories and how those categories can produce the pivot table. Before doing the pivot table, it would be good to fully understand the table and which data was appropriate to produce the pivot table that a person would want in a presentation or a team meeting.

## Results
- What are two conclusions you can draw about the Outcomes based on Launch Date?

After looking at the spreadsheet and creating a pivot table and a line graph, May and June were a great time to begin a theather campaign with the success number of 111 and 100 respectively. The trend began to slow down as the month passed by after June. Even though there was a light increase in October with no failed theater campaign, the lowest point of the campaign was December. I could infer that December was the lowest due to the end of the year and people could have different priorities other than going to support a play.

- What can you conclude about the Outcomes based on Goals?

As spoken before, campaigns with the goal of less than $1000 were the most successful in ratio between success and fail. The trend of increasing increment of failure percetange occurred as the funding goal increased.

- What are some limitations of this dataset?

The main limitation of this dataset was the broad ranges of categories and subcategories. If we were actually looking forward to see the numbers and percentages of success, fail, and cancel, the data in the spreadsheet could have decreased and narrowed down to only show theaters and plays for better accuracy and precise pivot tables and graphs. Having more data in unnecessary areas are not helpful when data scientists are trying to figure out a specific problem in a large model. Also, including different platform of kickstarter campaigns pertaining to theaters and plays would have been good since this project only included from one source.

- What are some other possible tables and/or graphs that we could create?

IN the categories of plays, comparison of different plays earning more support could have been created because some plays are more popular and would add more funds in the campaigns. Through that argument, a bar graph would be an appropriate visualization because it would compare different plays with various fundings that some popular plays would get and the campaign fund managers would come up with ideas to promote not well known plays. Through this process, different campaigns would get equal opportunities to promote and fund their plays despite the competition of well known plays. 

