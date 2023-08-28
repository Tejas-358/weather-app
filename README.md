# Weather App

A simple weather app that allows users to check the weather for a specific city.

![Weather App Screenshot](screenshot.png)

## Features

- Users can enter the name of a city to get the current weather information.
- Displays temperature, humidity, and wind speed.
- Weather icon changes based on the current weather conditions.

## Technologies Used

- HTML
- CSS
- JavaScript

## How to Use

1. Clone the repository: `git clone https://github.com/Tejas-358/weather-app.git`
2. Open `index.html` in your web browser.
3. Enter the name of a city in the search bar and click the search button.
4. The weather information will be displayed.

## API Usage

This app uses the OpenWeatherMap API to fetch weather data based on the user's input city.

To use the app, you need to provide your own API key. Sign up for a free API key from https://openweathermap.org/api and replace `your-api-key` in `script.js` with your actual API key.

```javascript
const apiKey = "your-api-key";
