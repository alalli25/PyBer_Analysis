# PyBer Analysis
Using Python, Pandas & Matplotlib to analyze and visualize ride-share data

## Overview of PyBer Data Analysis
The purpose of this project was to use python, and the pandas and matplotlib libraries, to clean, manipulate, organize, and graphically visualize PyBer historic ride-share data by type of city for my boss, V. Isualize. I am new to this job as a data analyst, and V. Isualize has a background in data analytics. She is looking for me, and a colleague Omar, to create visualizations of ride-share data for PyBer to help improve access to ride-sharing services and determine affordability for underserved neighborhoods. After we completed our initial analysis and presented our results, we have been asked to create a summary DataFrame of the ride-sharing data by city type and a multiple-line graph that shows the weekly fares for each city type. 

## PyBer Results & Summary
### Analysis: Differences between city type
After consolidating the detail by city type into a single DataFrame, we can see that most data points differ between city type. After visualizing the total fare by city type data, we can see the fare vs weekly trend lines are relatively similar, but the fare value by city type differs greatly.

***PyBer City Type Summary***

![](/Resources/Screenshots/PyBer_Summary.png)

***PyBer City Type Summary***
![](/analysis/PyBer_fare_summary.png)

- Urban cities were the most profitable ride-sharing geography, accounting for roughly $40K, or 62.7%, of total revenue. This is not surprising, as the urban city type also tallies 68.4% of the total rides and 80.1% of the total drivers. Total Fare ($) per week has increased roughly $400 per week over a four month period. That being said, there was a lot of volatility starting in late February and continuing through April. This weekly volatility is unique to urban cities.

- Suburban cities were steadily in between urban and rural cities for all metrics tracked. With 26.3% of the total rides, suburban cities achieved a $30.97 fare per ride average. Suburban cities experienced an increase of total fair in the second to last week of February, followed by a steep decline through the beginning of March. Suburban cities are the only city type experiencing an increase of total fare heading into May.

- Rural cities notched the highest average fare per driver, despite having the lowest total rides and total drivers. The average fare per driver in the rural cities is about $16 and $39 more per ride than the urban and suburban cities, respectively. Over a four month time period, rural cities did not significantly increase total fare per week. 

### Business Recommendations
- Continue to invest in infrastructure in urban geographies. Urban cities are clearly the most profitable city type. This is mostly due to the density of both riders and drivers. That being said, I would like to understand why there was so much volatility between late February through early April. Were people traveling less due to inclement weather? Was there a greater macro-economic issue? Were stay at home orders in place, then lifted due to a global pandemic? Gathering more data-points is critical to determining this outcome.
- Continue to invest in suburban cities. Looking at the suburban trend line on the Total Fare by City Type chart, you can see there is a steady incline of total fares over time beginning in early April. 
- Incentivize rural riders to take more trips. The average fare per ride for rural city types is greater than both suburban and urban. This is most likely due to the increased distance in rural areas between starting point and destination. I would look for ways to incentivize or entice more riders to use PyBer ride-share in rural areas to capitalize on the increased average fare per ride. 
