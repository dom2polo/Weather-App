---
Weather App
---

# Overview

This Weather App is a simple web application that allows users to check the weather conditions for a specified location (city or state). The app fetches real-time weather data using the OpenWeatherMap API and displays it in an intuitive user interface.

## Features

- User-friendly interface for entering the location (city or state).
- Displays temperature, humidity, and wind information.
- Utilizes the OpenWeatherMap API for accurate and up-to-date weather data.

## Technologies Used

- HTML
- CSS
- JavaScript
- OpenWeatherMap API
- Google Maps API

## Getting Started

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/weather-app.git
   ```
2. Open the index.html file in your preferred web browser.

3. Enter the desired location (city or state) in the input field.

4. Click the "search" button to fetch and display weather information.
   
## How to Use
On the main page, you will find an input field for entering the location.

After entering the location, click the "search" button.

The app will display the current temperature, humidity, and wind information for the specified location.

## API Configuration
To use the OpenWeatherMap API, you will need to sign up for an API key. Replace YOUR_API_KEY in the app.js file with your actual API key.

```javascript
const apiKey = 'YOUR_API_KEY';
const apiUrl = 'https://api.openweathermap.org/data/2.5/weather';
```

Credits
OpenWeatherMap API: [OpenWeatherMap](https://openweathermap.org/)
Google Maps API: [Google Maps Platform](https://developers.google.com/maps)

License
This project is licensed under the MIT License - see the LICENSE.md file for details.
