# Phase-i-Final-Project-
 # Overview
This repository contains the code for a simple weather application. The application utilizes the OpenWeatherMap API to fetch current weather data based on user input (city name). It then displays the weather information including temperature, weather conditions, and additional details on a webpage.

# Features
Weather Data Retrieval: The application fetches weather data from the OpenWeatherMap API using the provided city name.
Dynamic Background: The background of the webpage changes dynamically based on the current weather conditions such as Clear, Clouds, Rain, Snow, etc.
User Interaction: Users can input a city name and press enter to fetch the weather data for that city.
Error Handling: The application handles various error scenarios such as empty input, invalid city names, and displays appropriate messages to the user.
Components
HTML: Contains the structure of the webpage including input box, weather display area, and placeholders for weather information.
CSS: Provides styles for the webpage elements to improve visual appeal and layout.
JavaScript:
Weather API Configuration: Defines an object weatherApi containing the API key and base URL for accessing weather data.
Event Listener: Listens for keypress events on the input box and triggers a function to fetch weather data when the enter key is pressed.
Fetch Function: Fetches weather data from the OpenWeatherMap API using the provided city name and API key.
Display Function: Renders the retrieved weather data on the webpage including location, temperature, weather conditions, and additional details.
Utility Functions: Includes functions for date management, background image selection, and icon class determination.
Error Handling: Manages various error scenarios such as empty input and invalid city names, displaying appropriate messages using SweetAlert library.
Reset Function: Clears the input box after fetching weather data.
# Usage
To use this weather application:

Clone the repository to your local machine.
Open the index.html file in a web browser.
Enter the name of the city for which you want to fetch weather information.
Press enter, and the weather details will be displayed on the webpage.
Dependencies
OpenWeatherMap API: This application relies on the OpenWeatherMap API to fetch weather data. You need to sign up for an API key to use this service.
SweetAlert Library: The application utilizes SweetAlert library for displaying error messages in a user-friendly manner.
# Credits
This project is developed by Patrick Njuguna and is licensed under the MIT license. Feel free to contribute to the project by submitting pull requests or reporting issues.

