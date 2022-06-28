# PyBer_Analysis
Analyzing ride-sharing data (_using Python, Pandas, Matplotlib, and Jupyter Notebook_)

## Overview of PyBer Analysis
I performed an exploratory analysis and produced visualizations that demonstrate the apps performance metrics across different types of cities. 

After presenting my initial report, the company asked that I additionally create a summary DataFrame of the ride-sharing data by city type, and a multiple-line graph that shows the total weekly fares for each city type. The following summarizes all that I've uncovered while analyzing the ride-sharing dataset.

## Resources
- Data Sources: city_data.csv, ride_data.csv
- Python: 3.7.13, Jupyter Notebook

## PyBer Analysis Results
**PyBer ride-sharing data by city type:**

![PyBer_Summary_DF](https://user-images.githubusercontent.com/106599446/176276058-721e6819-f565-47c8-93b5-ef9d110e8af0.png)
- Total rides: 
    - 5.3% of rides (or 125) were in rural cities
    - 26.3% of rides (or 625) were in suburban cities
    - 68.4% of rides (or 1,625) were in urban cities
- Total drivers:
    - 2.6% of drivers (or 78) were in rural cities
    - 16.5% of drivers (or 490) were in suburban cities
    - 80.9% of drivers (or 2,405) were in urban cities
- Total fares: 62.7% of Urban Cities
    - 6.8% of fares (or $4,327.93) was made in rural cities
    - 30.5% of fares (or $19,356.33) was made in suburban cities
    - 62.7% of fares (or $39,854.38) was made in urban cities
- Average fare per ride:
    - $34.62 for rural rides
    - $30.97 for suburban rides
    - $16.57 for urban rides
- Average fare by driver: 
    - $55.49 for rural drivers
    - $39.50 for suburban drivers
    - $16.57 for rural drivers
    
**Total fare by city type:**

![Fare_By_City_Type](https://user-images.githubusercontent.com/106599446/176275725-0db06fb7-5844-4303-b1e2-e081444e1a89.png)
The above chart depicts the total fares for each city type, each point of a line representing the sum of all rides from the preceeding week in that type of city. 
- Rural cities saw a range of $67.65 to $501.24 for week's worth of fares. 
- Suburban cities saw a range of $721.60 to $1,412.74 for a week's worth of fares. 
- Urban cities saw a range of $1661.68 to $2470.93 for a week's worth of fares.

## PyBer Analysis Summary
As discernible in the above ride-sharing data analysis, in aggragate, there were more divers in Urban cities than there were rides. And similarly, there were less drivers than rides in both rural and suburban cities. This data might suggest that the company would benefit from attracting more drivers in rural and suburban cities, whereas it might consider limiting its driver total in various urban cities. It is possible that the number of rides in rural and suburban cities would have been higher, had there been more drivers readily available to accomodate those rides. It is worth noting that this may not be true for all cities within each city type. (It is quite possible that certain cities are skewing the dataset.) Thus, following this analysis, the compnay should review rides and drivers on an individual city by city basis, and determine which cities should have more or perhaps less drivers. 

_Condideration for the number of drivers in cities should be regularly adjusted according to fluctuations in the app's traction / demand from users._
