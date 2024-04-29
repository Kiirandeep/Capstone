# Capstone
Unemployment Trends in USA


Table of Contents:


•	Tableau Dasboard
•	Motivation
•	Data Questions
•	Data Cleaning
•	Challenges
•	Technologies Used
•	Sources
•	Conclusion

Tableau:

https://public.tableau.com/views/Capstone_17144045878100/TableauPublic?:language=en-US&publish=yes&:sid=&:display_count=n&:origin=viz_share_link 

Motivation:

Despite having the world’s highest GDP, the US has experienced fluctuations in employment from time to time. This sparked my interest in examining the narrative surrounding unemployment in America and its impact. For analysis I decided to look at unemployment and factors impacting it in seven US States as examples.


Data Questions:

1.	Unemployment trends globally in comparison to USA (OEDC countries).

2.	Unemployment trends in US States: Alaska, California, Hawaii, New York, Tennessee, Texas, Washington, covering the period from 2010 – 2023. 

3.	Impact on unemployment during the COVID-19 pandemic and a year after, particularly in California and Hawaii.

4.	Look into factors like homeownership, education, median income for the sample States.

5.	Is there any correlation between Unemployment, Homeownership, Education (college degree and above) and median household income in the states?



Data Cleaning:


1.	The dataset for unemployment was available from 1976 to 2023, whereas datasets for other variables were available for different time periods. Both the datasets were trimmed to match the time period. 

2.	Also, some of the columns needed changing of data types in order to merge the data sets.

3.	Case of the columns was changed using the string functions to normalize the data in both the data sets.


Challenges:

Unemployment Dataset:

The dataset for unemployment was available from 1976 to 2023 in separate files for each state. Also the description for the series in the unemployment datasets were in different files. Multiple files(around 18 tab separated files) were merged together to generate the unemployment dataframe.

Degrees, Homeownership, Median Income Dataset:

Data was available in a single file per variable for a state. A total of 19 files were merged to generate this dataset. 



Technologies Used:

Python/Pandas: for exploration, normalizing and aggregation of dataset.
Tableau: for dashboards and presentation 
PowerPoint: Introduction to the project 



Sources: 

1.	https://www.oecd-ilibrary.org/ 
2.	https://catalog.data.gov/dataset/local-area-unemployment-statistics-47d02
3.	https://www.bls.gov/lau/
4.	https://fred.stlouisfed.org 
5.	https://fred.stlouisfed.org/categories/27283
6.	https://fred.stlouisfed.org/categories/27286
7.	https://fred.stlouisfed.org/categories/27293
8.	https://fred.stlouisfed.org/categories/27314 
9.	https://fred.stlouisfed.org/categories/193 
10.	https://fred.stlouisfed.org/categories/27326 
11.	https://fred.stlouisfed.org/categories/27331 




Conclusion:

Over the past decades, the US has experienced significant fluctuations in unemployment rates. But in recent years all the States we looked into have managed to maintain low unemployment figures. According to this dataset, there is no correlation between Homeownership, Education, Median Income and Unemployment. However, the places that have higher number of degree holders and higher median income they tend to have lower unemployment rates.