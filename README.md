# backend-service
Technical challenge that collects and stores weather data from OpenWeatherMap API.

Design choices:
    Node.js - quick and intuitive startup
    SQLite for database - quick for local storage, assuming only one user for each application

Weather choices:
    12 hour / 7 day forecasts
    hourly forecasts include temperature and feels like, humidity, UV index, probability of precipitation
