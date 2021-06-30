# Weather-API

# Objectives

The main objective of this project was to take weather data from random locations around the world and prove that the weather does in fact get warmer as one approaches the equator.  By using citipy and OpenWeatherMap's API, one is able to generate weather data from 600+ cities around the world and analyze the impact location has on different weather elements.  A website was then created to better summarize and visualize the data for better comprehension.

# The Code

The code was written and performed using Jupyter Notebook.  Below are the dependencies used:
- matplotlib
- pandas
- numpy
- requests
- time 
- scipy
- citipy

Random latitudes and longitudes were generated and then used to find the nearest cities.  The cities were then appended to a list.

![image](https://user-images.githubusercontent.com/74691093/124031754-5307d280-d9bd-11eb-94e4-b60a1c8b93bb.png)

An API call was then performed using OpenWeatherMap's API and the information to be analyzed was then appended to a list.

![image](https://user-images.githubusercontent.com/74691093/124033874-20130e00-d9c0-11eb-95a9-e4b713452d6a.png)
