# Futuristic Weather App 🌤️

A fully responsive, visually stunning weather application that shows real-time weather updates for any location, including your current location. The app features smooth day/night transitions, animated weather conditions, and automatic updates as you move to different locations.

---

## Features

- **Current Weather:** Displays temperature, humidity, wind speed, pressure, and weather description.
- **Hourly Forecast:** Shows a 12-hour forecast with animated icons.
- **Location Detection:** Automatically fetches weather for your current location using the browser’s geolocation API.
- **Auto-Update on Travel:** Tracks your movement and updates the weather automatically if you travel to a new location.
- **Dynamic Background:** Smoothly transitions from sunrise → day → sunset → night with animated sky elements (sun, moon, stars, clouds).
- **Weather Animations:** Uses Lottie animations for clear, cloudy, rainy, snowy, misty, and thunder conditions.
- **Particle Effects:** Realistic raindrops, snowflakes, and mist/fog effects on the canvas.
- **Set Default Location:** Save a preferred location for quick access.

---

## Technologies Used

- HTML5, CSS3, JavaScript (ES6+)
- [OpenWeatherMap API](https://openweathermap.org/api)
- [Lottie Animations](https://lottiefiles.com)
- Canvas API for particle effects
- LocalStorage for saving default location

---

## Page live at
https://subh0220.github.io/Weather-Forecast/

---

## How to Use

1. Clone the repository:
- git clone https://github.com/YourUsername/Weather-App.git
2. Open index.html in your browser.
3. Enter a city name or click the location button to get your current weather.
4. Use the "Set Default Location" button to save your preferred location.
5. The app will automatically update weather based on your movements every 10 minutes.

---

## Notes

- Make sure to replace OPENWEATHER_API_KEY in script.js with your own OpenWeatherMap API key.
- Requires HTTPS for geolocation access in most browsers.

---

## License
This project is open-source and free to use.
