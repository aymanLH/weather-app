# Weather App

A simple and clean weather application that displays current weather conditions for any city worldwide.

## ✨ Features

- Real-time weather data
- City search functionality
- Current temperature display
- Humidity and wind speed information
- Dynamic weather icons based on conditions
- Error handling for invalid city names
- Responsive design

## 🛠️ Technology Stack

- HTML5
- CSS3
- Vanilla JavaScript
- OpenWeatherMap API

## 📦 Project Structure

```
weather-app/
├── index.html          # Main HTML file
├── weather.css         # Stylesheet
├── favicon.png         # Site favicon
├── isearch1.png        # Search button icon
├── clear.png           # Clear weather icon
├── clouds.png          # Cloudy weather icon
├── drizzle.png         # Drizzle weather icon
├── humidity.png        # Humidity indicator icon
├── mist.png            # Mist weather icon
├── rain.png            # Rain weather icon
├── snow.png            # Snow weather icon
├── wind.png            # Wind indicator icon
└── sky.jpg             # Background image
```

## 🚀 Getting Started

### Prerequisites

- Web browser
- OpenWeatherMap API key

### Installation

1. Clone the repository
```bash
git clone https://github.com/username/weather-app.git
cd weather-app
```

2. Open `index.html` in the script section and replace the API key
```javascript
const apiKey = "YOUR_API_KEY_HERE";
```

3. Open `index.html` in your browser

### Getting an API Key

1. Visit [OpenWeatherMap](https://openweathermap.org/api)
2. Sign up for a free account
3. Generate your API key
4. Replace the placeholder in the code

## 🎯 Usage

1. Enter a city name in the search box
2. Click the search button
3. View current weather information:
   - Temperature (°C)
   - Humidity (%)
   - Wind Speed (km/h)
   - Weather condition icon

## 🌤️ Supported Weather Conditions

- Clear
- Clouds
- Rain
- Drizzle
- Mist
- Snow

## 📝 API Reference

**Endpoint**: `https://api.openweathermap.org/data/2.5/weather`

**Parameters**:
- `q`: City name
- `units`: metric (Celsius)
- `appid`: Your API key

## 🔒 Security Note

For production applications, never expose your API key in client-side code. Consider using a backend proxy to secure your API key.

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch
3. Commit your changes
4. Push to the branch
5. Open a Pull Request

## 📄 License

This project is open source and available under the MIT License.

## 🐛 Known Issues

- API key is exposed in client-side code
- Limited to current weather data only

## 🔮 Future Enhancements

- 5-day forecast
- Geolocation support
- Temperature unit toggle (°C/°F)
- Multiple city comparison
- Weather alerts
- Backend API proxy for key security