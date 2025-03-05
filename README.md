# sqlalchemy-challenge

Climate Analysis and Flask API - Honolulu, Hawaii


Project Overview

This project conducts a climate analysis and data exploration using Python, SQLAlchemy, Pandas, and Matplotlib to understand weather patterns in Honolulu, Hawaii. The project is divided into two main parts:

Part 1: Climate Data Analysis - Explore precipitation data, station activity, and temperature observations.
Part 2: Flask Climate App - Develop a Flask API to serve climate data with multiple routes.


Data Source

Database: hawaii.sqlite

This SQLite database contains two tables:
-measurement (weather observations)

-station (weather stations)


Pandas and Matplotlib was used  to print the summary statistics for the precipitation data



Pandas and Matplotlib was used  to print the last 12 months of temperature observation data for this station .



Flask Climate API

I designed a Flask API based on the queries developed in my analysis for Climate data.








Route	Description

/	Homepage listing all available routes

/api/v1.0/precipitation	JSON representation of precipitation data for the last 12 months

/api/v1.0/stations	JSON list of all weather stations

/api/v1.0/tobs	JSON list of temperature observations (TOBS) for the most active station for the past year

/api/v1.0/<start>	JSON list of the minimum, average, and maximum temperatures for all dates after the start date

/api/v1.0/<start>/<end>	JSON list of the minimum, average, and maximum temperatures for dates between the start and end date


Conclusion 


This project serves as a comprehensive exercise in data exploration, analysis, visualization, and API development, It gave me an opportunity to both study historical weather patterns and make the data accessible through a RESTful API.