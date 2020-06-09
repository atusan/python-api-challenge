# python-api-challenge
This project is a part of the Data Analytics Boot Camp projects.

#### -- Project Status: [Completed]

## Project Intro
The purpose of this project consists of two parts:
* Part I - WeatherPy
* Part II - VacationPy
 
### Technologies
* Python
* Pandas, matplotlib, APIs, jupyter

## Project Description
### Part I - WeatherPy
The purpose of Part I is to create a Python script to visualize the weather of 500+ cities across the world of varying distance from the equator. Data is from the [OpenWeatherMapAPI](https://assertible.com/blog/7-http-methods-every-web-developer-should-know-and-how-to-test-them)

The scatter plots showcase the following relationships:

* Temperature (F) vs. Latitude
* Humidity (%) vs. Latitude
* Cloudiness (%) vs. Latitude
* Wind Speed (mph) vs. Latitude

The next objective is to run linear regression on each relationship:
* Northern Hemisphere - Temperature (F) vs. Latitude
* Southern Hemisphere - Temperature (F) vs. Latitude
* Northern Hemisphere - Humidity (%) vs. Latitude
* Southern Hemisphere - Humidity (%) vs. Latitude
* Northern Hemisphere - Cloudiness (%) vs. Latitude
* Southern Hemisphere - Cloudiness (%) vs. Latitude
* Northern Hemisphere - Wind Speed (mph) vs. Latitude
* Southern Hemisphere - Wind Speed (mph) vs. Latitude

The final result consists of:

* Randomly select at least 500 unique (non-repeat) cities based on latitude and longitude.
* Perform a weather check on each of the cities using a series of successive API calls.
Include a print log of each city as it's being processed with the city number and city name.
* Save a CSV of all retrieved data and a PNG image for each scatter plot.
### Part II - VacationPy
* The purspose of Part II is to create a heat map that displays the humidity for every city from the part I and narrow down the DataFrame to find your ideal weather condition. 
