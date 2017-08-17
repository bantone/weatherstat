weatherstat
# WeatherStat 
A simple python tool that leverages OpenWeatherMap's API to generate weather stats.

## First Steps
In order for this to work you will need to to sign up for an OpenWeatherMap API Key (https://openweathermap.org/api)

What I do is create a APPID variable in my zsh environment in order to call the API key in order to use it.

## Current Functionality

```
usage: weatherstat [-h] [-z ZIP] [-c CITY] [-id ID] [-lat LAT] [-lon LON]

optional arguments:
  -h, --help            show this help message and exit
  -z ZIP, --zip ZIP     zipcode
  -c CITY, --city CITY  city
  -id ID, --id ID       city id
  -lat LAT              latitude
  -lon LON              longitutde
  --data DATA           current weather data / 5 day / 3 hour forecast
```

Any suggestions appreciated! :) 

I am attempting to add more functionality to it outside of simply generating the current weather, pulling historical data, and making JSON pretty.
