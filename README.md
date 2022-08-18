# Weather Analysis for Surf Industry Business Forecasting
### The investment team for a breakout retailer in the surf industry has requested analysis of weather data to help identify the optimal city and site for a potential new retail store. The investors specifically want analysis run on temperature weather trends for the city of Oahu, Hawaii. There is a strong correlation in the surf industry between annual sales / renvenue from equipment rentals and temperature - the investment team wants to ensure that the weather trends of the city identified for the first potential location would not preclude long term financial viability and hinder aggressive growth plans. 

## Results: 
### The analysis team used weather data gathered from stations around the city of Oahu. From this metadata the team parsed out temperature data for the months of June and December. The investment team will draw conclusions about the financial viability of the new business from the observations below:

![june_temps](https://user-images.githubusercontent.com/107326987/185294880-72ff2bed-891b-4549-8327-3ab1dfd28229.png)
![dec_temps](https://user-images.githubusercontent.com/107326987/185294912-8ff21a3e-2ed2-4a9c-b02c-b72ffa8c40db.png)

- Low Variability in Comparative Temperature Data Spread Between June/December:
  - There is very little deviation across all the temperature data points from June to December. In the above tables we can see that the difference between any single data point is never greater than 10 (omitting the observation count). The standard deviation and average temperature datum across June and Decmeber are close in value which is a good indicator that retail sails in the surf industry will not experience large fluctuations over the course of the year due to fluctuations in annual temperatures.
- December Has a Greater Standard Deviation of Data than June:
  - We can conclude that the temperature is more volatile in December - more prone to relative 'extreme' highs and lows. You can see this expressed in the max temperature observed for December as 83˚ which is only 2˚ cooler than the maximum observed temperature of 85˚ in June. December however has a cooler minimum observed temperature of 56˚ (compared to June's observered low of 64˚) with a total spread of 27˚ between the high and low. The spread of our data points is greater in December, and skewed "cooler". December has more observations at cooler temperatures which drives the median down to 71˚ (compared to 75˚ in June) and the value of the 25% quartile to 69˚. 
- Fewer Observation Points in December:
  - There are fewer observation points collected in the month of December than in June. Conclusions could be more reliably drawn if we had analysis of how much alignment there was in observations drawn from the same stations month to month. There is a critial mass of observation points for each month (an average of 49 data observations per day in December) it is unlikely that the differential in observation counts and station locations is greatly impacting our results, but it is worth noting.
  
# Summary & Recommendations
### The city of Oaho has a fairly consistent and high annual average temperature, expressing low variabilily in seasonal temperature changes. The analysis team determined that Oahu could could be a viable potential site for a retail oriented surf-shop. The analysis team recommends further querying of the data to allow the investment team to make informed decisions about business forecasting.
- Analyze Precipitation Data: 
  - The analysis team recommends overlaying the temperature data with corresponding precipitation data. The temperature data shows low variability in weather changes across the seasons and therefore the investment team could assume consistent high reatil sales. Mapping precipitation data ontop of temperature data could help the analysis team identify potential days or seasons where retail sails would be jeapordized due to inclement weather. Including precipitation data in the weather analysis would help tell a more complete story about how weather trends could impact retail sails. Below is a comparison chart of percipitation data for June and December for inital exploratory analysis.

![june_prcp](https://user-images.githubusercontent.com/107326987/185294933-66212fea-ee50-4a33-9e28-9ca84b7d5d3b.png)
![dec_prcp](https://user-images.githubusercontent.com/107326987/185294947-afabc7a8-916c-4b5e-ba06-02de51684ecd.png)

- Explore Elevation and Location of Data Collection Stations 
  - The analysis team recommends further investigation of the location and relative proximity to Oahu of the observation stations used to gather temperature and precipitation data. The temperature and precipitation statistics might be skewed if stations with high count outputs of datum are all higher in elevation with less relative poximity to the Oahu city center and sea level.



