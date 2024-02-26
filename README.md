# Clima Telegram Bot

Clima is a Telegram bot that provides weather updates for users' locations. It utilizes the OpenWeatherMap API to fetch weather data and sends formatted messages containing various weather information.

## Features

- **Weather Updates**: Users can access weather updates for their location by using the `/weather` command.
- **Location Guidance**: The bot guides the user to enter their location.
- **Weather Data**: Utilizing the user's location, the bot fetches weather data from the OpenWeatherMap API.
- **Formatted Message**: The bot sends the user a formatted message containing the following weather information:
  - Weather description (e.g., cloudy, sunny)
  - Temperature (currently in Kelvin)
  - Maximum and minimum temperature (Kelvin)
  - Wind speed (meters per second)
  - Date and time when the weather information was retrieved

## Usage

To use Clima, follow these steps:

1. Start a conversation with the Clima bot on Telegram.
2. Use the `/weather` command to initiate weather updates.
3. Follow the bot's guidance to enter your location. Make sure the entered location spelling is correct.
4. Receive a formatted message with the latest weather information for your location.

## Installation

To run Clima locally or deploy it to your own server, follow these steps:

1. Clone this repository to your local machine.
2. Install the required dependencies using `pip install -r requirements.txt`.
3. Obtain an API key from OpenWeatherMap by signing up at [OpenWeatherMap](https://openweathermap.org/api) and replace `YOUR_API_KEY` in the `config.py` file with your API key.
4. Run the bot using `python Clima_5.py`.

## Output
[Result](https://github.com/DinjanAI/Clima_Weather_bot/assets/159764677/5c335554-1c11-4144-85fa-18197776a904)


