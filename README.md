# ML Summer School (2018) - Assignment 1

Fork this repo and complete the assignment. After completing the assignment, submit it [here](https://docs.google.com/forms/d/e/1FAIpQLSdOfz8veM9h8P4sT0NRI5PV6_-xJH4enm3syeg7LZ2OR97aCg/viewform).

## Assignment_1_1 - Numpy and Python Basics

The first part of the assignment is aimed to make you familiar with some of the basic Numpy functions. This assignment, along with the part 2 of it, is given in Python Notebook to make you feel comfortable while working in that notebook environment.


### Files Given

	array.pickle - A pickle file containing input array.
	Assignment_1_1.ipynb - A Python notebook which needs to be filled by you at appropriate palces to complete the assignment. Read the comments in order to understand what is required to be done at each step. 

In case you don't know the function which is required to execute any given operation or if you can't remember its syntax, Google your way out! Still if you face any difficulties, you can ask on the Slack channel. 


## Assignment_1_2 - Pandas Matplotlib


The 2nd part of this assignment helps you get familiar with Pandas functionalities and various Matplotlib operations you can do to generate various kinds of plots.

### Files Given

	day.csv -  It is part of a Bike Sharing Dataset. This dataset relates the bike sharing counts with various factors like temperature, weather and season. The fields present in day.csv are:
		
			* instant: record index
			* dteday : date
			* season : season (1:springer, 2:summer, 3:fall, 4:winter)
			* yr : year (0: 2011, 1:2012)
			* mnth : month ( 1 to 12)
			* hr : hour (0 to 23)
			* holiday : weather day is holiday or not (extracted from http://dchr.dc.gov/page/holiday-schedule)
			* weekday : day of the week
			* workingday : if day is neither weekend nor holiday is 1, otherwise is 0.
			+ weathersit : 
					* 1: Clear, Few clouds, Partly cloudy, Partly cloudy
					* 2: Mist + Cloudy, Mist + Broken clouds, Mist + Few clouds, Mist
					* 3: Light Snow, Light Rain + Thunderstorm + Scattered clouds, Light Rain + Scattered clouds
					* 4: Heavy Rain + Ice Pallets + Thunderstorm + Mist, Snow + Fog
			* temp : Normalized temperature in Celsius. The values are divided to 41 (max)
			* atemp: Normalized feeling temperature in Celsius. The values are divided to 50 (max)
			* hum: Normalized humidity. The values are divided to 100 (max)
			* windspeed: Normalized wind speed. The values are divided to 67 (max)
			* casual: count of casual users
			* registered: count of registered users
			* cnt: count of total rental bikes including both casual and registered
	Assignment_1_2.ipynb - A Python notebook which needs to be filled by you at appropriate palces to complete the assignment. Read the comments and text in order to understand what is required to be done at each step. 


This part of the assignment is abit tougher than the first one. On successfully filling a plotting function completely, the corresponding plot will get generated.	

