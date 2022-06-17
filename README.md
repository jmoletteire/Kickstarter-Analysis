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
  The data collected seems to indicate a seasonal pattern both for success and for the number of projects. There is a sharp spike in the total number of projects between March and May, which gradually declines as the summer months bleed into fall. This spike is most obvious based on the number of successful campigns, but is evident when checking all three sets of outcome data for May to August. That said, with all three outcome totals rising we can assume the total number of campaigns is increasing. What is important though, is that although the total number of campaigns has increased, a greater percentage are successful from May to August (during the spike) as well. We know this because the difference between the number of successful campaigns and the number of failures/cancelations is much greater in these months than at any other point in the year, indicating an ideal time for theater campaigns.
  
  A curious development is in October. There is a small spike in both successes and failures here, but the gap between the two narrows, which would indicate a greater percentage of failed projects that month. This may indicate that simply increasing the total number of campaigns does not guarantee greater success, which may depend more greatly on the time of year.
  
### Outcomes based on Goals
  As expected here, the greater the campaign goal, the more likely it failed. There may be a bit of a sweet spot - between $30,000 and $45,000 - where percent failed and percent canceled declined while percent successful rose, but in general there was a positive correlation between campaign goal and percentage failed or canceled (and vice versa for successful campaigns).
  
### Limitations
  While this data is relevant for the populations represented, it would not be accurate when drawing conclusions for the entirety of the data. The first chart only covers theater - a small portion of its parent category - while using monthly totals to visualize success/failure. It would be more helpful to use percentages for each month, perhaps in a stacked bar chart, as one can more quickly assess the data. Perhaps a greater problem with using totals is the possibility of outliers, which may have greatly skewed the data. Maybe May of 2012, saw a boom in successful campaigns in what is traditionally an uneventful month for theater?  In this case, we may be forced to throw out all of the above conclusions.
  
  The second chart does use percentages, and while it is useful, it is also a bit vague. This chart includes data from every category and country, which makes it an unreliable tool for assessing the plausibility of specific campaigns in specific regions. It is nice to see the general correlation between goal and outcome, but it isn't completely reliable for decision-making purposes.
