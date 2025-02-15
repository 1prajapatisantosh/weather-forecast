# weather-forecast

This project is a weather forecast application created using HTML, CSS, and JavaScript. It fetches weather data from a third-party API and displays the current weather conditions, as well as a 7-day forecast for any specified location.


Features:

Real-time Weather Data: Displays current weather conditions including temperature, humidity, wind speed, and weather description.

7-Day Forecast: Provides a detailed 7-day weather forecast with daily temperature highs and lows, weather conditions, and icons.

Responsive Design: Adjusts smoothly to different screen sizes, ensuring a good user experience on mobile, tablet, and desktop devices.

Search Functionality: Allows users to search for weather information by city name.


API Integration: Fetches data from a weather API (such as OpenWeatherMap).

Technologies Used

HTML5: For structuring the web page content.

CSS3: For styling the web page, including Flexbox and Grid for layout, and media queries for responsiveness.

JavaScript: For handling API requests, processing data, and updating the DOM dynamically

Weather API: Fetches weather data (e.g., OpenWeatherMap API).


Screenshots


Usage

To view the project locally, follow these steps:



Clone the repository:

git clone (copy github link)

Navigate to the project directory:

cd (filename)

Open index.html in your preferred web browser:

open index.html

Configuration

API Key: You need to obtain an API key from the weather service provider (e.g., OpenWeatherMap).

API Endpoint: Update the API endpoint and API key in the JavaScript file:

javascript

const apiKey = 'YOUR_API_KEY';

const apiUrl = `https://api.openweathermap.org/data/2.5/weather?q=YOUR_CITY&appid=${apiKey}`;


Contributing

Contributions are welcome! If you have any ideas or suggestions to improve this project, please feel free to submit a pull request or open an issue.
