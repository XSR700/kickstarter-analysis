
# Kickstarting with Excel
Performing analysis on Kickstarter data to uncover trends.

## Overview of Project
This report visulizes the data of theater plays that have started crowdfunded campaigns across the world through Kickstarter. The visulation and calculation has been made using Excel Office 16 spreadsheets. Using the Kickstarter data, this project visulies campaign outcomes based on thier launch dates and funding goals. 

### Purpose
Louise is looking for an appropriate budget for her new play called "Fever". The purpose is to present Louise an illustration and discription of past crowdfunded plays, and give a conclusion from the findings to help her estimate a budget. 

## Analysis and Challenges


I aquired the data of 4113 past and present crowdfunded projects from Kickstarter. The data consists collumns     




### Analysis of Outcomes Based on Launch Date

Examining the "Theater Outcomes Based on Launch Date" chart below we can compare which month of the year effects a campaign. The chart displays the outcomes of successful, failed, and canceled campaigns in the theater category from January to December. The successful line spikes during May which means this month expriences the most of successful campaings. 111 out of 166 (67%) campaigns were sucessfful. However the grand total in May was the highest with 166 total campaigns. This also means that we are more likely to see more campaings being launched around May.

Another point to note is that the line of failed outcomes stays roughly the same throughtout the chart. May, June, July, and August have almost the same number of failed outcomes. This indicates that the spike of successful campaings in May had little to now effect on the rise of failed campaings. 

![Theater_Outcomes_vs_Launch_Date](https://github.com/XSR700/kickstarter-analysis/blob/main/Theater_Outcomes_vs_Launch_Date.png)


### Analysis of Outcomes Based on Goals

Looking at the "Outcomes Based on Goal" chart we can come up with an understanding of which funding goal to choose for our campaign. The chart displays percentage of outcomes of theater plays based on thier choosen goals within the given ranges. We notice that as the goal increases the campaign success rate decreases, however not consistently. After $25000 the Sum of Percentage Successful line starts to increase again and drastically come back down after $40000. With these huge up and down swings could suggest that there is not much data within those ranges. Its better to have a bigger sample pool to use for our analysis. Therefore after we could say after $15000 goal the odds of failure starts to increase.   

![Outcomes_vs_Goals](https://github.com/XSR700/kickstarter-analysis/blob/main/Outcomes_vs_Goals.png)

### Challenges and Difficulties Encountered

During the process of obtaining and working on the data, I went through 2 challenges and issues that I had to overcome. 

While I was familliar with using Excel, my first challenge was downloading the software on my personal laptop. I have always used Excel on my work computer and needed to subcribe new license for my own. Thankfully Excel provies a 1 month free trial for all registered users. After I signed up for the free trial and downloaded Excel, Microsoft denied access because my email was not "associated" with the registered account. It took me a few moments to google and understand what the issue was. Apperently I had another long forgotten Hotmail account that my Excel connected to. My past automatic log ins seemed to have helped link the account. I quickly learned in order to link the Excel to the correct account I had to go to File > Account > Manage Account to log out and sign in with the new account.

As I was working through the module, I came across an issue displaying my charts. In module 1.3.3 "Timing Success" the instuctions show how to create a pivot table with a chart to show theater outcomes for each month. I followed the instructions carefully and created my pivot table. My results matched exactly and everything worked fine. However when I pressed _PivotChart_ under _PivotChart Analyze_ the chart did not show up and nothing happend no matter how many times I clicked. I tried restarting Excel and even using a different computer, but nothing happend again. I reached out to one of the TAs and asked for help. The TA said that Excel doesnt know which data to represent and I should restart my Excel file from scratch. I still dont undstand what exactly went wrong in my original work, but I went ahead and restarted my work. I recreated all the new collumns and formulas, and tried creating the chart again. This time it worked and the results matched the findings in the module.  



## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?

After our analysis we can conclude that to be successful, time of the year to launch a campaign does matter. We see that May had the most amount of successfull campaigns. In practicality it makes sense. People tend to attend more events when springs and summer roll around, threfore bringing more attandace for theatrical plays. On these seasons people are in a better mood and more likely to pledge. These factors contribute to the success rate. 

nNonetheless there is a caviat to launching a camapign in the summer. May, June, and July had the most ammount of campaigns launched total. This means more cmpetition for Louise. While this could deminish her chances we still see the the failed outcomes line is not effected in a major way on any month. Louise chances of failure are slightly higher in the summer, but chances of success are reletively much greater in May, June, and July compared to any other month. After those months the successful outcomes quickly drop off. Louise should pick May or June to start her campaign. 


- What can you conclude about the Outcomes based on Goals?

After the analsysis of the "Outcomes Based on Goals" chart we can suggest Louise which budget to avoid. Louise mentioned that she needs more than $10000 for her play. This does is not an comftrable situation since the precentage of successful line starts to fall after $10000 to $14999 range. Louise does have the option to set her budget somehwere higher than $35000 and before $40000, but this is a risky option. While the chart shows that 67% of plays with a goal between $35000 to $39999 were successful, this does not mean Louise odds will hold up the same. The count of plays with a goal greater than  $25000 drastically drop off and create extreme dips and spikes in the chart. 

In conclusion Louise should consider making her goal less than $15000, because the chance of success will be in her favor. However if $15000 will not be enough to create a her play than she can consider setting a goal above $35000 and less than $40000. The Success percentage is higher within this range, but this will be a reisky option because there is not enough data above $30000 range to conclude this tendency to be true. 

- What are some limitations of this dataset?

One of the limitations from this datast is currency. Eventhough the "goal" and "pledged" collumns are converted to US dollars the value of each currency fluctuated differently throughout all the countries. If the US dollar drops value this year while Louise makes her budget and the British pound increase, this will illustrate a false narrative of how much people from Britan are will to pledge. In addition the expected rise in inflation over the past years may skew the true reasonable budget lower than what it should be. 


- What are some other possible tables and/or graphs that we could create?

The campaign date created and deadlines varied accross categories. We could create a graph to that shows which durations of a campaign resulted in most success. To do this we could take the differance of date created and deadlines. Then plot the duration by months on the X axis with pecentage on the Y axis and display the lines of successful outcomes and failed outcomes.   

