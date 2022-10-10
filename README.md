# PyBer_Analysis

##Overview of Analysis

After receiving ride data from various cities with total rides, total drivers, total fares, average fare per ride and average fare per driver as the variables we were able to conclude some key trends in our data. Our data was compiled and split from three main categories: urban, suburban, and rural. 

##Results

After creating DataFrames and merging them together we were able to learn that the highest volume of both rides and drivers belong to the urban category. However, in rural areas we see that category rank highest in both average fare per ride and average fare per driver. The suburban category floats in between rural and urban in all our categories. 

![PyBer_data](https://user-images.githubusercontent.com/80132877/194795360-70d545ca-3e6c-4200-b89c-4d7670fafc2e.png)


Digging a little deeper we see that there are more total drivers than total rides in the urban category. For rural and suburban categories, we can see there are more total rides than total drivers and this is critical because of the correlation to the average fare per driver and ride being higher on average than fares from urban passengers and drivers.

![PyBer_graph](https://user-images.githubusercontent.com/80132877/194795354-c5a52b97-36a0-49da-812a-14bbda9f6fe1.png)


When we consider real world application of our data, we can see that drivers in urban areas are competing for fewer rides than passengers have options which affects the average fare per driver. Couple that with the fact that urban rides are on average shorter in distance which affects the average fare per ride, we can see how the urban area is affected the most.

Contrast to the urban area drivers plight, suburban and rural areas share the same luxuries regarding having more passengers than competition of drivers as well as the expected rate and mileage increases that apply to suburban and rural areas respectively.  


##Summary

Our summary is a little short-sided because our data in essence is incomplete. We assume that mileage is a correlation to our existing data, however it is paramount to collect data regarding mileage if we want a better understanding of how we can find more optimal solutions. We also are dealing with a small sample size regarding the time of data collected. We would need at least a years’ worth of data collected to have a better chance at creating optimal solutions. 

Three recommendations with our current data for PyBers business model would be creating incentives for urban drivers to accept rides in suburban and rural areas, creating a pool and divide system where the overall revenue is collected and disbursed evenly and or increase the cost per mile in urban area rides while charging a lower rate per mile in suburban and rural areas. 
