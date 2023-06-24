# Github-Copilot-Hackathon


# Weather Forecast Command-Line Tool

This is a command-line tool that accepts a city's name as input and returns the current weather forecast using the OpenWeatherMap API. Leveraging OpenWeatherMap API to fetch weather data and parsing it using Python.

## Prerequisites

- Python 3.x installed on your system
- `requests` library installed (you can install it by running `pip install requests`)

## Getting Started

1. Clone or download this repository to your local machine.
2. Sign up on the [OpenWeatherMap website](https://openweathermap.org/) to obtain an API key.
3. Open the `weather_forecast.py` file in a text editor.
4. Replace `"YOUR_API_KEY"` with your actual OpenWeatherMap API key (line 9).
   
## Usage

Run the command-line tool by executing the `weather_forecast.py` script from the command line and providing a city name as an argument.

## Working

1. The script constructs the API endpoint URL using the provided city name and your OpenWeatherMap API key.
2. It sends a GET request to the OpenWeatherMap API using the `requests` library.
3. If the response status code is 200, the JSON response is parsed, and relevant weather information is extracted.
4. The extracted weather information, including the city name, temperature, and description, is printed to the console.

## Error Handling

- If the API request fails, an appropriate error message is displayed.
- If the API response status code is not 200, an error message with the status code is shown.
- If no city name is provided as a command-line argument, an error message is displayed.




This code was written using GitHub Copilot, which can help you with API usage, data parsing, and error handling. For example, if you are not sure how to construct the URL for the OpenWeatherMap API, GitHub Copilot can suggest code that will help you. Or, if you are having trouble parsing the JSON response from the API, GitHub Copilot can suggest code that will help you extract the relevant data. GitHub Copilot can also help you to handle errors that may occur when you are fetching weather data from the API.
