# WeatherAPI

A simple Python script that fetches and displays the current weather data for Kakamega, Kenya using the free Open-Meteo API.

## What does it do?

This script sends a request to the Open-Meteo weather API and retrieves the current weather conditions for Kakamega (latitude: 0.28, longitude: 34.75).  
It extracts and displays:
- Temperature
- Wind Speed
- Wind Direction

## Why does it exist?

This project was created as a practical learning exercise to:
- Practice making HTTP requests in Python using the `requests` library
- Work with real-world APIs
- Understand how to parse and display JSON data
- Build a small, useful tool that can be expanded later (e.g., adding forecasts, different locations, or a web interface)

## How do you run it?

### Prerequisites
- Python 3.x installed
- `requests` library

### Installation

1. Clone the repository:
```bash
git clone https://github.com/AOB26_ai/WeatherAPI.git


### Its Output


Status Code: 200
Data received:
{'latitude': 0.28, 'longitude': 34.75, 'generationtime_ms': 0.12, 'utc_offset_seconds': 10800, 'timezone': 'Africa/Nairobi', 'timezone_abbreviation': 'EAT', 'elevation': 1530.0, 'current_weather_units': {...}, 'current_weather': {'time': '2026-10-25T12:00', 'interval': 900, 'temperature': 24.5, 'windspeed': 8.3, 'winddirection': 150, 'is_day': 1, 'weathercode': 1}}

Weather Data for Kakamega:
Temperature: 24.5
Wind Speed: 8.3
Wind Direction: 150
cd WeatherAPI

