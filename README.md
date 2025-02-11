
This is a simple weather application that allows users to search for the current weather of any city around the world. It fetches weather data from the OpenWeatherMap API and displays information like temperature, humidity, wind speed, and an icon representing the weather condition.

**Features**

Search for the weather by city name.

Displays current temperature in Celsius.

Shows weather icon corresponding to conditions (e.g., Rain, Clouds, Clear, etc.).

Provides additional weather information like humidity and wind speed.

Displays an error message if the city name is invalid.

**Technologies Used**

HTML

CSS

JavaScript

OpenWeatherMap API (for weather data)

**How to Use**

Clone or download the repository.

Open index.html in your browser.

Enter a city name in the input box and click the search button.

The weather information will appear below.

**File Structure**

├── index.html        # Main HTML file

├── style.css         # Styles for the app

├── index.js          # JavaScript for app logic

└── images/           # Folder for weather icons (e.g., rain.png, cloud.png)

**API Key**

This app uses the OpenWeatherMap API. You can get your own API key by signing up at OpenWeatherMap. Replace the apiKey in the index.js file with your own key.

const apiKey = "your_api_key_here";
