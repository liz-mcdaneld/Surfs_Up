# Surfs Up Analysis

## Overview

An investor is looking to build a Surf and Ice Cream shop in Oahu, Hawaii but wants to know more about the weather trends before opening the shop. Specifically, the temperature during June and December to see if the shop will have business year-round. 

## Purpose
1.	Use Flask application on Climate Analysis data.
2.	Use SQLAlchemy to connect to an SQLite database.
3.	Query the data that filters the date column for the requested months from the Measurement table.
4.	Convert the data to a list.
5.	Create a DataFrame from the list of data for the respective months.
6.	Use summary statistics for the DataFrame.
7.	Plot a graph to further visualize the data with Matplotlib.

## Results

### June
The June temperatures statistics are listed in the table below:

![June_temps_png](https://user-images.githubusercontent.com/103263248/178521653-15f93d58-ea47-4786-b833-346d3f3ed0e4.png)


The June precipitation statistics are listed in the table below:

![June_percipitation_png](https://user-images.githubusercontent.com/103263248/178521718-41934ee1-94be-4124-bf9c-31ff5616270b.png)

•	The mean, or average, temperature is 75F.

•	The mean, or average, precipitation is 0.14 inches.

Using Matplotlib to graph the temperatures for June to visualize the data:

![June_temps_plot_png](https://user-images.githubusercontent.com/103263248/178521756-f977660b-a4c8-45fe-b217-cc645ee0d161.png)

•	More frequent temperatures of approx. 70F to 80F during June.

The June Temperature to Percipitation Statistics Summary:

![June_temp_prcp_png](https://user-images.githubusercontent.com/103263248/178521907-e2fce080-5837-47ad-b939-a5485b38def5.png)

Using Matplotlib to scatter plot the relationship of June Temperatures to Precipitation:

![June_temp_prcp_scatter_png](https://user-images.githubusercontent.com/103263248/178521809-f5007c58-1fb5-49ff-9824-ebda7e4d1f9c.png)

•	As the temperature increases the precipitation decreases in June.

•	Highest precipitation in relation to the temperature is approx. 68F to 72F.

### December
The December temperatures statistics are listed in the table below:

![December_temps_png](https://user-images.githubusercontent.com/103263248/178522206-a895d682-ef8d-46cd-956c-0800d6b4a4c9.png)

The December precipitation statistics are listed in the table below:

![December_percipitation_png](https://user-images.githubusercontent.com/103263248/178522303-5da13f07-e0fe-47ea-9b33-420df87cc5b5.png)

•	The mean, or average, temperature is 71F.

•	The mean, or average, precipitation is 0.22 inches.

Using Matplotlib to graph the temperatures for December to visualize the data:

![December_temps_plot_png](https://user-images.githubusercontent.com/103263248/178522375-fc14d944-3963-473f-8d6f-fc2132d49e14.png)

•	More frequent temperatures of approx. 68F to 75F during December.

The December Temperature to Percipitation Statistics Summary:

![December_temps_prcp_png](https://user-images.githubusercontent.com/103263248/178522558-3134a579-bc68-4345-86ba-c3329a635c4e.png)

Using Matplotlib to scatter plot the relationship of December Temperatures to Precipitation:

![December_temps_prcp_scatter_png](https://user-images.githubusercontent.com/103263248/178522639-c9cd592e-03d1-4682-bce5-f3c3629c48ee.png)

•	Cooler temperatures appear to encourage higher precipitation.

•	December has a slightly higher precipitation than June, but both are realtively low percipitation with a few outliers.

## Summary

The main concern was does the weather in Oahu, Hawaii support opening a year-round Surf and Ice Cream shop. The temperature data is not vastly different in June versus December. Both have averages in the 70F range. The additional query on precipitation also gives insight into whether or not it will be raining to often to keep the shop open. Excluding a few outliers of high precipitation, both June and December have low averages of precipitation. All the data together encourages opening a Surf and Ice Cream shop year-round.  
