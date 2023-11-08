# sqlalchemy-challenge
# SQLAlchemy Challenge: Honolulu Climate Analysis

This repository contains the code and analysis for the SQLAlchemy Challenge, focusing on climate analysis for Honolulu, Hawaii.

## Project Description

Congratulations! You've decided to treat yourself to a long holiday vacation in Honolulu, Hawaii. To help with your trip planning, you've performed a climate analysis of the area. This project includes both data analysis using Python and SQLAlchemy and a Flask API to serve the analyzed climate data.

## Part 1: Analyze and Explore the Climate Data

In this section, you performed the following tasks:

1. Used SQLAlchemy to connect to the SQLite database.
2. Used SQLAlchemy to reflect the database tables into classes (`station` and `measurement`).
3. Performed a precipitation analysis to find the most recent date, retrieve the previous 12 months of precipitation data, and plot the results.
4. Calculated the summary statistics for the precipitation data.
5. Conducted a station analysis to find the total number of stations, identify the most-active stations, and calculate the lowest, highest, and average temperatures for the most-active station.
6. Analyzed temperature observation (TOBS) data for the most-active station over the previous 12 months and plotted the results as a histogram.

## Part 2: Design Your Climate App

In this section, you designed a Flask API with the following routes:

- `/`: The homepage listing all available routes.
- `/api/v1.0/precipitation`: Providing precipitation data for the last 12 months as a JSON dictionary.
- `/api/v1.0/stations`: Providing a JSON list of stations.
- `/api/v1.0/tobs`: Offering temperature observations (TOBS) for the previous year for the most-active station.
- `/api/v1.0/<start>` and `/api/v1.0/<start>/<end>`: Returning JSON data for minimum, average, and maximum temperatures for specified date ranges.


