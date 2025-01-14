# Weather App

A modern weather application built with Node.js and Express that provides real-time weather information using the OpenWeather API.

## Features

- Real-time weather data from OpenWeather API
- Clean and modern user interface
- Displays temperature, feels like temperature, humidity, and wind speed
- Responsive design that works on all devices
- Dynamic weather icons based on conditions
- Smooth animations and transitions

## Technologies Used

- Frontend:
  - HTML5
  - CSS3 (with animations)
  - JavaScript (ES6+)
  - Font Awesome icons
  - Google Fonts (Poppins)

- Backend:
  - Node.js
  - Express.js
  - OpenWeather API

## Setup

1. Clone the repository:
   ```bash
   git clone [your-repo-url]
   cd weather
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

3. Create a `.env` file in the backend directory and add your OpenWeather API key:
   ```
   OPENWEATHER_API_KEY=your_api_key_here
   ```

4. Start the server:
   ```bash
   npm start
   ```

5. Open `frontend/index.html` in your browser or use a local server to serve the frontend files.

## Usage

1. Enter a city name in the search box
2. Press Enter or click the Search button
3. View the current weather information for the specified city

## API Reference

The app uses the OpenWeather API to fetch weather data. You'll need to sign up for a free API key at [OpenWeather](https://openweathermap.org/api).

## Contributing

Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

## License

[MIT](https://choosealicense.com/licenses/mit/)
