# Weather App

This is a simple minimalistic weather application demonstrating how to fetch
weather data for a given city. It uses Express.js on the backend and the
OpenWeatherMap API for data.

## Features
- Query temperature and humidity for any city
- Displays weather icon and description
- Embedded interactive 3D globe (via globe.gl)
- Basic responsive layout with modern design

## Usage
Install dependencies and start the server:

```bash
npm install
node server.js
```

Set `OPENWEATHER_API_KEY` environment variable to a valid API key to retrieve
data from OpenWeatherMap.
