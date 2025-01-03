# India-Climate-Analytics-Dashboard
A Power BI dashboard that visualises and analyses India's climate data based on certain factors.

### Introduction
With climate change being a pressing issue, this comprehensive climate analysis dashboard provides detailed insights into India's weather patterns, focusing on temperature, rainfall and other atmospheric conditions from 1950-2024. The visualisations help us analyse national trends, with a special focus on Kerala's climate patterns.

### Contents:
- [Introduction](#introduction)
- [Objectives](#objectives)
- [National Temperature Trends](#national-temperature-trends)
- [National Rainfall Trends](#national-rainfall-trends)
- [Kerala Temperature Analysis](#kerala-temperature-analysis)
- [Kerala Rainfall Analysis](#kerala-rainfall-analysis)
- [Kerala Monsoon Period Analysis](#kerala-monsoon-period-analysis)
- [Humidity and Dew Point Analysis](#humidity-and-dew-point-analysis)
- [Atmospheric Pressure Analysis](#atmospheric-pressure-analysis)
- [Temperature and Rainfall Projections](#temperature-and-rainfall-projections)
- [Data Preprocessing](#data-preprocessing)
- [Tools Used](#tools-used)
- [Conclusion](#conclusion)

### Objectives
* To analyze temperature trends and variations across different regions of India.
* To track rainfall patterns and monsoon behavior, particularly in Kerala.
* To examine the relationship between various climate parameters (temperature, rainfall, humidity, and pressure).
* To provide future climate projections until 2040.

### National Temperature Trends
![National Temperature Trends Dashboard](https://github.com/AleenaVals/India-Climate-Analytics-Dashboard/blob/032edc2d7532aa9bca69f77d7775d6798831bf00/national_temp_trends.png)

#### Key Insights
* The national average temperature shows a clear upward trend from 1960-2024, indicating significant warming across the country.
* The critical temperature threshold of 23°C has been breached multiple times after 2000, suggesting increased frequency of heat events.
* The highest recorded peak temperature reached an average of 23.11°C, creating a significant peak in the temperature trend graph.
* The geographic map shows how the temperature varies across the country with light blue in the northern regions showing low temperatures, variations of red showing high temperature and yellow along the coastal regions showing moderate temperature. (Kerala has a deep red color since there are more points in Kerala and we needed to do a detailed analysis of the state)
* Regional temperature comparison reveals distinctive patterns. Northern region consistently shows lowest temperatures throughout the year while the Eastern region maintains relatively lower temperatures due to year-round rainfall. Southern and Western regions demonstrate highest average temperatures consistently over the years
* Monthly temperature extremes analysis shows how the summer months( March-June) have the maximum temperature variations over the year. For the winter months, the temperatures can go very negative in the country leading to an increased gap between the maximum nd minimum values.
* The slicers in the dashboard help in more detailed data filtration based on the requirements.

### National Rainfall Trends
![National Rainfall Trends Dashboard](https://github.com/AleenaVals/India-Climate-Analytics-Dashboard/blob/032edc2d7532aa9bca69f77d7775d6798831bf00/national_rainfall_trends.png)

#### Key Insights
* Annual rainfall data indicates a significant overall declining trend since 1960.
* Recent years show increasingly unpredictable distribution of rainfall across seasons with the rainfall events occurring over shorter periods but with higher intensity.
* The stacked bar chart reveals distinct regional patterns. Eastern region dominates rainfall in pre-monsoon months and Southern region shows significant increase in post-monsoon months. The monsoon months see an even distribution of rainfall all throughout the nation.
* North-Eastern India receives highest rainfall across all seasons as per the geographic map(The bubble size is directly proportional to the amount of rainfall)
* Central India is experiencing a concerning decreasing trend in annual rainfall.
* Monthly rainfall patterns reveal that approximately 70% of the annual rainfall occurs during the monsoon months.
* Pre-monsoon rainfall shows a declining trend over recent decades while the post monsoon rainfall has become less predictable. There has been a clear shift in traditional seasonal rainfall patterns.

### Kerala Temperature Analysis
![Kerala Temperature Analysis Dashboard](https://github.com/AleenaVals/India-Climate-Analytics-Dashboard/blob/032edc2d7532aa9bca69f77d7775d6798831bf00/kerala_temp_analysis.png)

#### Key Insights
* The state of Kerala has experienced a marked increase in average temperature since 1990, showing a clear warming trend.
* Temperature trend analysis shows that the average baseline temperature is being exceeded more frequently in recent years.
* Temperature spikes have become more common after 2000, indicating increased heat stress.
* Winter cooling periods have reduced in duration and intensity.
* Monthly temperature chart shows that April and May consistently record the highest temperatures throughout the year. Summer-like conditions are extending beyond traditional summer months.
* Comparative analysis of recent years shows significant changes with the year 2019 recording the highest average temperatures in the studied period.
* The frequency of heat events have increased throughout the year.
* Monsoon months are showing reduced cooling effects compared to historical patterns.

### Kerala Rainfall Analysis
![Kerala Rainfall Analysis Dashboard](https://github.com/AleenaVals/India-Climate-Analytics-Dashboard/blob/763b32d71dd54e1bc82b5da2dd8ddb23e5dc5af2/kerala_rainfall_analysis.png)

#### Key Insights
* Kerala's rainfall patterns show high variability compared to historical norms.
* Extreme rainfall events analysis reveals critical patterns with high intensity rainfall events occurring more frequently than in previous decades.The 2018 floods were characterized by unprecedented rainfall intensity.
* Dry spells between heavy rainfall periods have become more pronounced.
* Monthly rainfall distribution shows that peak rainfall periods are shifting from their traditional patterns.
* Rainfall is becoming more concentrated in fewer days throughout the year and monsoon rainfall variance has increased substantially in recent years.
* The flood analysis of Kerala reveals that strong correlations exist between atmospheric pressure patterns and extreme rainfall events.
* The changing rainfall distribution patterns impact flood frequency and intensity.

### Kerala Monsoon Period Analysis (2017-2019)
![Kerala 2018 Rainfall Analysis Dashboard](https://github.com/AleenaVals/India-Climate-Analytics-Dashboard/blob/c05efa611d71c5f20a796186df08e7fcfd6d0ab0/kerala_floods_2018.png)

#### Key Insights
* Monthly monsoon patterns across 2017-2019 show significant variations.
* June: 2018 experienced an extreme rainfall spike while 2017 maintained relatively lower levels
* July: Rainfall distribution was more uniform across three years, with 2018 showing slightly elevated levels mid-month.
* August: 2018 witnessed two significant spikes exceeding the critical threshold of 130mm, while other years showed relatively normal patterns.
* September: Began with an extreme rainfall event in 2018 as compared to other years.
* The 2018 flood analysis reveals critical patterns. Multiple instances of rainfall exceeding the threshold along with concentrated periods of extreme high-intensity rainfall shows how it aggravated the floods of 2018. The dry periods were very limited between these days as well.

### Humidity and Dew Point Analysis
![Humidity and Dew Point Analysis Dashboard](https://github.com/AleenaVals/India-Climate-Analytics-Dashboard/blob/ce8827c1b8d834ba9e22968e0218686e4fe8c2e8/humidity_dewpoint_analysis.png)

#### Key Insights
* Different regions of India show distinct variations in humidity patterns throughout the year.
* Strong seasonal correlations have been identified between temperature and humidity levels.
* Temperature peaks during April-May while Dew point peaks during July-September. 
* Largest gap between temperature and dew point occurs in summer months. Closest convergence happens in monsoon months.
* The dew point and humidity relationship chart shows that the highest humidity levels are recorded during the monsoon months while the lowest during the winter months.
* The matrix showing monthly dew point patterns reveals the highest and lowest values based on the intensty of colors. The darker the color, higher the dew point value.
* Further filtration can be done by the time hierarchy slicer that filters according to years, quarters, months and days.

### Atmospheric Pressure Analysis
![Atmospheric Pressure Analysis Dashboard](https://github.com/AleenaVals/India-Climate-Analytics-Dashboard/blob/7fe765d1df7a917f507ee67dd16e24c08d6e1956/atm_pressure_analysis.png)

#### Key Insights
* Atmospheric Pressure shows clear seasonal pattern with highest pressure in winter months.
* The green shaded area in the area chart shows the typical pressure variation range.
* Northern region consistently shows highest pressure levels as expected.
* Southern region demonstrates relatively lower pressure values and the coastal regions have moderate values for high pressure. During monsoon months the pressure converges for all regions.
* To analyse how the pressure impacted Kerala during floods, a monsoon period analysis line chart was created. And 2018 flood period showed distinctive pressure pattern.
*  Highest rainfall occurs during low pressure periods,hence the low pressure values in the peak rainfall months.
*  Seasonal pressure patterns show changes from historical norms.
*  Region wise atmospheric pressure analysis shows an entirely different curve and that can be analysed with the help of year and region filters.

### Temperature and Rainfall Projections
![Temperature and Rainfall Projections](https://github.com/AleenaVals/India-Climate-Analytics-Dashboard/blob/8126a35c51e0c7f457abf7adb0f5d9177db4e6ce/projections.png)

#### Key Insights
* Temperature and rainfall projections through 2040 indicate significant changes.
* A continued warming trend is expected across all regions and critical temperature threshold breaches are projected to become more frequent.
* Traditional seasonal rainfall patterns are likely to experience shifts with the annual rainfall decreasing and extreme rainfall events increasing.

### Data Preprocessing
The dataset was checked for quality and consistency of the data. Several calculated columns were created using DAX to handle seasonal variations, including the custom aggregations across regions.

### Tools Used
* Visualisation Tool : Power BI Desktop
* Data Visualization Techniques: Line Charts, Geographic Maps, Bar Charts, Combo Charts, Area Charts, Small Multiple Line Charts, Heat Maps, Slicers
* Dataset: https://open-meteo.com

### Conclusion
This comprehensive climate analysis dashboard effectively visualizes India's changing weather patterns from 1950 to 2024, with particular emphasis on Kerala's climate variations.The analysis reveals clear evidence of increasing temperatures across regions (especially post-2000), shifting rainfall patterns with more extreme events, and significant climate variations in Kerala, highlighted by the 2018 floods. Dashboards like this can serve as a powerful tool for climate change monitoring, disaster preparedness planning, and policy making, making it valuable for researchers and decision-makers across various sectors.

Have thoughts on enhancing this dashboard? I welcome your feedback and ideas for making it even more insightful.
[LinkedIn | Aleena Vals](https://www.linkedin.com/in/aleenavals) 





