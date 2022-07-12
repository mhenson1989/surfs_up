# Module 9 - Surfs Up Analysis
## **Overview**
The purpose of the Surds Up Analysis is to assess review the weather data and statistics of Oahu in the months of June and December in order to determine the success probability and sustainability of a year-round ice cream shop. Within this analysis, we specifically reviewed temperature data within the two months and the overall statistical summaries of the months. 

## **Results**
**1. On average, the temperature in Oahu in June is only slightly higher than the temperature in Oahu in December**
As seen in the chart below, the average temperature in Oahu in June is 75 degrees (rounded up). This is only 4 degrees higher than the average temperature in Oahu in December, which is nominal in terms of an overall fluctuation in weather. Though we did not run the analysis for the months in between June and December, one could assume that they will, on average, range between 75 and 71 degrees, which could still be acceptable ice cream consuming weather.  

!["June Avg Temp"]()

**2. There is a significant drop in temperature from the beginning of December to the end of December** 
Looking at a snapshot of the December temperature dataframe, you can see that the temperature on December 1st is 76 degrees, which is on par for the average temperatures in June, however, over the course of 30 days, we see a significant temperature drop by 11 degrees on December 31st, which indicates that as the month passes, Oahu begins to get significantly colder. I would also offer the assumption that this trend might continue in January and February and would recommend running an analysis on these months to assess if it is necessary to close for a Winter Break. 

!["December Database"](https://github.com/mhenson1989/surfs_up/blob/main/Resources/Dec_Temp_DF.PNG)

**3. Overall, there is not a significant difference in temperature in Oahu from June to December when looking at the full statistical summary** 
When looking at the summary statistics overall, the differences in average temperature, upper and lower quartile temperatures and max temperatures are nominal. The only significant difference in statistics is the minimum temperature datapoint, where you start to see a trend in December towards lower temperatures. 

## **Summary**

*Final Recommendations*
Overall, we do not find significant variations in the summarized statistics between temperatures in June and December, however, the minimum temperatures in the December database indicate a trend towards colder weather at the end of the year. I would recommend performing additional queries and statistical analysis in January and February, at minimum to assess whether these trends continue, and there is a need close the ice cream shop when the weather is too cold. 

Additionally, I would recommend performing an analysis of the highest temperatures during the year and compare it to overall sales at similar businesses. This might indicate specific times of the year where the shop could extend hours or reduce hours, based on overall sales. As an example, if in July, the temperatures are highest and days are longest, you might see higher overall sales in "daylight hours". This model could help balance other times during the year that yield lower overall sales with operational cost. 

