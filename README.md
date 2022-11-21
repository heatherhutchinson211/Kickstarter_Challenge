# Kickstarter_Challenge

## Overview of Project
### Purpose
This project was designed to analzye trends between successful, failed, and cancelled goals among campaigns for plays using the data provided. A few visualizations were made in order to better see how these trands occurred and make reasonable changes for goal setting and launch dates in future campaigns. 

## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date
The first analysis on the data that I did was a look into the trends on how outcomes were affected by the date that the campaign was launched.  I looked specifically at theater campaigns and how often these goals were achieved based on which months they were launched in.  I set up a pivot table that allows you to see the outcomes of the campaigns in the theater category; however, you can also change the filter in order to see how other categories of campaigns were affected as well.  The table is also set up so that you can dive deeper into one certain year and see how campaigns did in that specific year.  

I then created a line graph to visualize the theater outcomes vs launch dates, as shown below.

![Theater_Outcomes_vs_Launch](https://user-images.githubusercontent.com/117620028/202964441-30bce308-e112-426c-bfc7-87ce21bcb9f0.png)

As you can see, December was the month in which the number of failed and successful goals were closet to being the same, which leads me to believe that this was the most unsuccessful month based on overall launches.  May had the most successful launches, but it also was the month with the most failed laumches.  This is where this analysis may lack, because rather than showing percentages of failed, successful, and canclelled campaigns, it is only shoiwng the number.  May could have just been the month with the most campsigns overall which is why there were so many successes.  

### Analysis of Outcomes Based on Goals
The second analysis I did was an analysis of the success of campaigns based on their initial goals.  I focused in on plays specifically and analyzed 11 different ranges between being less that $1000 goal, to being more than a $50,000 goal.  I looked only at the number of each that were successful, failed, or cancelled.  I then calculated the percentage each of these were out of the total number of campaigns in each goal range.   After inputting some of my data, I found that there actually weren't any cancelled play campaigns, which simplified this analysis quite a bit.  I then created a line graph that visualized how the percentages of failed and successful campaigns varied based on these goal ranges, as shown below. 
![Outcomes_vs_Goals](https://user-images.githubusercontent.com/117620028/202965621-897d77af-8c0c-40dd-8ee8-33da886df091.png)
 After viewing the data in this graph, it seems that there was not a clear linear trend between a higher goal and the campaigns success rate, as I would have guessed there would have been.  However, when the goal gets to $45000 and above, there are a significant amount higher failed campaigns than successful ones. 
 
### Challenges and Difficulties Encountered
One challange, mentioned earlier, was that with my first analysis, I would have liked to see the percentages displayed, rather than just the counts, in order to more accurately depict trends inthe data.  This was challenging for me to make assumptioins due to this difficulty.  
Another challenge I faced was the process of using the COUNTIF() function to pull my data.  It was a big learnign curve for me, and I didn't realize for a while that you instead had to use "COUNTIS()" if using more than one range.  Other than that, this analysis went fairly smooth.  

## Results
* Based on the Outcomes based on Launch data, I can make two conclusions.  First, december seems to be the most unsuccessful month to launch.  Second, May seems to be the most popular month to launch, with lots of successes and failures alike. 
* Based on the outcomes Based on Goals analysis, I can conclude that any goals higher than $45,000 are very unlikely to succeed.  Additionally, goals between 0 and $10000 are likely to do very well, in the plays subcategory. 
* Some limitations I encountered were again, the lack of percentages displayed in the outcomes based on launch year.  I also think that the second analysis could have been displayed without the "canceled" category, and been analyzed in the same way; however, it was good ot see that there were no cancelled campaigns in the plays subcategory.
* For future analysis, I would like to filter the Outcomes Based on Launch analysis to show just US campaigns, or any other country in particular.  I would also like to create a blend of the two data sets to show those pers=centages of failed and successful lanuhces, based on launch date.  It would also be interesting to analyze the Outcomes based on goals, but look at a few different subcategorys and see how the results vary.  
