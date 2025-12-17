# 🌤️ Weather App

A simple and responsive weather application that allows users to retrieve real-time weather information for any city using the OpenWeather API. The app displays temperature, humidity, weather description, and a visual emoji representing current conditions.

---

## 📌 Features

* Search weather by city name
* Displays:
  - City name
  - Temperature (°F)
  - Humidity
  - Weather description
  - Weather condition emoji
  
* User-friendly error handling for:
  * Empty input
  * Invalid city names
  * Network/API errors
* Clean, responsive UI built with vanilla CSS
* Uses modern JavaScript (ES6+)

---

## 🛠️ Technologies Used

* HTML5 – Structure
* CSS3 – Styling and layout
* JavaScript (ES6+) – Application logic
* OpenWeather API – Real-time weather data

---

## 🚀 How It Works

1. User enters a city name
2. App sends a request to the OpenWeather API
3. Weather data is fetched asynchronously using `fetch`
4. The UI updates dynamically with weather details
5. Errors are gracefully handled and displayed to the user

---

## 📂 Project Structure

```
weather-app/
│
├── index.html        # App structure
├── stylesheet.css    # Styling
├── index.js          # Application logic
└── README.md         # Project documentation
```

---

## ⚙️ Setup & Usage

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/weather-app.git
   ```

2. Open the project folder:

   ```bash
   cd weather-app
   ```

3. Open `index.html` in your browser
   *(No build tools required)*

---

## 🔑 API Key Notice

This project uses the OpenWeather API.

To use your own API key:

1. Sign up at [https://openweathermap.org](https://openweathermap.org)
2. Replace the API key in `index.js`:

   ```js
   const apiKey = "YOUR_API_KEY_HERE";
   ```

---

## 📈 Future Improvements

* Display temperature unit toggle (°C / °F)
* Show wind speed and pressure
* Add loading state
* Improve accessibility (ARIA labels)
* Deploy live version (GitHub Pages)
