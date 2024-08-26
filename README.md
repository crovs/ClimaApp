# Clouds

Clouds is a simple yet powerful weather app that provides real-time weather updates based on your location or a selected city. This app was built to enhance my understanding of API integration, networking, and Core Location services in iOS development.

## Features

- **Real-Time Weather Data**: Fetches current weather conditions using the OpenWeather API.
- **Location-Based Updates**: Automatically retrieves weather data based on your current location.
- **City Search**: Allows users to search for weather updates in specific cities.
- **User-Friendly Interface**: Clean and intuitive design that supports both light and dark modes.

## Key Learning Objectives

- **API Integration**: Mastered networking with `URLSession` to interact with external APIs and retrieve JSON data.
- **JSON Parsing**: Learned how to parse and utilize JSON data to update the UI dynamically.
- **Core Location**: Implemented Core Location to fetch and use the user's current location for weather updates.
- **Swift Protocols and Delegates**: Used protocols and delegates to manage data flow and UI updates efficiently.
- **Error Handling**: Implemented error handling to manage potential issues like failed network requests.

## Installation

1. Clone the repository.
2. Open the project in Xcode.
3. Install dependencies if any (CocoaPods or Swift Package Manager).
4. Run the app on your preferred device or simulator.

## How It Works

1. **Location Access**: The app requests access to your location to provide weather updates.
2. **Fetching Data**: Clouds uses the OpenWeather API to fetch weather data based on your location or selected city.
3. **Displaying Weather**: The app parses the received JSON data and updates the UI with the latest weather information.

## Future Improvements

- **Hourly and Weekly Forecasts**: Extend the app to provide hourly and weekly weather forecasts.
- **Weather Alerts**: Implement notifications for severe weather alerts.
- **Enhanced UI**: Continue refining the UI for an even better user experience.

## Contributing

Feel free to fork this repository and submit pull requests. Any contributions that improve the app are welcome!

## License

This project is open-source and available under the MIT License.
