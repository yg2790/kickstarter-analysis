# Kickstarting with Excel

## Overview of Project
### Purpose
Performing analysis on Kickstarter data to uncover trends between the launch days of campaigns and fundraising goals to support Louise's play *Fever*. 

## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date
Based on Launch Date, we can see that the number of successful events peaks in May at 111. The overall number of successful Kickstarter events in the theatre category is higher during the summer months than other times of the year with June, July, and August having the second to the fourth highest, with 100, 87, and 72 counts, respectively. 
  ![Theatre_Outcomes based on Launch Date](/Users/yutinggao/Desktop/DA Boot Camp/Crowdfunding Analysis/Theatre_Outcomes_vs_Launch.png)
  Going a step further, by isolating the plays from the theatre category, we can identify that it has a similar trend as the overall theatre parent category with the highest success in fundraising events during the summer months. 
  ![Plays Outcomes based on Launch Date](/Users/yutinggao/Desktop/DA Boot Camp/Crowdfunding Analysis/Plays_Outcomes_vs_Launch.png)

### Analysis of Outcomes Based on Goals
Through categorizing goals by 5,000s from less than 1,000 to over 50,000, we analyzed the number of events in each outcome for all plays in the dataset. The highest success rate of 76% with 141 successfull crowdfunding events out of the total 186 events with goals of raising less than $1,000. The second-highest success rate is in the goal $1,000 to $4,999 category of 73%, accounting for 51% of all 1049 Kickstarter events in the plays category with 388 out of 534 in the goal category.
  ![Outcomes based on Goals](/Users/yutinggao/Desktop/DA Boot Camp/Crowdfunding Analysis/Outcomes_vs_Goals.png)

### Challenges and Difficulties Encountered
I did not run into any challenges and difficulties during this analysis. However, one potential issue can be that the data provided might not be clean and require the analysts to take further steps to ensure all data are formated properly and ready for analysis. An example of formating error can be the currency of the goal and pledged crowdfunding values. Since this dataset includes data from different nations, if not properly calculated, large currency differences can significantly impact the accuracy and reliability of the analysis. 

## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?
  Louise should schedule the launch date of the Kickstarter crowdfunding event for the play *Fever* in May to ensure the highest chances of success in meeting the goal. Louise should also avoid December due to past data illustrating high chances of failure in meeting the goal and low chances of success in the same month.

- What can you conclude about the Outcomes based on Goals?
  I can conclude that Louise will be more likely to meet her fundraising goal if it has been set to a lower amount of below $5,000. As the goal becomes more ambitious or higher, past data shows that the likelihood of failure increases, and the number of successes in past data decreases.

- What are some limitations of this dataset?
  The limitations to this dataset are the limited variables that tie more specifically to Louise's needs. Many other factors can contribute to the success of the event such as the quality, genre, target audience, plot of the play, the actors, the location of the event, as well as the budget for marketing strategies, advertisements, etc. Due to the broadness of this dataset, such as other large parent categories and countries, many of these data will not be suitable to help Louise conclude.

- What are some other possible tables and/or graphs that we could create?
  Another possible table is to analyze the outcomes by country/region. Certain countries might have a higher success rate than others depending on the consumer culture for plays. A pivot table can be created, filtered by parent category theatre, with countries in rows, outcomes in columns, and counts of outcomes in values.
  Another graph that one can create is the relationship between outcomes and crowdfunding event duration. The length of the event can significantly impact the success rate. We can create a scattered plot to demonstrate clusters and identify patterns of the two variables. 
