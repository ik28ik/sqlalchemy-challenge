
This repo contains homework from the SQLAlchemylecture series from The Columbia Engineering Data Analytics Boot Camp.

I used SQLAlchemy, and a Flask API called, app.py, to perform and pull climate data from the hawaii.sqlite weather station tables. Data analysis was performed using Python and Pandas (Jupyter Notebook).

The Jupyter Notebook contains the climate analysis for precipitation and temperature in Hawaii, from 08-23-2016 to 08-23-2017 (last twelve months of data). It also looks at specific trip dates from 05-09-2017 to 05-12-2017 to model the climate temperature normals and precipitation based on historical weather data.

Also included an Flask API Application to query:

* Precipitations from last year
* Weather stations
* Temperature Observations (tobs) for the previous year
Minimum temperature, the average temperature, and the max temperature for a given start and/or start-end range inlcusive.