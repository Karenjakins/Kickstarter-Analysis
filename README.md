# Kickstarter Analysis

## **Overview of Project**

The following analysis was conducted for Louise to ensure the success of her crowdfunding play Fever, the analysis was based on real world data and trends of thousands of campaigns to provide her with in depth feedback to ensure she achieved her goals.

## **Analysis and Challenges**

Throughout the analysis, we found trends that were responsible for the success of many plays in the United States, we added data visualization to make it easy for Louise to understand it and make the most of this information.

Since Louise was going to launch her theatre campaign in the US, we filtered the data to display the results for all the theatre fundraisers conducted in the US. We also applied conditional formatting to easily visualize the data by colour-coding the successful, failed and cancelled campaigns. 

[conditional formatting]

Since we found there was a correlation between successful campaigns and the month of the year they were launched, we created a pivot table to help Louise pick the most successful date to start her fundraiser. 

[successful months]

As for her fundraising goal, we used descriptive statistics to help Louise pick a fundraising amount by finding the median of goal and pledged amounts of successful theatre campaigns so that Louise can pick a realistic amount. 

### Analysis of Outcomes Based on Launch Date

Based on the data we had on theatre fundraisers we created a pivot table to filter by successful, failed and cancelled fundraisers based on the month. Once the chart was generated, we were able to observe that campaigns launched during the summer months had a higher success rate compared to the rest of the year. The line graph can be referenced below:

![alt text] [Outcomes Based on Launched Date]

[Outcomes Based on Launched Date]: https://github.com/Karenjakins/kickstarter-analysis/blob/main/Theater_Outcomes_vs_Launch.svg "Outcomes Based on Launched Date"

### Analysis of Outcomes Based on Goals

For the analysis on Outcomes Based on Goals, we observed that the if the goal amount is within less than $1000 and up to $14999 the success rate is higher, and the number of failed fundraisers is low. Please reference the line graph below:

![alt text](https://github.com/Karenjakins/kickstarter-analysis/blob/main/Outcomes%20Based%20on%20Goal.png "Outcomes Based on Goal")

### Challenges and Difficulties Encountered

The biggest challenge I had was when conducting the analysis of Outcomes Based on Goals, when I entered the formula for **=COUNTSIFS** as I entered the wrong angle brackets which provided me with the wrong values. I spent a few hours trying to figure what was wrong so this actually wasted a lot if my time, so next time I will make sure to be more careful when entering my formulas. 

The second challenge was that at some point during the analysis I must have entered or altered some of the values on my spreadsheet and as a result I got the wrong values on one of my tables, so it’s very important to save your progress as you go in separate files to make sure you don’t have to do the ensure process from the beginning. 

## **Results**

- What are two conclusions you can draw about the Outcomes based on Launch Date? 

Based on the data collected for Theatre Outcomes by Launch Date we can observe that fundraisers launched during the months of April to September have a greater success rate than at any other time during the year. This most likely can be that the summer months are better times to run campaigns are people are more interested in investing in activities. 

- What can you conclude about the Outcomes based on Goals?

Fundraisers with a goal lower than $15,000 tend to be more successful as the amount gets lower, the most successful being a 76% success rate for campaigns under $1000. 

- What are some limitations of this dataset?

There isn’t any data on the demographics of the people who pledged in the fundraiser, perhaps if we knew more about the investors, we could also know how to cater campaigns to target goals based on specific ages groups and interests. 

- What are some other possible tables and/or graphs that we could create?

We could create a table that displays the genre of the play and then create a graph that shows the correlation of success rate based on the genre. 
