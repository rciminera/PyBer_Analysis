# PyBer_Analysis
by Bob Ciminera

## Overview of the analysis: 
Pyber is a Python based ride sharing app company.  I conducted an analysis of rider and city data for January through April to understand and present potential opportunities to improve access to ride sharing services and improve affordability for underserved markets.

These markets were grouped into three different types:
Rural, Suburban, and Urban. For each of these types I analyzed number of rides, drivers, total fares, average fare per ride, and average fare per driver.

The tools used for the analysis were Python, Pandas scripts, Jupyter notebook, and Matplotlib.

The PyBer analysis code can be found here: [Pyber_Challenge.ipynb](PyBer_Challenge.ipynb)

## Results: 

Following are the results of the analysis.

In terms of Total Rides, the Urban market had significantly more rides, drivers, and total fares but the average fares per ride and driver were the lowest among the three markets.  See Pyber Summary Dataframe below:

![GitHubLogo](https://github.com/rciminera/PyBer_Analysis/blob/main/Pyber%20Screen%20Shots/Pyber%20Dataframe.png)

The weekly Fare by City type analysis in the chart below shows that the ranking of total fares by city type is consistent Urban, Suburban, and Rura; each maintaining their ranking for the first four months of the year.

The variation in Total Fare is most pronounced in the Urban markets, and the trend line for all city types shows a spike in the third week of February which corresponds to Presidents Day vacation week.


![GitHubLogo](https://github.com/rciminera/PyBer_Analysis/blob/main/Pyber%20Screen%20Shots/Pyber_graph.png)


The file with the line plot can be found here: [Pyber_fare_summary.png](Analysis/PyBer_fare_summary.png)

## Summary: 

Based on the results, following are four business recommendations to the CEO:

1. Introduce a variable pricing scheme in the urban market based on supply and demand.
    
    Ratio of drivers to rides indicates excess capaity and capitalizing on times of peak demand to raise prices can help improve margins and help with driver attrition.

    This will create some profit opportunity during peak times and their is sufficient demand.

2. Experiment with raising fare rates in the Suburban market.

    The number of rides over time is the most consistent so it appears there is a reasonable equilibrium of supply and demand.  
    
    It seems there is some opportunity for modest price increases whcih can be done on a trial basis before full rollout.   

2.  Maintain in the Rural market.

    The average fare per driver vs ride is the highest of all all three markets and the rural demand is consistent.  However, the overall demand is low.  
    
    








