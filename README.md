
# 🌦️ Weather App

A simple and elegant weather web application built using **HTML**, **CSS**, and **JavaScript**. This app fetches real-time weather data for any city using the **OpenWeatherMap API**, and dynamically updates the UI with weather information, icons, and background images based on the weather condition.

Web link
:-
https://ayushiverma309.github.io/weatherwebapp/



## 🚀 Features

- 🌍 Get real-time weather by entering any city name
- 📅 Displays current date and time
- 🌡️ Shows temperature, weather status, min/max temperature
- 💨 Displays humidity, pressure, wind speed
- 🎨 Changes background dynamically based on weather conditions
- ⚠️ Alerts for invalid or empty input using SweetAlert

## 🛠️ Tech Stack

- **Frontend**: HTML, CSS, JavaScript
- **API**: [OpenWeatherMap](https://openweathermap.org/api)
- **Libraries/CDNs**:
  - Font Awesome for weather icons
  - SweetAlert for alert popups

## 📂 Project Structure

```
weather-app/
├── index.html           # Main HTML structure
├── style.css            # All styling here
├── script.js            # App logic and API calls
├── img/                 # Folder containing background images
│   ├── bg.jpg
│   ├── bg1.jpg
│   ├── clear.jpg
│   ├── clouds.jpg
│   ├── drizzle.jpg
│   ├── mist.jpg
│   ├── rainy.jpg
│   ├── snow.jpg
│   ├── sunny.jpg
│   └── thunderstrom.jpg
```

## ⚙️ Setup Instructions

1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/weather-app.git
   ```

2. Navigate to the project directory:
   ```bash
   cd weather-app
   ```

3. Open `index.html` in your browser to run the app locally.

> ✅ Make sure you have a stable internet connection to fetch data and use the CDN libraries.

## 🔑 Get Your API Key

1. Go to [OpenWeatherMap](https://openweathermap.org/api)
2. Sign up and generate a free API key
3. Replace the existing `key` in `script.js` with your own:
   ```javascript
   const weatherApi = {
       key: '4eb3703790b356562054106543b748b2',
       baseUrl: 'https://api.openweathermap.org/data/2.5/weather'
   }
   ```


## 💡 Future Enhancements

- Add support for multi-day forecast
- Use geolocation for weather by current location
- Improve mobile responsiveness
- Add loading indicators

## 🙌 Acknowledgements

- [OpenWeatherMap API](https://openweathermap.org/api)
- [Font Awesome](https://fontawesome.com/)
- [SweetAlert](https://sweetalert.js.org/)

---


