# Weather Analysis for Surf Industry Business Forecasting
### The investment team for a breakout retailer in the surf industry has requested analysis of weather data for an identified potential city/site for a retail store. The investors specifically want analysis run on weather trends for temperature for the city of Oahu, Hawaii. There is a strong correlation in the surf industry between annual sales / renvenue from equipment rental and temperature - the investment team wants to ensure that the city identified for the first potential location meets the minimum parameters for average temperature. 

## Results: 
### The analysis team used weather data gathered from stations around the city of Oahu. From this metadata the team parsed out temperature data for the months of June and December. The investment team will draw conclusions about the financial viability of the new business from the results analysis below:
               JUNE             |            DECEMBER
![june_temps](https://user-images.githubusercontent.com/107326987/185020325-4cf6816e-98e8-4e4b-b55f-99233d388bca.png)
![dec_temps](https://user-images.githubusercontent.com/107326987/185020355-8d556c4a-448b-4ff4-80f1-b57a5f6459a7.png)

- Low Variability in Comparative Data Spread:
  - There is very little deviation across all the data points from June to December. In the above tables we can see that the difference between any  single data point is never greater than 10 (omitting the observation count). The standard deviation values and average temperature values across Juen and Decmeber are close in value which is a good indicator that retail sails in the surf industry will not experience large fluctuations over the course of the year due to fluctuations in annual temperatures.
- December Has Greater Standard Deviation of Data than June:
  - We can conclue that the temperature is more volatile in December - more prone to relative 'extreme' highs and lows. You can see this expressed in the max temperature observed for December as 83˚. June (only 2˚ cooler than June's max temperature) but a much cooler minimum observed temperature of 56˚ (compared to June's observered low of 64˚). The spread of our data points is greater in December, and skewed "cooler". December has more observations at cooler temperatures which drives the median down to 71˚ (compared to 75˚ in June) and the value of the 25% quartile to 69˚. 
- Fewer Observation Points in December:
  - There are fewer observation points collected in the month of December. Conclusions could be more reliably drawn if we had analysis of how much alignment there was in observations drawn from the same observation stations. There is a critial mass of observatino poitns for each month (an average of 49 data observations per day in December) it is unlikely that the differential in observation counts is greatly impacting our results, but it is worth noting.
# Summary & Recommendations
### Through analysis it is observed that the city of Oaho has great annual temperature, experiences low variabilily in seasonal temperature changes. The analysis team determined that Oahu could could be a viable potential site option for a retail oriented surf-shop. The analysis team recommends further querying of the data to allow investment team to make informed decisions.
- Analyze Precipitation Data: The analysis team recommends overlaying the temperature data with corresponding percipitation data. Percipitation date could and eliminate otherwise viable day for surfing and cut into profit. Below is a comparison chart of percipitation of June and December compared for inital exploratory analysis.


- Elevation and Location of Data Collection Stations: The analysis team recommends further investigation of the location and relative proximity to Oahu of the observation stations used to gather data. The temperature and precipitation statistics might be skewed if high performing stations are all closer in elevation to nearby mountainous regions with less relative poximity to Oahu city center and shoreline.

disparity
deviation
fluctuation


