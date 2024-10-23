
# Weather Data Collection and Analysis System

This Weather Data Collection and Analysis App retrieves real-time weather data from an API, providing detailed metrics like temperature, humidity, and wind speed. It includes features for daily summaries, trend analysis, and alerts based on user-defined thresholds. The app presents the data visually, enabling users to monitor and analyze weather conditions effectively.


## Features

- Real-Time Weather Updates: Fetches up-to-date weather data for multiple cities, displaying metrics like temperature, humidity, and wind speed.
- Temperature Unit Conversion: Allows users to view temperatures in Celsius, Fahrenheit, or Kelvin.
- Weather Forecast: Provides a 5-day forecast with detailed hourly updates.
- Additional Parameters: Supports retrieval and analysis of additional weather parameters such as humidity and wind speed.



## Prerequisites

To build and run this project locally, you need:

- Node.js (v14.0 or above)
- npm (Node Package Manager)
- API Key: An OpenWeatherMap API key (Sign up here for an API key)

## Design Choices

- Real-Time Data: Utilized OpenWeatherMap API to provide live weather updates and forecasts, ensuring accurate, up-to-date information for users.
- Responsive UI: Implemented a fully responsive user interface with a dynamic background video for visual engagement, enhancing the user experience across different devices.
- Temperature Unit Conversion: Integrated a dropdown menu to allow seamless switching between Celsius, Fahrenheit, and Kelvin, offering flexibility based on user preference.
- User Input-Based Search: Designed the system to allow users to search for weather data based on any city, ensuring flexibility in monitoring weather conditions globally.
- Minimalist and Clear Layout: The UI design focused on simplicity and ease of navigation, with cards and charts clearly presenting relevant weather data in a clean, organized format.
## Build Instructions

#### Clone the Repository

```bash
    git clone https://github.com/GargiRajput/Zeotap_WeatherApp.git
    cd Zeotap_weather_app
```
#### Install Dependencies
```bash
    npm install
```
#### Start the Application
```bash
    npm start
```

