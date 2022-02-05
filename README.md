# Module 5 | Assignment - PyBer

# Overview of the analysis: 
We are going to analyse ride share data based on type of cities: Urban, Suburban and Rural.

## Results: 
Using images from the summary DataFrame and multiple-line chart, describe the differences in ride-sharing data among the different city types.
There is a description of the differences in ride-sharing data among the different city types. Ride-sharing data include the total rides, total drivers, total fares, average fare per ride and driver, and total fare by city type. (7 pt)
After merging and summarizing the data using groupby, we find out that:
-   Rural cities have lowest and Urban cities have highest number of drivers and number of rides
-   Rural areas also have the highest average fare, either by ride or by driver. 
-   However, Revenue (total fare amount) is lowest in rural cities and while it is hishest in urban cities . 
-   One interesting find is the average fare per driver is really low in urban cities.

## Summary: 
Based on the results, provide three business recommendations to the CEO for addressing any disparities among the city types.
There is a statement summarizing three business recommendations to the CEO for addressing any disparities among the city types. (4 pt)

Here are our three business recommendations:
1. There are lot more drivers in urban areas as compared to other two. Data shows that there is actually shortage of drives in rural areas by 2:1. It will help if the drivers are **moved** to Rural and Suburban cities from Urban cities. 
2. Gap between average fare per driver is significantly higher than average fare per ride between Urban and Rural cities. This stems from lack of drivers in rural areas. Company can benefit from providing discounts while maintaining driver compensation in rural areas which may increase total rides and attract more drivers.
3. All three city types show consistent variations in fare amount except during the start of summer season in suburban areas. It may make sense to expand services during summer in suburban areas.


## Challenges encountered:
- It would be helpful if the data included miles driven or time taken during each ride.
- More statistics like car maintenance (including gas) per mile or per minute of ride would be helpful in understanding costs incurred during each ride. These numbers will help us get to a profit and loss ratio for each driver. 

Jupyter notebook file is saved at: [Jupyter Notebook](PyBer_Challenge.ipynb)
