# Weather Report App

A simple weather application built with Python. The app asks the users to type a U.S. city, calls the OpenWeather API, and displays the current weather information in the terminal.

## Features

* Accepts a city name from the command line
* Retrieves current weather data from the OpenWeather API
* Displays the city name, temperature in Celsius, humidity, weather description, feel-like temperature.

## Requirements

* Python 3.10
* `requests`
* `python-dotenv`
* An OpenWeather API key

## Installation

1. Clone this repository:

```bash
git clone YOUR_GITHUB_REPOSITORY_URL
cd week5-day1-challenge
```

2. Install the required packages:

```bash
pip install -r requirements.txt
```

3. Create a `.env` file in the project folder.

Add your OpenWeather API key:

```text
OPENWEATHER_API_KEY=your_api_key_here
```

Please remember do not upload `.env` file to GitHub.

## Run the App

Run the program from the terminal:

```bash
python weather.py
```

Enter a U.S. city when prompted:

```text
Enter a US city: Seattle
```

Example output:

```text
In Seattle, it is 25.9°C with clear sky. The humidity is 56%. It feels like 26.01°C.
```

## Project Structure

```text
week5-day1-challenge/
│
├── weather.py
├── requirements.txt
├── README.md
├── .env
└── .gitignore
```

## API

This project uses the OpenWeather Current Weather API to retrieve current weather information.
