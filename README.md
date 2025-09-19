# ABC Weather Dashboard

A clean, responsive weather application that provides current weather conditions and 5-day forecasts for any city worldwide.

## Features

- **Current Weather Display**: Shows temperature, weather conditions, and location
- **5-Day Forecast**: Extended weather outlook with daily summaries
- **City Search**: Search for weather data by city name
- **Responsive Design**: Works seamlessly on desktop and mobile devices
- **Weather Icons**: Dynamic icons that change based on weather conditions
- **Loading States**: Visual feedback during data fetching
- **Error Handling**: User-friendly error messages for invalid searches

## Technologies Used

- **HTML5**: Semantic markup structure
- **CSS3**: Styling and responsive design
- **JavaScript (ES6+)**: Interactive functionality and API integration
- **OpenWeatherMap API**: Weather data source
- **Font Awesome**: Weather and UI icons

## Getting Started

### Prerequisites

- A modern web browser
- OpenWeatherMap API key (free registration required)

### Setup

1. **Clone or download** this repository to your local machine

2. **Get an API key**:
   - Visit [OpenWeatherMap](https://openweathermap.org/api)
   - Sign up for a free account
   - Generate an API key

3. **Configure the API key**:
   - Open `src/js/main.js`
   - Replace the placeholder API key on line 3:
     ```javascript
     const apiKey = 'YOUR_API_KEY_HERE';
     ```

4. **Launch the application**:
   - Open `public/index.html` in your web browser
   - Or serve the files using a local web server

## Project Structure

```
├── public/
│   └── index.html     
├── src/
│   ├── css/              
│   └── js/
│       └── main.js     
└── README.md          
```

## Usage

1. **Default Location**: The app loads with weather data for Pondicherry by default
2. **Search**: Enter any city name in the search box and press Enter or click the search button
3. **View Results**: Current weather and 5-day forecast will display after a brief loading period

## API Integration

This application uses the OpenWeatherMap API with two endpoints:

- **Current Weather**: `https://api.openweathermap.org/data/2.5/weather`
- **5-Day Forecast**: `https://api.openweathermap.org/data/2.5/forecast`

Both endpoints use metric units (Celsius) and require a valid API key.

