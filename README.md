# 🌦️ Weather Forecast API Integration

A simple web-based **API Integration project** developed using HTML, CSS, and JavaScript.

This project demonstrates how a webpage communicates with an external **Weather API** using JavaScript's `fetch()` function, receives JSON data, processes it, and displays the weather information dynamically.

---

## 📌 Project Overview

The application allows users to:

- 🔍 Search for a city
- 📍 Convert the city name into latitude and longitude
- 🌡️ Get the current temperature
- 💧 Get the current humidity
- 💨 Get the current wind speed
- 🔗 View the API request used by the application

The project uses the **Open-Meteo API** for weather data.

---

## 🚀 Features

- 🌍 City-based weather search
- 📍 Latitude and longitude detection
- 🌡️ Temperature display
- 💧 Humidity display
- 💨 Wind speed display
- 🔄 Real-time API requests
- 📦 JSON response processing
- 🛡️ Basic error handling
- 📱 Responsive web design
- 🔎 API request visibility for learning and demonstration

---

## 🔄 API Integration Workflow

```text
User enters city
       ↓
Geocoding API
       ↓
Latitude + Longitude
       ↓
Weather Forecast API
       ↓
HTTP GET Request
       ↓
JSON Response
       ↓
JavaScript processes data
       ↓
Weather displayed on webpage
