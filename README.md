# 🌤 WeatherMappr - Weather Forecast App

WeatherMappr is a simple, clean web application that displays **daily weather forecasts** using the [Tomorrow.io Weather API](https://www.tomorrow.io/weather-api/). Users can search by **city name** or use their **current location** to get weather conditions including temperature and description.

## 🚀 Features

- 📍 Get weather forecast using **your current location**
- 🔎 Search weather by **city name**
- 🔁 Uses **Tomorrow.io API** for daily weather forecast
- 🗺️ Converts city names to coordinates using **OpenStreetMap (Nominatim)**
- 🌦️ Displays:
  - Max Temperature
  - Weather Condition (Clear, Rain, Snow, etc.)

## 🧑‍💻 Tech Stack

- HTML
- CSS
- JavaScript (Vanilla)
- Tomorrow.io REST API (Forecast endpoint)
- OpenStreetMap Nominatim API (Geocoding)

## 🔑 API Information

**Tomorrow.io API Key used:**

```
Q9MuMI77qiswrcBeXORiuAjmkjwfRZlj
```

## 📁 Project Structure

```
/TomorrowCast/
├── index.html        # Main single-page app
└── README.md         # Project documentation
```

## 🛠 How to Run

1. Clone or download this repository.
2. Open `index.html` in your browser.
3. Enter a city or click **"Use My Location"**.
4. View the weather forecast.

## 🌐 API Endpoints Used

- **Tomorrow.io Forecast API**  
  `https://api.tomorrow.io/v4/weather/forecast?location=LAT,LON&apikey=YOUR_API_KEY`

- **OpenStreetMap Geocoding**  
  `https://nominatim.openstreetmap.org/search?format=json&q=CITY_NAME`

## 🧠 Future Improvements

- [ ] Add hourly and 7-day forecast
- [ ] Add weather icons and illustrations
- [ ] Make UI fully responsive
- [ ] Cache results for repeated lookups
- [ ] Use a secure proxy backend for API key protection

## 📝 License

This project is licensed under the **MIT License**.  
Built with ❤️ using [Tomorrow.io](https://www.tomorrow.io/) and OpenStreetMap.
