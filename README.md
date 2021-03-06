# lab-06 -> 09 City Explorer Back-end

**Author**: Brendan Smith
**Version**: 1.0.0

## Overview
Provides back-end support for the Code Fellows City Explorer front-end. 

## Getting Started
- Get API keys from: Yelp, NPS, Geocode, Weatherbit, and MovieDB
- Get connection string for Postgres database-url
- install node modules
- set up a port 
- Generate .env file with values for PORT, GEOCODE_API_KEY, WEATHER_API_KEY, PARKS_API_KEY, MOVIE_API_KEY, DATABASE_URL, YELP_API_KEY

## Architecture
Requires Node.js, cors, dotenv, and express. 

## Change Log
01-18-21 6:23pm - Application has functioning /location and /weather paths, returning data from attached JSON files.
01-19-21 4:59pm - Added locationIQ api integration to search location data, Weatherbit api for weather data, and NPS parks  api for local park data. 
01-20-21 7:06pm - Added postgresql database storage for location data. 


## Credits and Collaborations
CodeFellows' [City Explorer](https://codefellows.github.io/code-301-guide/curriculum/city-explorer-app/front-end/) project front-end was crucial to this project.
Thanks to TA Chance for his assistance.

## Lab-06
Number and name of feature: *Repository setup*

    Estimate of time needed to complete: 45m

    Start time: 3:15

    Finish time: 4:00

    Actual time needed to complete: 45m

Number and name of feature: *Locations*

    Estimate of time needed to complete: 1hr

    Start time: 4:00

    Finish time: 5:20

    Actual time needed to complete: 1hr20m

Number and name of feature: *Weather*

    Estimate of time needed to complete: 1 hr

    Start time: 5:20

    Finish time: 6:00

    Actual time needed to complete: 40m

Number and name of feature: *Errors*

    Estimate of time needed to complete: 20m

    Start time: 6:00

    Finish time: 6:17

    Actual time needed to complete: 17m

## Lab-07
Number and name of feature: *Code Review*

    Estimate of time needed to complete: 0:45

    Start time: 3:00

    Finish time: 3:45

    Actual time needed to complete: 0:45

Number and name of feature: *Heroku Deployment*

    Estimate of time needed to complete: n/a (automatic heroku deployments were enabled yesterday)

    Start time: 2:45

    Finish time: 2:45

    Actual time needed to complete: n/a

Number and name of feature: *getWeather callback to .map*

    Estimate of time needed to complete: 0:15

    Start time: 3:35

    Finish time: 3:45

    Actual time needed to complete: 0:10

Number and name of feature: *Locations*

    Estimate of time needed to complete: 0:30

    Start time: 4:30

    Finish time: 4:59

    Actual time needed to complete: 0:30

Number and name of feature: *Weather*

    Estimate of time needed to complete: 0:30

    Start time: 5:00

    Finish time: 5:43

    Actual time needed to complete: 0:43

Number and name of feature: *Parks*

    Estimate of time needed to complete: 1:00

    Start time: 5:44

    Finish time: 7:05

    Actual time needed to complete: 1:20

## Lab-08

Number and name of feature: Database

    Estimate of time needed to complete: 0:30

    Start time: 4:20

    Finish time: 5:09

    Actual time needed to complete: 0:51

Number and name of feature: Server

    Estimate of time needed to complete: 0:45

    Start time: 5:15

    Finish time: 6:25

    Actual time needed to complete: 0:50

Number and name of feature: Heroku

    Estimate of time needed to complete: 1:00

    Start time: 6:30

    Finish time: 7:06

    Actual time needed to complete: 0:36

## Lab-09

Number and name of feature: Movies

    Estimate of time needed to complete: 1:00

    Start time: 4:40

    Finish time: 5:45

    Actual time needed to complete: 1:05

Number and name of feature: Yelp

    Estimate of time needed to complete: 1:00

    Start time: 6:30

    Finish time: 7:42

    Actual time needed to complete: 1:42

Number and name of feature: Pagination

    Estimate of time needed to complete: 0:30

    Start time: 7:43

    Finish time: 7:53

    Actual time needed to complete: 0:10