# PyBer Analysis
## *Analyze Rideshare Data from January to Early May 2019*
### Project Overview: Use Pandas and Matplotlib to asses the number of riders, drivers and fares by type of city, to help improve rider access to rideshares and affordability. 
---
</br>

## Results 
PyBer tasked us with exploring rideshare data from 2019 to address disparities among city types: urban, suburban and rural.
</br>
Expectedly, urban areas produced the most rides, had the most drivers, and grossed the most in sales or total fares out of the three city types.
</br>

<img align="right" src="https://github.com/ajcurtis916/PyBer_analysis/blob/main/resources/df_summary.png" width="600" />

Fare per ride and average fare per driver was lowest in urban areas. Inversely, rural cities had the fewest number of rides, drivers, and sales or total fares, but the highest tickets per ride, and highest average fare per driver.

Suburban cities clocked in at second on all metrics: total rides, drivers and fares, and average fare per ride and fare per driver.  To give a little perspective to these numbers, urban cities had 171% more rides, 187% more drivers, and 161% more in total fares than it's rural counterparts, but 34% less in average fare per ride and 108% less in average fare per driver.

<img align="left" src="https://github.com/ajcurtis916/PyBer_analysis/blob/main/resources/fares_graph.png" width="600" />

Suburban cities had 89% less rides, 132% less drivers, 69% less in total fares, but 23% more in average fare per ride and 82% more in average fare per driver than urban cities.  Suburban cities also 133% more rides, 145% more drivers, 127% more in total fares, but 11% more in average fare per ride and 34% less in average fare per driver than rural cities.
</br>

It should also be noted that there appears to have been a stark downturn in total fares for urban cities for at least one week during April of 2019.
<br>

## Summary
Our analyses shows that number of rides, drivers, and total sum of fares from the more populous city types are the highest, with urban being the most, then suburban, then rural.  Our analyses also shows the more populous a city, the lower the fare per ride and fare per driver, with rural cities bringining in the highest average fare per ride and fare per driver, then suburban cities, then urban.  This is likely due to the short distances between pick-ups and drop-offs, higher demand for rides, and greater saturation of drivers in more populous cities.

Market research is needed to determine whether the cost of rides or lack of available drivers is limiting rideshare usage in the less populated city types.  If it is simply lack of demand, not much can be done.  If the low number of rides is due to high cost or lack of available drivers, it is recommended PyBer offer incentives or bonuses to drivers currently residing or working in cities, to attract more drivers to areas in need.  This may also help with the issue of low fare per ride and fare per driver in the more populous cities.

If some of the drivers pivot their efforts to rural areas, this will in turn increase the drivers who stay in the urban or suburban areas fare per driver. To increase the fare per ride in more populous areas, PyBer could offer discounts for longer rides, such as the rate/mile decreasing as the number of miles increases.  This could concurrently entice riders in rural areas to order more rides.
