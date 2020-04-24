# An Analysis of Kickstarter Campaigns
Performing analysis on kickstarter data to uncover trends related to crowd funding a theatrical experience. 

![Outcomes Based on Launch Date.png](https://github.com/jburs/kickstarter-analysis/blob/master/Outcomes%20Based%20on%20Launch%20Date.png)

The above figure shows the outcome trendlines for funding projects based on the month funding began. Based on the above data, the optimal times to begin a kickstarter campaign is May, with February being the second. These two months have the high success rates, and the largest difference between successful, and failed kickstarters. 

![US Funding Outcomes by parent category.png](https://github.com/jburs/kickstarter-analysis/blob/master/US%20Funding%20Outcomes%20by%20parent%20category.png)

Theater projects in the US are corwdfunded frequently on kickstarter. They have the highest number of projects both sucessful and failed. Based on this, some advertising/ensentive is recomended to ensure your project gets viewed and traction on kickstarter. 

![US Theater Funding success rates.png](https://github.com/jburs/kickstarter-analysis/blob/master/US%20Theater%20Funding%20success%20rates.png)

Expanding on the previous chart, and diving into the Theater subcategory, we see that plays are the most popular, and most successfully funded. 

![Kickstarter_Descriptive_Statistics.png](https://github.com/jburs/kickstarter-analysis/blob/master/Kickstarter_Descriptive_Statistics.PNG)

Looking to the descriptive statistics. The successful kickstarters for plays have a mean goal of $5,049 and receive much higher value donations than the failed kickstarters. However, the standard deviations (std) are all roughly twice the interquarterly range (IQR) in each distribution, meaning the aveage goal and pledge are being skewed by some very large goals and pledges. This is exagerated further in the failed kickstarters where the std is three times the IQR.


To conclude, it is recomended a goal of roughly $5000, and to begin funding in May for your theatrical play 'fever'. There are limitations within this anylsis, specifially the lack of specific data on theatrical plays, with roughly 675 data points. 


### Challenge

![Kickstarter_Descriptive_Statistics.png](https://github.com/jburs/kickstarter-analysis/blob/master/Plays%20Outcomes%20Based%20on%20Goals.png)

The above line chart shows the relationship between the outcome, and goal for kickstarter plays. In order to select a goal with a the highest rate of success, we will look at the difference between the percent successful trendline, and the sum or percent failed and cancelled. The three most successful ranges are 15000-19999, Less than 1000, and 1000-4999. From the general trend of the three outcomes, it is clear that as we increase the goal, we decrease the percentage of successful kickstarters, and increase the percentage of cancelled and failed kickstarters. This plot and analysis is limmited by the spread of the data, he number of data points are heavily squed toward smaller funding goals. The large peak at 15000-19999 contains 1.4% of the total data, whereas the 1000-4999 range contains 45.1% of the total data points. This significantly lowers the statistical significance of the chart as the goal amount increases due to lack of data. 
To conclude, The recomended goal amount to set is within the 0-4999 range, or even the smaller portions of 5000-9999 range. The 15000 to 19999 range is not recomended due to lack of statistical significance from the small number os data points. b


![Kickstarter_Descriptive_Statistics.png](https://github.com/jburs/kickstarter-analysis/blob/master/Plays%20Outcomes%20Based%20on%20Launch%20Month.png)

The Plays' Outcomes Based on Launch Month chart is based off of data from 2009 - 2017 kickstarter plays, and organized monthly. By comparing the difference between the successful, and failed treadlines we can see the optimal months to begin the kickstarter campaign. The canceled treadline is relatively horizontal and low, so it can mostly be ignored. The optimal months to begin the kickstarter are May and June. These months also have the highest numer of kickstarter campains, so advertisement is recomended to help gain funding. This data is limited by the date range of the data. The majority of datapoints come from 2014-2016, making 2010-2013 and 2017 not a random distribution, and reduce the statistical accuracy of the data. However, these datapoints contribute to a very small portion of the total data, allowing us to still pull conclusions from the line graph. 


