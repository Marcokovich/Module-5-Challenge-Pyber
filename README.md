# Pyber
## 1. Project Overview
### Background
We've been tasked by Visualize to use Python and Pandas to create a summary data frame using the data from their ride sharing app. The data is broken down by the different variables such as the date, time, city, type of city, and fare. We are to process and make a summary data frame of the data then make a multiple-line graph.
### Purpose
This code is to read a .csv file into a data frame, make a summary data frame by altering the original and the derivatives thereof. We group up the different types of cities to create a summary data frame. The next step is to make a subset of the first third of the year broken into intervals of weeks. Then tally up the total fares collected each week per each type of city. Finally, we make a multiple-line graph to map the weekly sum of the fares, broken up by the type of city.
## 2. Results
### Summary Data Frame:

![image](https://user-images.githubusercontent.com/71575748/151721417-c81935c8-42b5-4e1d-80ec-5cd922620513.png)

### Line Plot Graph:

![image](https://user-images.githubusercontent.com/71575748/151721513-3ccfdb7b-454f-4dcf-9123-17f8754b253b.png)

### In the Urban Types:
- Urban types have the most number of total fares, rides and drivers. This makes sense due to the high population and population density would make a high quantity demanded.
- They also have the lowest average fare per ride, and lowest fare per driver.
- The graph corresponds with this data as the weekly sums are still totals and also have the maximum.
### In the Suburb Types:
- Suburban types have the middle of every metric:
  - total fares
  - rides
  - drivers
  - average fare per ride
  - average fare per driver
- This type makes sense as the population of suburbs is between that of Urban and Rural areas, leading to a middling quantity demanded.
- In the graph, the suburban line is always between the rural and the urban line.
### In the Rural Types:
- Rural types have the lowest total fares, rides, and drivers. This is the opposite of urban types, which matches with the lower population density having a lower quantity demanded
- However, they have the highest average fare per ride, and highest fare per driver.
- The graph shows the Rural line at the bottom of the list
## 3. Summary
### Recommendations:
- For Rural areas, taking advantage of the higher fares by increasing demand of rides can greatly increase the total fares brought in from rural areas. Perhaps decreasing the price can be less elastic and lead to much higher totals.
- For Suburban areas, depending on the elasticity of rides, if increaseing or decreasing fare can lead to an increase in total. Its difficult to make a recommendation as suburbs lie in between both rural and urban in terms of density and total fares.
- For Urban areas, taking advantage of the higher demand, increasing the fares could possibly increase totals from these areas, but would definatly increase the averages. This of course depends on the elasticity of the demand for the ride sharing service.
