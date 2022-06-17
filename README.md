# An Analysis of Kickstarter Campaigns
  Using Excel to visualize Kickstarter campaign outcomes based on a number of criteria. Goal to become more familiar with both basic Excel techniques and more advanced   tools.

## Analysis and Challenges
### Overview
  ![Theater_Outcomes_vs_Launch](./Resources/Theater_Outcomes_vs_Launch.png)
  * There are clear patterns in both sets of data. The image above shows outcome totals for each month of the year for all years in which data was collected for theater projects (2009-2017). This monthly aggregate indicates a seasonal trend for theater projects.


  ![Outcomes_vs_Goals](./Resources/Outcomes_vs_Goals.png)
  * Taking a look at project outcomes based on the amount of money they hoped to raise, there are some predictable trends, with positive correlations between higher goals and the percent of projects failed and canceled. 


### Challenges
  I had no hiccups when completing the project, but some aspects took longer than others. For example, filling in outcomes based on goal data was a bit tedious as I couldn't copy the formula across cells without adjusting dollar amount parameters (i.e., ">1000", ">5000", etc.), or across columns without adjusting outcome. Otherwise, I thought it was relatively straightforward with clear instructions. I could see COUNTIFS() and the concept of a function with multiple groups of parameters posing difficulty, but having experience with Excel and the use of formulas made it a little easier for me to implement.
  
  
## Results
### Theater Outcomes by Launch Date
  The data collected seems to indicate a seasonal pattern both for success and for the number of projects. There is a sharp spike in the total number of projects between March and May, which gradually declines as the summer months bleed into fall. This spike can be seen most clearly in the number of successful campigns, but can be seen in all three sets of outcome data. That said, with all three outcome totals rising we can assume the total number of campaigns is increasing. What is importnat though, is that although the total number of campaigns has increased, a greater percentage are successful from May to August. We know this because the difference between the number of successful campaigns and the number of failures is much greater in these months than at any other point in the year, indicating a 
