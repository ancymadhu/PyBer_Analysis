# PyBer_Analysis

## Project Overview

Use data visualization techniques to give insight into the data from a ride sharing company called PyBer.

## Resources

* Data Source: city_data.csv, ride_data.csv
* Software: Python 3.7.7, Anaconda Navigator 1.9.12, Jupyter Notebook 6.0.3

## Challenge Overview

You’ve been asked by your CEO to create an overall snapshot of the ride-sharing data. She would like to see a summary table of key metrics of the ride-sharing data by city type, and a multiple-line graph that shows the average fare for each week by each city type.

## Results

### DataFrame Summary

The dataframe summary for ridesharing tells us a number of things.

![1](https://user-images.githubusercontent.com/73450637/99102752-87548d00-25ac-11eb-983e-8d060b77e25e.png)

> There are significantly more rides in Urban cities than Suburban or Rural. 
> The average fare per ride and average fare per driver are actally most expensive in the rural areas and cheaper in the Urban cities.
> This tells us that as a ride share service has more drivers available, the ride expenses or fares become cheaper on average.

### Multiline Graph Summary

The multiline graph gives a nice visualiation of the ride share data. 

![1](https://user-images.githubusercontent.com/73450637/99103166-28434800-25ad-11eb-8f6c-38b477b3e52a.png)

> It clearly shows that all city types (Urban, Suburban, and Rural) are fairly consistent in total fares over time.
> There are a few spikes in the data here and there but overall quite consistent. 
> It also shows that the majority of the money comes from Urban cities followed by Suburban and then Rural.

## Summary

The recommendations to the CEO upon reviewing the analysis are as follows:

1. A very subsequent fare rise can be seen from February end till March (in all the three areas) which appears to be worth exploring.
2. If we compare the number of drivers to total rides ratio, the number of drivers in urban are unusually high compared to the other two areas even though avaerage fare per driver is very low.
3. Having proper driver to ride ration according to the area would be worth saving all other resources.
