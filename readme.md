# Climate Analysis and Weather API

## Table of Contents
- [Description](#description)
- [Data Files](#data-files)
- [Features](#features)
- [Installation](#installation)
- [Results](#results)
- [Author](#author)

---

## Description

This project conducts a climate analysis on weather data in Hawaii and builds a simple Flask-based API to deliver the results. Using Python and SQLAlchemy, the project interacts with a SQLite database containing weather station data and temperature measurements. A Jupyter Notebook is used for exploratory data analysis and visualizations.

---

## Data Files

The project includes the following files:

| File Name                 | Description                                           |
|---------------------------|-------------------------------------------------------|
| `hawaii_measurements.csv` | Contains weather measurements like precipitation and temperature. |
| `hawaii_stations.csv`     | Contains information about weather stations in Hawaii. |
| `hawaii.sqlite`           | SQLite database file containing weather data.        |
| `climate_starter.ipynb`   | Jupyter Notebook for data exploration and analysis.  |
| `app.py`                  | Flask application to set up weather data API routes. |

---

## Features

1. **Exploratory Data Analysis**:
   - Analyze weather data (precipitation, temperatures) in Hawaii.
   - Visualize trends using Matplotlib.

2. **Database Interaction**:
   - Use SQLAlchemy to query the SQLite database for climate data.
   - Perform data retrievals for weather stations and measurements.

3. **Flask Weather API**:
   - Create API routes to query weather information:
     - `/api/v1.0/precipitation` - Precipitation data.
     - `/api/v1.0/stations` - List of weather stations.
     - `/api/v1.0/tobs` - Temperature observations for the most active station.
     - `/api/v1.0/<start>` and `/api/v1.0/<start>/<end>` - Min, average, and max temperatures for a date range.

---

## Installation

1. **Prerequisites**: 
- Python 3.x
- SQLite
- Flask
- Jupyter Notebook

2. **Setup**:
- Clone this repository or download the project files.
     
- Install dependencies (if needed):
```bash
     pip install -r requirements.txt
```
---

## Results 

## Key Insights:

1.	Precipitation Trends:
- Analysis shows seasonal precipitation patterns in Hawaii.
2.	Temperature Observations:
- Temperature observations indicate consistent warmth, with peak observations in the most active weather station.

Example Outputs:
- Visualization: Line charts for precipitation trends over time.
- Flask API: JSON responses with climate data for specific routes.