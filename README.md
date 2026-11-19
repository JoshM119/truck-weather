# truck-weather

## Endpoint
https://api.open-meteo.com/v1/forecast?latitude=31.14352&longitude=-93.261&current=temperature_2m,wind_speed_10m&timezone=auto&wind_speed_unit=mph&temperature_unit=fahrenheit (Open-Meteo, GET)

## What I changed using the docs
I added `Timezone=auto amd wind_speed_unit=mph`.
Before:  Timezone was in GMT and wind speed was showing km/h.
After: Time show showing in correct timezone as location in url and wind speed in mph

## Live site

https://JoshM119.github.io/truck-weather/