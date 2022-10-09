# kickstarter-analysis
Performing analysis on kickstarter data to uncover trends

## Overview
Louis held a fundraisers for her plays and in that time she request that I create a visual of the different campaigns in relation to the different outcomes based on **Launch Dates** and **Funding Goals**. 

## Analysis and Challenges

###### Theater Outcomes Based on Launch Dates

![Graph1](https://github.com/oroosevelt/kickstarter-analysis/blob/main/Theater_Outcome_vs_Launch.png)

Overview: The graph visualizes the percentage of outcomes by month for the parent category filtered by "Theater."

Analysis -The goal was to make sure I was able to filter the parent category by genre and years. The pivot table then needed to display the results of "theater" by the outcomes for each month for all the years combined. Therefore making it easier to understand, which month had the most results for each outcome.

Challenges -Some of the challenges I faced were filtering the field names in to the correct filters for the pivot table. Before begining. I switched the fields in to differet sections of the PivotTable Fields. This helped me understand the purpose of each fields sections and how the information will be used. 

In conclusion, the number of successful outcomes surpassed both failed and canceled pledges, especially inthe months of May. The amount of successful pledges begin to plummit towards the end of the year. You will also notice no cancellatons for the month of October when failed pledges takes a sudden peak. 

###### Outcomes Based on Goals

![Graph2](https://github.com/oroosevelt/kickstarter-analysis/blob/main/Outcomes_vs_Goals.png)

Overview: The outcome percentages based on the amount of pledged funds for subcategory "Plays"

Analysis: Looking at the analysis, you can see that the higher the goal was the percentage of failed outcomes were more than 80%. The outcome of successful never reached more than 80%. The highest amount of successful outcomes were pledges $1000 or less, which was the highest that resulted in success. within a goal ranged $15,000 to $19,999 had the exact same amount of success and failed goals reached. With the subcategory of _Plays_, there were no cancellations.

Challenges- Some of the challenges some may run in to if entering the correct formula with the correct data from another sheet. You have to make sure that the information is specific or the results will not appear correctly. 

In Conclusion, although no pledges cancelled on the subcategory _Plays_, the amount of successful goals reached were less than 80% in all ranges, down to 0%. The higher the range, the goals were achieved more frenquently 

###### Results
What are some limitations of this dataset?

*The limitations from the dataset were that we could only give a specific analization for 2 different categories, instead of all
    
What are some other possible tables and/or graphs that we could create?

*Some possible graphs we could have used was a stacked bar graph. That wouls display a difference in between the two ouctomes 
