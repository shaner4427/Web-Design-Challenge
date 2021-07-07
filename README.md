# Weather-API

# Objectives

The main objective of this project was to take weather data from random locations around the world and prove that the weather does in fact get warmer as one approaches the equator.  By using citipy and OpenWeatherMap's API, one is able to generate weather data from 600+ cities around the world and analyze the impact location has on different weather elements.  A website was then created to better summarize and visualize the data for better comprehension.

# The Code

The code was written and executed using Jupyter Notebook.  Below are the dependencies used:
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

Using matplotlib, plots were created to determine the correlation between latitude and elements of weather.

![image](https://user-images.githubusercontent.com/74691093/124391818-eab83a00-dcb7-11eb-9f1e-02873883834d.png)

![image](https://user-images.githubusercontent.com/74691093/124391931-9e212e80-dcb8-11eb-8151-78251821d5fe.png)


# Analysis

As expected, the weather becomes significantly warmer as one approaches the equator (0 Deg. Latitude).  More interestingly, however, is the fact that the southern hemisphere tends to be warmer this time of year than the northern hemisphere. This may be due to the tilt of the earth.  There is no strong relationship between latitude and cloudiness. However, it is interesting to see that a strong band of cities sits at 0, 80, and 100% cloudiness.  There is no strong relationship between latitude and wind speed. However, in northern hemispheres there is a flurry of cities with over 20 mph of wind.

Additionally, in order to present a better visual showing how the average temperature increases as one approaches the equator, Tableau was used to map out the average temperature by country.

https://public.tableau.com/views/WeatherPy/Sheet1?:language=en-US&:display_count=n&:origin=viz_share_link

