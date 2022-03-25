# Report for Module-5 Challenge

# 1.	Overview the task.
This task is based on a data from a compay called PyBer which is a python based ridesharing application company. PyBer is interested  in exploring the relationship between city type and number of drivers, number of rides, and total fare. The exercise involves writing a python script in Jupyter note book to generate a data summary of ride sharing the includes total rides, total drivers, total fares, average fare per ride and driver, and total fare by city type. To help understand the relationship better the company wants the results presented in a chart and analyses the results.   
## The purpose of the report is
* To write a python code script in jupyter notebook that create a ride-sharing summary DataFrame , which includes the total rides, total drivers, total fares, average fare per ride and driver, and total fare by city type. 
* To write a python code script in jupyter notebook that create multiline chart of weekly total fare by city type
* Analysis the data summary and chart and provide recommendations
# 2.	Results
 ## 2.1 2.A ride-sharing summary
Table-1 below shows the ride-sharing summary DataFrame. As shown in the table, interns of the total rides, total number of drivers and total fare, we can observe that these total values increase with level of urbanization and this is expected. More movement is expected in urban areas than in rural areas. However, in terms of the average fare per ride, we can observe that fares per ride are expensive in rural city types($34.62 in rural Vs. $24.53 in urban) and fares per ride is also highest in rural city type($55.49 in rural city type Vs. $16.57 urban city type).
### Table-1: Ride sharing summary by city type 

![Table-1](https://github.com/nebil2016/PyBer_Analysis/blob/main/analysis/Table-1-Ride-sharing%20summary.png)

## 2.2.  Total fares for each city type
The weekly fare trends shown in the figure shows almost similar trend for the three types of cites. For the urban and suburban city type, there is an increasing trend in fares between January and 3rd week of February and decreasing trend in the four weeks of March. On the other hand, the fares in rural city type the fares substantially decreases after April while there is an increasing trend on the same time frame for the urban and suburban city type. 
### Fig-1: Total Fare by city type

![fig-1](https://github.com/nebil2016/PyBer_Analysis/blob/main/analysis/Fig_challenge.png)

# 3. Summary
Total fares, total rides and total number of drivers are highest in urban areas and lowest in rural city types. However, the fare per ride and per driver is highest in rural areas than in urban areas. This is expected because there are fewer rides in rural areas and it will be difficult to make profits with fewer rides. Further, the fares are also lowest in the four weeks march for all city types and in rural the areas fares substantially decline after the first week of April. The company needs to consider different prices in March for all city types to encourage more ride and also in April for the rural city type.
