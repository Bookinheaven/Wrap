# 🌦️ Wrap - Interactive Weather Dashboard

**Wrap** is a beautiful, real-time, interactive weather dashboard built with **React**, **MapLibre GL JS**, and the **OpenWeatherMap API**. It provides current weather data, 5-day forecasts, location-based search, map interactions, and network awareness — all in a responsive and user-friendly UI.

![Screenshot of App](./Screenshots/intro.png)

---
## ✨ Features

* 🔍 **Smart City Search**
  Instantly search any city worldwide to view current weather conditions and a 5-day hourly forecast.

* 🌍 **Interactive Map Click**
  Click anywhere on the global map to fetch localized weather data for that precise location — no typing needed.

* 📍 **Auto-Detect Location**
  Get weather details for your current location using browser geolocation (with user permission).

* 📅 **5-Day Forecast Visualization**
  See upcoming weather trends grouped by date with hourly breakdowns, temperature, and condition icons.

* 🧠 **Recent City History**
  Automatically remembers your last 5 searched cities using `localStorage` — quick access without typing again.

* 🌙 **Dark Mode Friendly**
  Supports a dark theme out of the box for better readability in low-light environments.

* 📶 **Real-Time Network Detection**
  Detects and notifies you when you go offline or come back online — perfect for unstable connections.

* 📱 **Fully Responsive UI**
  Built with a mobile-first approach — works seamlessly across desktops, tablets, and smartphones.

---

## 🧱 Built With

| Tech        | Description                         |
|-------------|-------------------------------------|
| React       | Frontend Framework                  |
| MapLibre GL | Open-source mapping library         |
| OpenWeatherMap API | Weather data (Current + Forecast) |
| OpenCage API       | Geocoding (City to Lat/Lng)   |
| CSS         | Custom styles, transitions, layout  |

---

## 📸 Screenshots

### 🔍 City Search (Andhra Pradesh, India)
![City Search](./Screenshots/1.png)

### 🌍 Global Map Click (Mutum Biyu, Nigeria)
![Map Click](./Screenshots/2.png)

### 📱 Responsive Mode (Tall Daghash, Iraq)
![Responsive Weather](./Screenshots/3.png)

### 🚫 Offline Mode
![Offline Banner](./Screenshots/4.png)

### ✅ Back Online
![Online Banner](./Screenshots/5.png)

---

## 🚀 Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/Bookinheaven/Wrap.git
cd Wrap
````

### 2. Install Dependencies

```bash
npm install
```

### 3. Setup Environment Variables

Create a `.env` file in the root directory with the following keys:

```env
VITE_WEATHER_API_KEY=your_openweathermap_api_key
VITE_WEATHER_GEOCAGE_KEY=your_opencage_api_key
```

### 4. Run the App

```bash
npm run dev
```

Your app will be available at `http://localhost:5173`.


---

## 📌 To-Do & Enhancements

* [ ] Toggle °C / °F support
* [ ] Add weather icon animations
* [ ] Show weather cards for recent cities
* [ ] Unit tests for utility functions
* [ ] Light/Dark mode toggle UI

---

## 🌐 APIs Used

* [OpenWeatherMap](https://openweathermap.org/api)
* [OpenCage Geocoding](https://opencagedata.com/api)
* [MapLibre GL JS](https://maplibre.org/)

---

## 💬 Feedback or Contributions?

Feel free to open issues or pull requests if you’d like to contribute, report bugs, or suggest improvements.

---
