# Weather App 🌤️

A simple Python application that fetches real-time weather information using the [OpenWeatherMap API](https://openweathermap.org/api).

## Features

- 🌡️ Current temperature in Celsius and Fahrenheit
- 🌡️ Feels-like temperature
- 💧 Humidity
- 💨 Wind speed
- 🌥️ General weather conditions
- 🌅 Sunrise and sunset times (local time)

## Technologies Used

- Python
- Requests library
- OpenWeatherMap API
- Datetime module

## Installation

**1. Clone the repository**

```bash
git clone https://github.com/YOUR_USERNAME/python-weather-app.git
cd python-weather-app
```

**2. Install dependencies**

```bash
pip install requests
```

**3. Set up your API key**

Create a file named `api_key` in the project directory and paste your OpenWeatherMap API key into it.

Get your API key here: https://openweathermap.org/api

**4. Run the application**

```bash
python weather-api.py
```

## Example Output

```text
Temperature in Astana: 15.25*C or 59.45*F
Temperature in Astana feels like: 14.10*C or 57.38*F
Humidity in Astana: 65%
Wind Speed in Astana: 3.5m/s
General Weather in Astana: scattered clouds
Sun Rises in Astana at 2026-11-17 07:30:00 local time.
Sun Sets in Astana at 2026-11-17 16:45:00 local time.
```

*Note: The output above is an illustrative example, not live weather data.*

## What I Learned

- Working with external APIs using Python
- Sending HTTP requests with the Requests library
- Processing JSON responses
- Working with dates and timestamps
- Converting temperature units
- Using API keys to access external services

## Author

Created as a Python learning project.