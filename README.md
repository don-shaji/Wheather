Dynamic Weather Dashboard

Overview

This is a Dynamic Weather Dashboard built with HTML, CSS, and JavaScript. It provides real-time weather information for any city using the OpenWeatherMap API. The dashboard features a visually appealing interface with dynamic background themes, weather animations, and a responsive design that adapts to different weather conditions.

Features

Search Functionality: Users can search for weather data by entering a city name, with autocomplete suggestions powered by the OpenWeatherMap Geocoding API.
Real-Time Weather Data: Displays temperature, "feels like" temperature, humidity, wind speed, pressure, and weather description for the searched city.
Dynamic Themes: The background and animations change based on the current weather condition (e.g., sunny, rainy, snowy, cloudy, etc.).
Weather Animations: Includes animated effects like clouds, sun rays, raindrops, snowflakes, and lightning to enhance the visual experience.
Responsive Design: Optimized for both desktop and mobile devices with a clean, modern layout.
Error Handling: Shows error messages for invalid city names or API failures.
Auto-Refresh: Updates weather data every 5 minutes if a city is selected.

File Structure

index.html: The main (and only) file containing the HTML structure, embedded CSS styles, and JavaScript logic.
Technologies Used
HTML5: For the structure of the dashboard.
CSS3: For styling, animations, and dynamic themes (embedded in <style> tags).
JavaScript: For API integration, DOM manipulation, and interactivity (embedded in <script> tags).
OpenWeatherMap API: Provides weather data (weather endpoint) and city suggestions (geo endpoint).

How It Works

API Integration:
Uses the OpenWeatherMap API with a provided API key (e28bfa8175cca343995da33921cc4dd1).
Fetches weather data via the /weather endpoint and city suggestions via the /geo endpoint.
Dynamic UI:
The search input triggers city suggestions as the user types.
Upon selecting a city or pressing "Search" (or Enter), the app fetches and displays weather data.
The background theme and animations update based on the weather condition (e.g., "Clear", "Rain", "Snow").

Animations:

CSS keyframes animate clouds, sun rays, raindrops, snowflakes, and lightning effects across the screen.

Notes

API Key: The current API key is hardcoded in the script. For production use, consider securing it (e.g., via environment variables or a backend proxy).
Dependencies: No external libraries are required; everything is self-contained in index.html.
Browser Compatibility: Works best in modern browsers supporting CSS animations and ES6 JavaScript.
