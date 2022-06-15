# Weather-Data-Clustering
Cluster analysis to generate a big picture model of the weather at a local station using a minute-graunlarity data.

Each row in weather.csv contains weather data captured for a one-minute interval. Each row, or sample, consists of the following variables:

rowID: unique number for each row (Unit: NA)
hpwren_timestamp: timestamp of measure (Unit: year-month-day hour:minute:second)
air_pressure: air pressure measured at the timestamp (Unit: hectopascals)
air_temp: air temperature measure at the timestamp (Unit: degrees Fahrenheit)
avg_wind_direction: wind direction averaged over the minute before the timestamp (Unit: degrees, with 0 means coming from the North, and increasing clockwise)
avg_wind_speed: wind speed averaged over the minute before the timestamp (Unit: meters per second)
max_wind_direction: highest wind direction in the minute before the timestamp (Unit: degrees, with 0 being North and increasing clockwise)
max_wind_speed: highest wind speed in the minute before the timestamp (Unit: meters per second)
min_wind_direction: smallest wind direction in the minute before the timestamp (Unit: degrees, with 0 being North and inceasing clockwise)
min_wind_speed: smallest wind speed in the minute before the timestamp (Unit: meters per second)
rain_accumulation: amount of accumulated rain measured at the timestamp (Unit: millimeters)
rain_duration: length of time rain has fallen as measured at the timestamp (Unit: seconds)
relative_humidity: relative humidity measured at the timestamp (Unit: percent)
