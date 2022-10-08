
# Surfs_up
Precipitation, Temperature and Weather Station analysis using SQLite and SQLAlchemy. Climate App building using Flask. Other tools use in this analysis include Python and Jupyter Notebooks.

## Overview of Surfs Up Analysis

The purpose and aim of this analysis is to review a dataset pertaining to weather conditions of Hawaii. The analysis would provide us the information that will convince an investor that opening up a **Surf n' Shake** shop in Oahu, Hawaii is a good business idea. The idea is that the shop will sell surf boards and ice cream throughout the year, but the investor is hesitant because he invested in a similar business that failed due to the weather conditions. In order to get this investor on board, we need to provide statistical analytics specifically on the weather conditions in Oahu that will convince him that this will be a successful business venture.

More so, in order to explore the data in the `SQLite` database, we used `SQLAlchemy` to connect and generate queries to pull the necessary information needed for our analysis. Throughout this module, we used jupyter notebook to import dependencies and create the commands to pull the data from the `SQLite` database. The features/functions below are some of the other useful tools that we also learned in this module:

**SQLAlchemy**
* `ORM` (Object Relational Mapper)
* `Create Engine` function
* `Automap Base` function
* **Reflect Tables** using `prepare` function
* `Session` link to database

## Results 

The results of this analysis consists of annual temperature data from the months of June and December.

### June Takeaways.

The following are summary of this project

1. The average temperature is 74.94 degrees fahrenheit
2. The minimum temperature is 64 degrees fahrenheit
3. The maximum temperature is 85 degrees fahrenheit

This data is comprised of 1700 entries.

!["june_temp"](https://github.com/Adpetfem83/surfs_up/blob/main/Images/June_temp.png)

### December Takeaways

1. The average temperature is 71.04 degrees fahrenheit
2. The minimum temperature is 56 degrees fahrenheit
3. The maximum temperature is 83 degrees fahrenheit

This data is comprised of 1517 entries.

!["dec_temp"](https://github.com/Adpetfem83/surfs_up/blob/main/Images/Dec_temp.png)

### Summary

Mere looking at the results, opening a surf shop would be a smart investment. This is because there is an enjoyable average temperature in two months that are 6 months apart from one another. That shows that for most months of the year, there will be enjoyable temperature for people to come and use the surf shop.
