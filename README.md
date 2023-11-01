# Weather App

This is a simple web-based Weather App that allows users to search for weather information by location. It uses the OpenWeatherMap API to fetch weather data based on the city name entered by the user.

## Features

- Allows users to enter a location and retrieve weather information.
- Provides weather details such as temperature, description, humidity, and wind speed.
- Displays weather icons based on the current weather conditions (e.g., clear, rain, snow, cloud, haze).
- Handles errors gracefully and shows a message when an invalid location is entered.

## Live Demo

You can try the Weather App by following this [Live Demo Link](https://alejandrov074.github.io/Clima-app/).

## Usage

To use the Weather App, follow these steps:

1. Open the HTML file (`index.html`) in your web browser.
2. Enter a city name in the search box and click the search button.
3. The app will make an API request to OpenWeatherMap and display weather information.

## Code Structure

- `index.js`: This JavaScript file contains the code for fetching weather data and updating the user interface based on the response.

- `index.html`: The HTML file defines the structure of the web page, including input fields, weather details, and error messages. It also links to the JavaScript file and includes the Font Awesome icon library.

- `style.css`: The CSS file provides the styling for the application. It sets the layout, fonts, colors, and animations to create an appealing user interface.

## Dependencies

- [Font Awesome](https://fontawesome.com/): This project uses Font Awesome for icons.

## API Key

You will need an API key from OpenWeatherMap to use this application. Update the `APIkey` variable in `index.js` with your API key for the app to work.

## Author

Alejandro Vargas

## Acknowledgments

This Weather App is a simple and useful project for displaying weather information. It demonstrates how to make API requests and handle responses in a web application. Feel free to customize and expand upon it as needed.
