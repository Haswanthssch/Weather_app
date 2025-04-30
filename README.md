# 🌤️ React Weather App

This is a simple React application that fetches and displays the **temperature**, **humidity**, and **wind speed** for a specific location using the [OpenWeatherMap API](https://openweathermap.org/api).

---

## 🔧 Features

- Search weather by city name
- Displays:
  - 🌡️ Temperature
  - 💧 Humidity
  - 🌬️ Wind speed
- Clean and responsive UI

---

## 📸 Demo

![App Screenshot](./screenshot.png) <!-- Optional: replace with actual screenshot if available -->

---

## 🚀 Getting Started

### Prerequisites

- Node.js (v14 or higher recommended)
- npm or yarn
- OpenWeatherMap API key (get one for free from https://openweathermap.org/api)

### Installation

1. **Clone the repository:**

```bash
git clone https://github.com/your-username/react-weather-app.git
cd react-weather-app
```

2. **Install dependencies:**

```bash
npm install
# or
yarn install
```

3. **Add your OpenWeather API key:**

Create a `.env` file in the root directory and add:

```
REACT_APP_WEATHER_API_KEY=your_api_key_here
```

4. **Start the app:**

```bash
npm start
# or
yarn start
```

Open [http://localhost:3000](http://localhost:3000) to view it in the browser.

---

## 🧠 How It Works

- When a user enters a city name, the app sends a request to the OpenWeather API.
- The API returns weather data including temperature, humidity, and wind speed.
- These values are extracted and displayed in the UI using React components.

---

## 📁 Project Structure

```
react-weather-app/
│
├── public/
│   └── index.html
├── src/
│   ├── components/
│   │   └── WeatherDisplay.js
│   ├── App.js
│   ├── index.js
│   └── api.js
├── .env
├── package.json
└── README.md
```

---

## 🔐 Environment Variables

| Variable Name             | Description                        |
|--------------------------|------------------------------------|
| REACT_APP_WEATHER_API_KEY | Your OpenWeatherMap API key        |

---

## 📝 License

This project is licensed under the MIT License.

---

## 🙋‍♂️ Questions or Feedback?

Feel free to open an [issue](https://github.com/your-username/react-weather-app/issues) or submit a pull request!
