Web Application using three.js for visualizing census data vs population density of US counties.
Further data can be added via data from US census website.


I was able to get this webpage running in Firefox by just hosting it with python. 
python -m http.server
It also lags a lot and sometimes runs into memory errors, might be a memory leak.
I tried to make it more efficient but couldn't figure out a way to get 3000+ geometries to load well.


data from https://www.census.gov/data.html
geojson file from https://eric.clst.org/tech/usgeojson/

Tianlu David Wang


