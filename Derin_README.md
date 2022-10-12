# (Dataset Exploration Title)
## by (your name here)


## Dataset

The data consists of information regarding 174,952 ford go-bike rides, including duration in seconds, time period, time taken, station names and ids other properties. The dataset can be downloaded via this [link](https://www.google.com/url?q=https://www.fordgobike.com/system-data&sa=D&ust=1554484977399000)


## Summary of Findings

>
During exploration I found that there where time periods and days when the number of rides were significantly higher than the others. During weekdays the number of trips per day were generally a lot more than what we had on weekends. In terms of hours trips started we had, the peaks at periods between 7-9 am and 16-18 pm, periods where people leave for work and close from work respectively. The duration of trips were rightly skewwed, generally trips were atleast longer than 1 minute and shorter than 30 minutes with the mode of the duration being between 5-6 minutes. The generated displacement and aveg_velocity only give an idea as to the distance and average speed between the start and end stations. However, the bivariate plot of the displacement against duration showed that as displacement increases the minimum time taken on trips also increase, indicating a reltionship, one which might have been clearer if we had the actual distances.
I also looked at the top 10 bike id's, start stations and end stations. Majority of the top start stations were present in the top 10 end stations. I found that some stations didn't follow the status quo trends.

> 
Apart from the main variables I also looked at the user_type and bike_share categorical features. My observations were that the average displacement for customers were longer and that no customer had a Yes value for the bike_share_for_all_trip feature.


## Key Insights for Presentation

> 
For the Presentation I focused on the Top 10 start stations. I explore the difference in distributions of numeric features for each start station in the top 10. I also look out for the counts per value for categorical features.
>
I start by introducing them through an horizontal bar graph. The bar graph shows their overall number of rides within the entire time frme of the dataset.  
>
Next, I break down the number of rides per day and then per hour, using both crosstabs and countplots. I also look at the numeric features; duration and displacement. I check if the top 10 stations have different distributions from what we have in the general distribution of said numeric features. 
Lastly I bring them together in multivariate plots using line plots with station names on the x-axis, day of the week as hues, displacement on the y-axis for one and duration for the other.