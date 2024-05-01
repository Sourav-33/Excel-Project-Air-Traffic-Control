# Excel-Project-Air-Traffic-Control

This dataset provides U.S. monthly airline traffic from 2003 to 2023, including number of passengers, number of flights, revenue passenger-miles (RPM), available seat-miles (ASM) and load factor.

Inspiration
Time series analysis is a statistical method used to analyse data points collected or recorded at specific time intervals. This method can reveal trends, patterns and other significant information from the data as it evolves over time.

In the context of airline traffic data, time series analysis can be used to predict future air passenger numbers based on historical data, which can help with capacity planning, pricing strategies and other business decisions.

Step 1
Now the dataset on which I am working is taken from Kaggle and it’s an air traffic record of the domestic and international flights of the United States. The dataset contains of a total of 18 columns and 250 rows.
Now the main key factors of the dataset are:
1.	Number of Passenger 
2.	Number of flights
3.	The revenue of passengers per mile which is the total number of miles flown by paying passengers on U.S. airlines.
4.	The availability of seats per mile, that is the total number of seats available for passengers on U.S. airlines.
5.	The Load factor which is basically the ratio of the revenue and availability of seats per mile. 

Step 2:
Here the project focuses on the following objectives. 

Now for the first objective, this is the dashboard which I have made, which consists of the Quarterly flight variation, The Revenue per mile based on international and domestic flights, The passenger variation along the course of time, And the load factor for the domestic and international flights. 
	Now we can see the data of the dashboard changes according to the slicers. For example, if considered the research question 1 that is determining the month with the highest and lowest travel frequency. We clearly see that in the month of July there is a maximum number of flights, that is 0.8 million, and in the month February it is the least that is less than 0.7 million. And hence we can solve other business questions from this dashboard as well. 

Step 3:
Moving on to the research question 1, to verify the result in the dashboard I have used the help of pivot table to determine the frequency of passengers and flights on the basis of months and again we can see that the frequency peaks in the months of July and is lowest in the month of February. 

Step 4:
In the research question 2, again using the help of pivot table we can see the seasonality of the revenue and the availability of seats along the course of time. From this chart we can conclude that the seasonality was disturbed due to the covid 19 on the year 2020. 

Step 5:
Now for the next question we have used the forecast function to predict the future trends in the revenues and the availability of seat. The calculations are done by the forecast function in excel. The Lower dotted line signifies the lower confidence level and the upper confidence level is described by the dotted line at the top. Well, the chart of it can be also achieved by the forecast sheet option in excel which clearly shows the table with the calculations. 

Step 6:
Now for the final objective I have used the basic functions such as sumifs, and countifs function to determine the effect of covid for the different aspects and we can also conclude that the international flights getting more affected than the domestic flights which concludes the impact of complete lockdown.
