# SkyCast Weather App

A responsive weather dashboard built with **React, HTML, CSS, and JavaScript** using Vite.

## Features
- Search for cities worldwide
- Current weather, feels-like temperature, humidity, wind, and precipitation
- Hourly forecast and 7-day forecast
- Celsius / Fahrenheit toggle
- Optional browser geolocation
- Responsive layout for desktop and mobile
- Weather condition icons
- Live weather data from the free Open-Meteo API (no API key required)

## Requirements
- Node.js 18+ recommended
- Internet connection for weather data

## Run locally
1. Extract the ZIP file.
2. Open the extracted `weather_app` folder in VS Code.
3. Open a terminal in that folder.
4. Install dependencies:
   ```bash
   npm install
   ```
5. Start the development server:
   ```bash
   npm run dev
   ```
6. Open the local URL shown in the terminal (usually `http://localhost:5173`).

## Build for production
```bash
npm run build
npm run preview
```

## Project structure
```text
weather_app/
├── index.html
├── package.json
├── README.md
└── src/
    ├── App.jsx
    ├── main.jsx
    └── styles.css
```

Weather data is provided by [Open-Meteo](https://open-meteo.com/). City search uses its geocoding endpoint. The app requires internet access to fetch weather information.
