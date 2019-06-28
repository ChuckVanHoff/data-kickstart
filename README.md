# Kickstart a New Journey
Get the most out of a Kickstart

## My First Data Project -- Excel
This first data project uses Excel to clean, filter, organize, and otherwise prepare a dataset of about 4000 Kickstarter campaign records for analysis. It's also the first "data" project I've done.

### Background
Over two billion dollars have been raised using the massively successful crowdfunding service, Kickstarter, but not every project has found success. Of the over 300,000 projects launched on Kickstarter, only a third have made it through the funding process with a positive outcome.

Since getting funded on Kickstarter requires meeting or exceeding the project's initial goal, many organizations spend months looking through past projects in an attempt to discover some trick to finding success. For this week's homework, you will organize and analyze a database of four thousand past projects in order to uncover any hidden trends.

### Data
Data comes from database of Kick Starter campaigns. The data ranges from 5/2009 to 3/2017 and contains 3,859 records. The analysis is performed in Excel. 

Initially this data set was 4,115 records long. I decided to drop all the records that exceeded their goal by more than 100%. This was for the sake of creating a visualization that conditionally colored the cells according to the percent contributed of their stated goal. The total number of dropped records is 256, only 6.2% of the total data and 6.6% of the used data.

### Analysis
Category and sub-category

From the brief view of the data it’s clear that campaigns in the “Theatre” category did best, with that category being dominated by the sub-category for “Plays”.

<a href="url"><img src="https://github.com/ChuckVanHoff/data-kickstart/blob/master/charts/sub-category.png" align="center" height="500" width="880" ></a>

This should be based on the specific interests of the “kickstart-minded” campaigners and donners. I would expect to see clear trends through the data if more details about the (individual) people behind the kickstarts. Unfortunately that data was not present within the available data.

<a href="url"><img src="https://github.com/ChuckVanHoff/data-kickstart/blob/master/charts/category.png" align="center" height="400" width="600" ></a>

Launch Dates

Analysis of the successes according to their launch dates shows a bit of a double peak, with the most prominent peak rising in late spring and plateauing to mid summer before plummeting to near the annual low by late summer. 

<a href="url"><img src="https://github.com/ChuckVanHoff/data-kickstart/blob/master/charts/launch_date.png" align="center" height="450" width="660" ></a>

My guess is that this relates to student age ‘kickstarters’ completing their school year and, seeing a full summer ahead of them, decide to invest their newly abundant time on their dream project. The trend quickly fizzles out as the threat of a return to normal class schedule looms on the horizon, and the number of Kickstart launches rapidly declines.



Initial Goal

Further analysis offers more compelling trends. When “success” and “failed” are compared against each other, it looks almost like a direct inverse proportion relates the two lines. The percent of success declines continuously from it’s maximum of 65% at goals set under $1000 down to under 50% as the goal size rises above $5,000. The limit of the graph is all campaigns $50,000 and over lumped together, where the success rate is barely 30%.

<a href="url"><img src="https://github.com/ChuckVanHoff/data-kickstart/blob/master/charts/goal.png" align="center" height="336" width="600" ></a>

There is also a very clear, steady, though not quite as dramatic trend in canceled campaigns. This type nearly always is quite a bit less frequent of an outcome that either of the other two types. Only when the goal is set above $50K does the cancelation rate exceed the successful rate. One possible explanation might be simple: the higher the goal is set, the earlier it becomes apparent whether the goal is likely to be met; and as was observed above, the likelihood of success quickly approaches zero as the goal is set more and more above $45K.


### Conclusions
The core conslusions are: 

1.  Theatre all the way, baby!!! The most likely area of the whole Kickstart universe to be funded is in theatre.

2.  The more you seek to get as your goal, the less likely it is that you will succeed. There is, however, a bit if a high-end sweet spot around $35K-$45K that sees about 50% success.

3. Success is lowest around the end of the year. Whether this is because of seasonal or holidy or something else influencing outcomes, Kickstart donners won't be back until spring.

### Future Work
Future analysis might try other methods for improving visualizations. Perhaps more detailed data on the campaigns and their outcomes: perhaps some information about the “Kickstarter”, for instance, personal demographics, address or more specific location information, even information about the donations and their donners would allow for broader and more granular analysis.
