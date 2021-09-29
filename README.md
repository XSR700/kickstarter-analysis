
# Kickstarting with Excel
Performing analysis on Kickstarter data to uncover trends.

## Overview of Project
This report visualizes the data of theater plays that have started crowdfunding campaigns across the world through Kickstarter. The visualization and calculation have been made using Excel Office 16 spreadsheets. Using the Kickstarter data, this project visualizes campaign outcomes based on their launch dates and funding goals. 

### Purpose
Louise is looking for an appropriate budget for her new play called "Fever". The purpose is to present Louise with an illustration and analysis of past crowdfunded plays and give a conclusion from the findings to help her estimate a budget. 

## Analysis and Challenges
   


### Analysis of Outcomes Based on Launch Date

Examining the "Theater Outcomes Based on Launch Date" chart below we can compare which month of the year affects a campaign. The chart displays the outcomes of successful, failed, and canceled campaigns in the theater category from January to December. 

We see that successful line spikes in May which means this month experiences the most successful campaigns. 111 out of 166 (67%) campaigns were successful. However, in May alone a grand total of 166 campaigns were launched which is the highest. This also means that we are more likely to see more campaigns being launched around late spring to the peak of summer because June and July were 2nd and 3rd highest respectively.

Another point to note is that the line of failed outcomes stays roughly the same throughout the chart. May, June, July, and August have almost the same number of failed outcomes. This indicates that the spike of successful campaigns in May had little to no effect on the rise of failed campaigns. 

![Theater_Outcomes_vs_Launch_Date](https://github.com/XSR700/kickstarter-analysis/blob/main/Theater_Outcomes_vs_Launch_Date.png)


### Analysis of Outcomes Based on Goals

Looking at the "Outcomes Based on Goal" chart we can come up with an understanding of which funding goal to choose for Louise's campaign. The chart displays the percentage of outcomes of theater plays based on their chosen goals within the given ranges. We notice that as the goal increases the campaign success rate decreases, however not consistently. After $25000 the Sum of Percentage Successful line starts to increase again and drastically come back down after $40000. These huge up and down swings could suggest that there is not much data within those ranges. It's better to have a bigger sample pool to use for our analysis. Therefore it's more useful to suggest that after the $15000 goal the odds of failure start to increase.   

![Outcomes_vs_Goals](https://github.com/XSR700/kickstarter-analysis/blob/main/Outcomes_vs_Goals.png)

### Challenges and Difficulties Encountered

During the process of obtaining and working on the data, I went through 2 challenges and issues that I had to overcome. 

While I was familiar with using Excel, my first challenge was downloading the software on my personal laptop. I have always used Excel on my work computer and needed to subscribe new license for my own. Thankfully Excel provides a 1 month free trial for all registered users. After I signed up for the free trial and downloaded Excel, Microsoft denied access because my email was not "associated" with the registered account. It took me a few moments to google and understand what the issue was. Apparently I had another long forgotten Hotmail account that my Excel connected to. My past automatic log-ins seemed to have helped link the account. I quickly learned in order to link the Excel to the correct account I had to go to File > Account > Manage Account to log out and sign in with the new account.

Now with a working full version of Excel, I was working through the module and I came across an issue displaying my charts. In module 1.3.3 "Timing Success" the instructions show how to create a pivot table with a chart to show theater outcomes for each month. I followed the instructions carefully and created my pivot table. My results matched exactly and everything worked fine. However, when I pressed _PivotChart_ under _PivotChart Analyze_ the chart did not show up and nothing happened no matter how many times I clicked. I tried restarting Excel and even using a different computer, but nothing happened again. I reached out to one of the TAs and asked for help. The TA said that Excel doesn't know which data to represent and I should restart my Excel file from scratch. I still don't understand what exactly went wrong in my original work, but I went ahead and restarted my work. I recreated all the new columns and formulas and tried creating the chart again. This time it worked and the results matched the findings in the module.  



## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?

After our analysis, we can conclude that to be successful, the time of the year to launch a campaign does matter. We see that May had the most amount of successful campaigns. In practicality it makes sense. People tend to attend more events when spring and summer roll around, therefore bringing more attendance for theatrical plays. In these seasons people are in a better mood and more likely to pledge. These factors contribute to the success rate. 

Nonetheless, there is a caveat to launching a campaign in the summer. May, June, and July had the most amount of campaigns launched total. This means more competition for Louise. While this could diminish her chances we still see the failed outcomes line is not affected in a major way on any month. Louise's chances of failure are slightly higher in the summer, but chances of success are relatively much greater in May, June, and July compared to any other month. After those months the successful outcomes quickly drop off. Louise should pick May or June to start her campaign. 


- What can you conclude about the Outcomes based on Goals?

After the analysis of the "Outcomes Based on Goals" chart we can suggest to Louise which budget to avoid. Louise mentioned that she needs more than $10000 for her play. This does is not a comfortable situation because the percentage of the successful line starts to fall after the $10000 to $14999 range. Louise does have the option to set her budget somewhere higher than $35000 and before $40000, but this is a risky option. While the chart shows that 67% of plays with a goal between $35000 to $39999 were successful, this does not mean Louise's odds will hold up the same. The count of plays with a goal greater than  $25000 drastically drops off and creates extreme dips and spikes in the chart. 

In conclusion, Louise should consider making her goal less than $15000, because the chance of success will be in her favor. However, if $15000 will not be enough to create her play then she can consider setting a goal above $35000 and less than $40000. The Success percentage is higher within this range, but this will be a risky option because there is not enough data above the $30000 range to conclude this tendency to be true. 

- What are some limitations of this dataset?

One of the limitations of this dataset is currency. Even though the "goal" and "pledged" columns are converted to US dollars, the value of each currency fluctuated differently throughout all the countries. For example, If the US dollar drops value this year while Louise makes her budget and the British pound increase, this will illustrate a false narrative of how much people from Britain are willing to pledge. In addition, the expected rise in inflation over the past years may skew the truly reasonable budget lower than what it should be. 


- What are some other possible tables and/or graphs that we could create?

The campaign date created and deadlines varied across categories. We could create a graph that shows which durations of a campaign resulted in the most success. To do this we could first take the difference of dates created and deadlines. Then create a pivot table to display campaign length among plays. Then plot the duration by months on the X-axis with percentage on the Y-axis and display the lines of successful outcomes and failed outcomes.   

