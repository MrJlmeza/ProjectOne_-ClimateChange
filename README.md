# ProjectOne_-ClimateChange
UPenn Bootcamp
Group 5 - Project 1
May 3, 2021
Brian Havard, Vito Jacono, Angela Leonard, Jorge Meza, Tanmay Patel

Project Objective: 
Study the relationship between the effect of global warming to the earth’s surface temperatures by displaying historical surface temperature data. We hope to gain insights into whether temperatures have risen in a particular area of the world or at scale due to the rise in CO2 emissions.

Research Questions
Question 1
The current growth of global land temperatures - How has surface temperatures increased in the last 100 years by country? 
Question 2
Correlate CO2 emissions by country to surface temperatures - do CO2 emissions increase surface temperatures?

Data References
Berkeley Earth - Surface Temperatures
CO2 Emissions - OurWorldInData
Population - The World Bank
GeoCode - Google Public Data

Data Analysis Process
Data Load
Download data sources 
Load csv into dataframes to be used to transform/cleanse
Data Transformation
Review CSVs and removed unnecessary columns.
Rename columns appropriately
Transform rows and take mean over decades
Merge dataframes to a singular dataframe

Data Analysis & Visualization
Graph appropriate visuals based on countries researched
Analyze trends based on line equations, regressions etc.



Findings

United Kingdom
Land Temperatures increased the steepest amongst all countries reviewed at 1.13 (delta of correlation coefficient between 1800s and 1900s)  

Land Temperatures have been on a steady incline with a correlation coefficient of 0.79 (1900) vs. -0.34 (1800)

CO2 Emissions have been rising in the U.K. with a correlation coefficient of 0.79.


United States
While temperatures were in a decline in the U.S. in 1800s, the turn of the century brought an increase in surface temperatures. 

Just like the U.K., the U.S. saw a decline in surface temperatures from 1930 to 1960 that affected the overall correlation coefficient. Could World War II be a factor based on the increase in production and wartime effects?

CO2 emissions have been steadily rising at a correlation coefficient of almost 1 (0.98).


India
India is one of the few countries we saw that had a steady rise in temperatures in both the 1800s and 1900s. 

The 1900s saw a greater rise in land temperatures

India produced almost 1B Metric Tons of CO2 in 2000


China
Land temperatures remain rather consistent (1800s) - Correlation Coefficient: 0.54 
Steep incline in land temperatures  (1900s) - Correlation Coefficient: 0.9
Land Temperatures in china remain consistent during the 1800s until a steep incline in temperatures in the 1900s - Correlation Coefficient between 1800s and 1900s: 0.83


Brazil
-  Land Temperatures saw almost no increase in the 1800s in Brazil. However, we saw the highest temperature increase out of all countries in the 1900s. 
-  CO2 Emissions have been rising in Brazil with a correlation coefficient of 0.9.


Denmark
Land Temperatures saw a steep decline in the 1800s. In the 1900s, they have been fluctuating (decline from 1930 to 1970, and an increase from 1970 to 2000)

CO2 Emissions rose at a rate of 0.94, however, in comparison to the rest of the world, Denmark still has a relatively low CO2 emission count


CO2 Emissions Analysis
- Both CO2 emissions and temperature have steadily increased since 1900.

- Emissions were 2 million tonnes (metric tons) in 1900 vs. 4 billion tonnes in 2010

Analysis

Final Analysis
CO2 Emissions 
CO2 Emissions have risen across the world since 1900
Of all 5 countries researched, CO2 emissions increased for each country.
Land Temperatures
Correlation 
Future Work
Population vs. CO2 Emissions
Forecasting the rise of surface temperatures - when will the world end :) 
For all countries researched, from 1940 onwards, land temperatures have significantly increased.
Even though we observed slight rises in temperatures in the 1800s, the 1900s saw an exponential growth.
There is a strong correlation between the rise of CO2 emissions and surface land temperatures based on the countries compared.
Other factors can participate in the growth of surface land temperatures as well

Data Limitations
Significant Gaps in Temperature Data
215993 valid measurements in the 1800s
31601 measurements dropped as NaN
High Levels of Uncertainty



Early Data in Particular is Lacking
Only 76 of 243 possible entities have recorded measures in the 1700s
Colonialism
Several of those entities were distinguished as France/France (Europe), ect
Average temperature uncertainties of 4.0 degrees in 1700s, 1.9 in 1800s, .46 in 1900s

