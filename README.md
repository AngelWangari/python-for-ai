# 🌦️ Nairobi Weather Analysis

## Overview

This is a simple Python project that retrieves weather data for Nairobi over the past seven days using the Open-Meteo API. The data is processed, visualized, and saved for future analysis.

## Features

* Fetches the last 7 days of weather data from the Open-Meteo API
* Displays daily maximum and minimum temperatures
* Generates a line chart for easy visualization
* Saves the weather data as a CSV file
* Automatically creates a `data` folder if it doesn't exist

## Technologies Used

* Python
* Pandas
* Matplotlib
* Requests
* Open-Meteo API

## Project Structure

```text
├── data/
│   └── nairobi_weather.csv
├── weather_chart.png
├── weather.py
└── README.md
```

## Getting Started

1. Clone this repository.
2. Install the required libraries:

```bash
pip install pandas matplotlib requests
```

3. Run the project:

```bash
python weather.py
```

The program will fetch the latest weather data, display a temperature chart, save the chart as `weather_chart.png`, and export the data to `data/nairobi_weather.csv`.

## Purpose

This project demonstrates how to work with APIs, process data using Pandas, create visualizations with Matplotlib, and save datasets for further analysis. It serves as a beginner-friendly example of integrating data collection, analysis, and visualization in Python.
