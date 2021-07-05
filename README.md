# kickstarter-analysis
## Overview of Project
### Purpose
Create two separate graphs based on the following criteria. A chart that examines the launch date of Kickstarters compared to the outcome. Also, filter the data based on "Parent Category" and "Years".

The second chart required comparing the Goal amount to the outcome of the Kickstarters.
### Background
The task was to help Louise get a better understanding of the Kickstarter data initially given.

Louise specifically wanted to know how the date a Kickstarter campaign was launched and the goal amount of money the campaign asked for impacted the eventual success.
## Analysis and Challenges
### Analysis of Outcomes Based on Launch Date
![Theatre_Outcomes_vs_Launch](https://user-images.githubusercontent.com/85756203/124505421-1823e700-dd8f-11eb-9ee2-0911414aeba4.png)

There is an increase in the number of successful Kickstarter campaigns in May and June. Conversely, December had the lowest amount of successes.

There is no significant variation in the number of failures concerning the month it launched.
### Analysis of Outcomes Based on Goal
![Outcomes_Based_on_Goal](https://user-images.githubusercontent.com/85756203/124505489-3be72d00-dd8f-11eb-86d8-061f24eba7bc.png)

The Outcomes Based on Goal chart presents two distinct patterns.
Goals of less than 5,000 have about a 75% chance of success. Goals from the range of 5,000 to 24,999 see a drop to about 50% successful.

The Goals greater than 25,000 see an inconsistent pattern, possibly due to a limited sample size.
### Challenges
A challenge I encountered came during the creation of the Outcomes Based on Goals chart. There was an error in the chart when I first created it. The Percentage Canceled line had a value equal to the Percentage Failed value in one range. I had accidentally entered a "Failed" COUNTIF function in the Canceled column. I fixed the mistake, and the proper chart was displayed.
## Results
### Outcomes Based on Launch Date
The best time of the year for Louise to launch her Kickstarter would be in May or June. As described in the analysis of Outcomes Based on Launch Date, there is a clear jump in successful campaigns that start in those months.

The worst month for Louise to launch her campaign would be in December. There were only two more successful campaigns than failed campaigns.
### Outcomes Based on Goal
The targeted goal amounts for Louise's Kickstarter should be less than 5,000. In the less than 1,000 and 1,000 to 4,999 range, the percentage of success is around 75%. The success rate drops to about 50% in goals greater than 5,000, and for the largest amounts, the success rate appears too varied to conclude.
### Limitations
Looking at the analysis of Outcomes Based on Goals presented a challenge. There is limited data to pull from when the goal amounts reached the higher levels.

The Goals of less than 15,000 has 961 Kickstarters. The remaining eight intervals only contain 86 Kickstarters. It is difficult to conclude on the relationship of Goals and Outcomes with a limited amount of data points.
### Recommendations
An additional graph could be Outcomes based on the number of days a Kickstarter was active. To do this, we would create a row called Total Days Active (Date Ended Conversion - Date Created Conversion). Then use the COUNTIFS function to create intervals, and make the chart using the same method as Outcomes Based on Goals.
Louise would be able to see if there is a length of time where the outcome's success significantly changes.
