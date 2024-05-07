# NYPD Arrests Analysis 2006-2023

Drilled down into NYC arrest data to identify yearly patterns and trends of arrests effected by the NYPD from 2006-2023.

The data revealed a concerning trend of higher arrests of "Black Males" each year from 2006-2023. The data also revealed that the borough where higher arrests were made each year is Brooklyn, except in 2015 when Manhattan had the highest arrests.
Also, people in the Age group of 25-44 have been arrested the most each year, and the Offense Category with the Highest Arrest Count each year is Misdemeanor.

The datasets used in this analysis were sourced from the NYC OpenData Repository. At the time of extraction, the data available was the Historic Arrest data from 2006-2022 in a separate file and the Arrest data for 2023 in a separate file. I resorted to using the Pandas library to merge the data, performed some basic data cleaning and transformation, and saved the cleaned data.
The data transformation process involved steps like removing null values, changing data types, and filtering out invalid values from some columns (Age Group, Level of Offense). 

The cleaned dataset has a total of 5,664,571 records.

I then imported the data into Tableau to perform my analysis and visualization and presented the summary on a dashboard.

Link to Tableau dashboard: https://lnkd.in/euw6Wghm
