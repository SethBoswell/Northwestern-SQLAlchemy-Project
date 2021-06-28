# surfs_up
SQLite and SQLAlchemy Project Folder
## Overview of Project

### Purpose
The purpose of this project folder is to provide an analysis of weather data for the island of Oahu to determine if the weather is suitable for opening a surf shop. The Challenge Assignment utilizes only temperature data from the months of June and December to determine if the weather is temperate all year round. 

### Method
In this project folder, I filter an SQLite database use SQLAlchemy to only include temperatures from these months. I then convert the query results into a list and a dataframe and then calculate summary statistics to provide an overview of the temperature of Olahu during these two months over the course of several years of data.

## Results
The summary statistics for the month of June are below:

![June Summary Statistics](https://github.com/SethBoswell/surfs_up/blob/main/Resources/December%20Summary%20Statistics.png)

And for December:

![December Summary Statistics](https://github.com/SethBoswell/surfs_up/blob/main/Resources/December%20Summary%20Statistics.png)

Three key points from these deliverables are:
- In June, the mean temperature is higher and the standard deviation is lower compared to December, indicating that the temperature is generally higher and there's lot variation across the months. 
- The min, max, and percentiles all have higher temperatures for June than December, also reinforcing the notion that June will have better temperatures for surfing.
- However, even in December, the mean/median temperature is around 71 degrees and the lowest temperature is 56, implying that there may be some days where it's too chilly to surf, but that the store can generally be open year round.

## Summary
Based on these results, I would say that the surf shop would be able to be open all year. In June, there is strong summer temperature and little variation, implying that most days will be surf weather. In December, although this is less true, the climate is tropical enough to support surfing even in these months. One additional query I would run would be to look at precipation levels for these two months. Is there more precipitation in December compared to June? This also might imply that it rains more in December and it may not be as ideal as June for surfing. Another interesting query would be to look at wind speed data and compare that across months. Does the island of Oahu have enough wind to be conducive for surfing? How high do the waves typically get with these levels of wind? This would also be pertinent information before deciding to open a surf shop on this island. 
  
