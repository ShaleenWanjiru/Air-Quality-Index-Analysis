# Air-Quality-Index-Analysis-using-Python
Air quality index (AQI) analysis involves monitoring and analyzing air quality in a specific location. It aims to provide a numerical value representative of overall air quality, essential for public health and environmental management.

According to World Health Organization (WHO) air pollutants are as followsPollutants
## 1. Particulate matter (PM)
PM is a common proxy indicator for air pollution. There is strong evidence for the negative health impacts associated with exposure to this pollutant. The major components of PM are sulfates, nitrates, ammonia, sodium chloride, black carbon, mineral dust and water.

## 2. Carbon monoxide (CO)
Carbon monoxide is a colourless, odourless and tasteless toxic gas produced by the incomplete combustion of carbonaceous fuels such as wood, petrol, charcoal, natural gas and kerosene.

## 3.Ozone (O3)
Ozone at ground level – not to be confused with the ozone layer in the upper atmosphere – is one of the major constituents of photochemical smog and it is formed through the reaction with gases in the presence of sunlight.

## 4. Nitrogen dioxide (NO2)
NO2 is a gas that is commonly released from the combustion of fuels in the transportation and industrial sectors.

# Below are the steps that I followed  for the task of Air Quality Index Analysis:

1. Gather air quality data from various sources, such as government monitoring stations, sensors, or satellite imagery.
2. Clean and preprocess the collected data.
3. Calculate the Air Quality Index using standardized formulas and guidelines provided by environmental agencies.
4. Create visualizations, such as line charts or heatmaps, to represent the AQI over time or across geographical regions.
5. Compare the AQI metrics of the location with the recommended air quality metrics.

# Calculating Air Quality Index
# Analyzing AQI of Delhi
Now, let’s have a look at the AQI of Delhi in January: using a bar chart.
![Analyzing AQI of Delhi](https://github.com/user-attachments/assets/eef41eaa-d26a-4488-9725-fa24ae73e2b8)

# The Air quality distribution overtime illustrated with a Histogram
![AQI category distribution overtime](https://github.com/user-attachments/assets/7acb1b07-03ab-49bf-ad3f-c60ceefb7397)

# To understand the distribution of each pollutant in the AQI according to WHO we use a Pie Chart to visualize the representation.
![Distribution of pollutants in the air quality of Delhi](https://github.com/user-attachments/assets/d3b57906-3791-49f7-af97-df74ac5bee19)

# Correlation Between Pollutants
The correlation matrix displayed here represents the correlation coefficients between different air pollutants in the dataset. Correlation coefficients measure the strength and direction of the linear relationship between two variables, with values ranging from -1 to 1. Overall, the positive correlations among CO, NO, NO2, SO2, PM2.5, PM10, and NH3 suggest that they may share common sources or have similar pollution patterns, while O3 exhibits an inverse relationship with the other pollutants, which may be due to its role as both a pollutant and a natural atmospheric oxidant.
![Correlation Between Pollutants](https://github.com/user-attachments/assets/2bb963ed-648f-4754-ac2e-9f7506b6f443)

# Average AQI by Day of the Week
It shows that the air quality in Delhi is worse on Wednesdays and Thursdays.

![Average AQI by day of the week in Delhi](https://github.com/user-attachments/assets/4cb16c63-49c6-4b69-b647-bf8cf5897de8)



