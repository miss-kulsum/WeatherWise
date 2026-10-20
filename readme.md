```markdown
# WeatherWise Mini Project

A beginner-friendly weather tracker built with plain HTML, CSS and JavaScript. No application server or API key is used. The page requests live data from Open-Meteo.

## Run it

1. Extract the project folder.
2. Open a terminal in this folder.
3. Start a small local static file server:
	```bash
	python -m http.server 8000
	```
4. Visit `http://localhost:8000` in your browser.

A local server makes browser geolocation and API requests work reliably. The browser may ask permission when you choose **Use my location**. City search does not need location permission.

## Features

- Search locations by city name
- Use the browser's current location
- Current weather, feels-like temperature, humidity, wind, rain chance and UV index
- Air-quality index with a plain-language label
- Hourly forecast and seven-day forecast
- Sunrise and sunset times
- Weather-based clothing and activity tips
- Saved cities and recent searches in browser storage
- Celsius/Fahrenheit and light/dark controls
- Responsive layout for phones and desktop screens

## Files

- `index.html` page structure
- `style.css` responsive visual styles
- `app.js` API requests, weather rendering and UI interactions

Weather and air-quality data come from the Open-Meteo Forecast, Geocoding and Air Quality APIs. This demo is an educational project and does not provide official emergency alerts.
```
