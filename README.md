# surfs_up-1


# Surfs_up
Precipitation and Weather Station analysis using SQLite and SQLAlchemy. Climate App building using Flask. Other tools include Python and Jupyter Notebooks.

## Overview of Surfs Up Analysis

The purpose of this analysis is to review a dataset pertaining to weather conditions that has been stored in a [SQLite database](https://github.com/amylio/Surfs_up/blob/main/MOD9_Challenge_Submission/hawaii.sqlite) to provide information that will convince an investor that opening up a **Surf n' Shake** shop in Oahu, Hawaii is a good business idea. The idea is that the shop will sell surf boards and ice cream throughout the year, but the investor is hesitant because he invested in a similar business that failed due to the weather conditions. In order to get this investor on board, we need to provide statistical analytics specifically on the weather conditions in Oahu that will convince him that this will be a successful business venture.

In order to explore the data in the `SQLite` database, we used `SQLAlchemy` to connect and generate queries to pull the necessary information needed for our analysis. Throughout this module, we used [Jupiter notebook](https://github.com/amylio/Surfs_up/blob/main/climate_analysis.ipynb) to import dependencies and create the commands to pull the data from the `SQLite` database. Some of the features/functions that we learned in this module included:

**SQLAlchemy**
* `ORM` (Object Relational Mapper)
* Differences between a **decoupled system** and a **tightly coupled system**
* `Create Engine` function
* `Automap Base` function
* **Reflect Tables** using `prepare` function
* `Session` link to database

## Results 

The results of this analysis are comprised from looking at annual temperature data from the months of June and December.

### June Takeaways

1. The average temperature is 74.94 degrees fahrenheit
2. The minimum temperature is 64 degrees fahrenheit
3. The maximum temperature is 85 degrees fahrenheit

This data is comprised of 1700 entries.

!["june_temp"](https://github.com/Wall-E28/surf_analysis/blob/master/resources/june_temp.png)

### December Takeaways

1. The average temperature is 71.04 degrees fahrenheit
2. The minimum temperature is 56 degrees fahrenheit
3. The maximum temperature is 83 degrees fahrenheit

This data is comprised of 1517 entries.

!["dec_temp"](https://github.com/Wall-E28/surf_analysis/blob/master/resources/dec_temp.png)

### Summary

By looking at the results, opening a surf shop would be a smart investment. This is because there is an enjoyable average temperature in two months that are 6 months apart from one another. That shows that for most months of the year, there will be enjoyable temperature for people to come and use the surf shop.
