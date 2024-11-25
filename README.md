# Weather App

This Weather App allows users to get real-time weather data by entering the name of a city. It fetches the weather information from the OpenWeather API and displays it, including the temperature, humidity, and wind speed.

## Features

- Search for any city to get the latest weather data.
- Displays weather information such as:
  - Temperature
  - Location name
  - Humidity
  - Wind Speed
- Provides different weather icons based on weather conditions (e.g., clear, rain, snow).

## Technologies Used

- **React**: The app is built using React for UI components.
- **Vite**: The project is scaffolded with Vite for faster development and lightweight builds.
- **OpenWeather API**: The weather data is fetched from the [OpenWeather API](https://openweathermap.org/).

## Installation

To set up this project locally, follow these steps:

1. **Clone the repository**:
    ```bash
    git clone https://github.com/Beexoul/weather-app.git
    cd weather-app
    ```

2. **Install dependencies**:
    ```bash
    npm install
    ```

3. **Set up API key**:
   - Sign up for a free API key at [OpenWeather API](https://openweathermap.org/appid).
   - Create a `.env` file in the root directory of the project and add your API key:
     ```
     VITE_APP_ID=your_openweather_api_key
     ```

4. **Run the app**:
    ```bash
    npm run dev
    ```

5. **Build for production**:
    ```bash
    npm run build
    ```

## Usage

1. Open the app.
2. By default, the weather for "Butwal" is displayed.
3. To search for weather in a different city, type the city name in the search bar and click the search icon.

## Folder Structure
```
|
├── public/
├── src/
│   ├── assets/
│   |    ├── search.png
│   |    ├── clear.png
│   |    ├── cloud.png
│   |    ├── drizzle.png
│   |    ├── rain.png
│   |    ├── snow.png
│   |    ├── wind.png
│   |    └── humidity.png
│   ├── components/
|   |   ├── Weather.css
│   │   └── Weather.jsx
|   ├── App.css
│   ├── App.jsx
│   ├── main.jsx
│   └── index.css
├── .env
├── eslint.config.js
├── index.html
├── package-lock.json
├── package.json
├── README.md
└── vite.config.js
```

- **src/components**: Contains the Weather component, which is responsible for fetching and displaying weather data.
- **src/assets**: Stores static assets like weather icons (clear, rain, cloud, etc.).
- **public**: Contains static files like the `favicon.ico` and `index.html`.
- **node_modules**: Contains the project's dependencies.
  
## License

This project is open-source and available under the [MIT License](LICENSE).

---
