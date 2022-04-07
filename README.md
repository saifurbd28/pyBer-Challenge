# pyBer-Challenge

# Overview of the analysis:
These analyses and data visualizations on the ride-sharing have been prepared by merging of two datasets using pandas and matplotlib libraries on jupyter notebook. The objective was to compare the quantity and fares of rides in every city type (i.e., urban, suburban, and rural); create clear visualization, and provide a recommendation to the CEO for addressing any disparities among the city types.

# Results
Here, I merged datasets using left join based on the city column and got one dataset with all available data. First of all, I created a summary data frame by city type. It has revealed the first insight - there are few drivers and rides in rural cities with higher average fares compared to urban cities:
•	There are 13 times more rides in urban cities compared to rural cities (1,625 vs 125 rides)
•	The average fare per ride is 1.4 times less and the average fare per driver is 3.4 times less in urban cities compare to rural cities ($24.53 vs $34.62 and $16.57 vs $55.49)
•	The total fares in urban cities are 9 times higher than in rural cities and 2 times higher than in suburban cities. ($39,854.38 vs $4,327.93) 


![image](https://user-images.githubusercontent.com/100442163/162205655-6c19155c-be45-4f85-bf82-ec7baf3493d3.png)

en I created a multiple-line plot that shows the total weekly fares for each type of city. The yellow line for urban cities is higher than the red and blue lines for suburban and rural cities, respectively. That means the ride-sharing company has more total fares and revenue in urban cities rather than in suburban and rural cities. 

![image](https://user-images.githubusercontent.com/100442163/162205768-3951b523-d134-4b51-8e63-54234ef56df2.png)

# Summary
The results can be summarized as: City rides are in demand based on the number of rides. However, there is a challenge. If we calculate the number of rides per driver in the city, it is less than one. It means some drivers do not get a chance to provide a ride. As such, the number of drivers in the city should be reduced to make a balanced market. It will decrease the overhead cost and increase the profit. 
