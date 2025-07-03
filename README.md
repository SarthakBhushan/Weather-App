# Weather-App
# 🌦️ Java Swing Weather App

A simple desktop GUI application built with **Java Swing** that displays real-time weather data using an **external weather API**. Designed for a clean and minimal user experience.

---

## 🚀 Features

- 🌍 Search weather by city name
- ☁️ Displays temperature, humidity, wind speed, and weather description
- 🌡️ Real-time data from external weather API (e.g., OpenWeatherMap)
- 🖥️ Built using Java Swing for desktop GUI
- 🔁 Refresh weather with one click
- 🧪 Error handling for invalid inputs or API issues

---

## 🧰 Technologies Used

- Java (JDK 8+)
- Java Swing (GUI)
- JSON Parsing using `org.json` or `Gson`
- External Weather API (e.g., OpenWeatherMap)

---

## 🌐 External API

Using **OpenWeatherMap API**:
- API Endpoint: `https://api.openweathermap.org/data/2.5/weather?q={city}&appid={API_KEY}&units=metric`

Sign up at [https://openweathermap.org/api](https://openweathermap.org/api) to get a free API key.

---

## 🖥️ How It Works

1. User enters a city name in the input field.
2. App makes a GET request to the weather API.
3. API response is parsed and displayed in the GUI:
   - Temperature (°C)
   - Weather Description (e.g., Clear, Rain)
   - Humidity (%)
   - Wind Speed (m/s)

---

## ⚙️ How to Run

1. Clone or download the repository.
2. Open the project in any Java IDE (e.g., IntelliJ, Eclipse).
3. Make sure to replace `YOUR_API_KEY_HERE` in the code with your actual API key.
4. Compile and run the main class:
```bash
javac WeatherApp.java
java WeatherApp
```

---

## 📁 Project Structure

```
WeatherApp/
├── WeatherApp.java
├── WeatherService.java
├── utils/
│   └── JsonParser.java
└── README.txt
```

---

## 🛠 Future Improvements

- 🌍 Support for location-based weather using IP
- 🕒 5-day forecast
- 📱 Convert to Android version
- 🌈 Add themes or light/dark mode toggle

---

## 🙏 Acknowledgments

- [OpenWeatherMap API](https://openweathermap.org/)
- Java Swing community and documentation
