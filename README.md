# Hourly Sky

A small weather app: pick a city and a date range (up to 16 days ahead, or back to 1940) to see hourly temperature, feels-like, rain, wind, UV and a suggestion of what to wear. Starts in °C, with a °F switch.

Live page: https://malavikaramprasad.github.io/hourly-sky/

Temperature and rain are a blend (median) of up to seven forecast models: ECMWF, GFS, ICON, UK Met Office, Météo-France, GEM and JMA. The chart shades the range between models, and each day shows how closely they agree. You can also pick a single model.

Weather data by [Open-Meteo.com](https://open-meteo.com/) (CC BY 4.0). No API key or build step; everything is in `index.html`.
