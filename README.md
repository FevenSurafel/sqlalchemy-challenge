# sqlalchemy-challenge

## Summary

This project involves analyzing climate data for Honolulu, Hawaii, using SQLAlchemy, Pandas, and Matplotlib, and creating a Flask API to serve the analysis results.

### Key Components

- **Jupyter Notebook Analysis:** 
  - `climate_starter.ipynb`: Perform climate analysis including precipitation and station data.
  
- **Flask API:** 
  - `app.py`: Provide API endpoints to access the climate analysis results.

### Flask API Endpoints

- `/api/v1.0/precipitation`: Returns last 12 months of precipitation data.
- `/api/v1.0/stations`: Returns a list of weather stations.
- `/api/v1.0/tobs`: Returns last 12 months of temperature observations for the most-active station.
- `/api/v1.0/<start>`: Returns min, max, and average temperatures from the start date.
- `/api/v1.0/<start>/<end>`: Returns min, max, and average temperatures from the start date to the end date.
