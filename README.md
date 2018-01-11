# Predicting-Bike-Sharing-Demand-Using-Linear-Regression
This repository comprises of R Code for Exploratory Data Analysis conducted on Bike Sharing Demand data set. 
The document also comprises of Linear Regression Model which is built to predict the rental bike count based on different features.

# About Project
This project focuses on conducting Exploratory Data Analysis and running Linear Regression on Bike Sharing Demand data set
which was provided by Hadi Fanaee Tork using data from Capital Bikeshare.

## What is Bike Sharing Systems ?
Bike sharing systems are a means of renting bicycles where the process of obtaining membership, rental, and bike return is automated 
via a network of kiosk locations throughout a city. Using these systems, people are able rent a bike from a one location and return
it to a different place on an as-needed basis. Currently, there are over 500 bike-sharing programs around the world.

## Objective
The main objective of this project is to explore and create a linear Regression Model so as to try to predict bike sharing demand.

## Features 
The data set contains following features :-
datetime - hourly date + timestamp 
season - 1 = spring, 2 = summer, 3 = fall, 4 = winter 
holiday - whether the day is considered a holiday 
workingday - whether the day is neither a weekend nor holiday 
weather - 
 1: Clear, Few clouds, Partly cloudy, Partly cloudy 
 2: Mist + Cloudy, Mist + Broken clouds, Mist + Few clouds, Mist 
 3: Light Snow, Light Rain + Thunderstorm + Scattered clouds, Light Rain + Scattered clouds 
 4: Heavy Rain + Ice Pallets + Thunderstorm + Mist, Snow + Fog 
 
temp - temperature in Celsius 
atemp - “feels like” temperature in Celsius 
humidity - relative humidity 
windspeed - wind speed 
casual - number of non-registered user rentals initiated 
registered - number of registered user rentals initiated 
count - number of total rentals 

## What we are trying to predict ?
We are trying to predict count variable i.e. number of total rentals which will be behaving as a dependent variable for our analysis.

## Exploratory Data Analysis
First I will be conducting exploratory data analysis which is an essential step to undestand the data.

## Scatter Plot to show the relationship between count (number of total rentals) and temp (temperature in Celsius)
![pic1](https://user-images.githubusercontent.com/16829371/34804580-60e7f57c-f647-11e7-806d-0bc467adffa8.png)

The above scatter plot shows that as the temperature increases the count i.e. the number of total rentals also increases.

## Scatter Plot to show the relationship between count (number of total rentals) and date time.

There is a clear seasonal trend where the total rental bikes seems to decrease during Winters i.e month of January 
and Feburary of the year and the total rental bikes seems to increase during summers.
The other trend which is quite evident is that the number of rental bike counts is increasing from year 2011 to year 2013.

## Box Plot

The box plot between the number of bike rentals and season shows that the line can not capture the non linear relationship and that there’s is more rentals in winter as compared to spring.

