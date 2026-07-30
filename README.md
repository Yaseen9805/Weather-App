# Weather App

![HTML5](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-ES6-F7DF1E?logo=javascript&logoColor=black)
![OpenWeather API](https://img.shields.io/badge/OpenWeather_API-EB6E4B?logo=openweathermap&logoColor=white)

## Short description

A weather lookup app built with plain HTML, CSS, and JavaScript. Type in a city name and it pulls real-time weather data from the OpenWeather API.

## Technologies

HTML5, CSS3, JavaScript (Fetch API, async/await), OpenWeather API

## Features

- Search current weather by city name
- Displays temperature, humidity, and a short description of conditions
- A dynamic emoji-based icon that changes depending on the weather
- Error handling for invalid or unrecognized city names
- Clean, responsive layout

## The process

The main focus here was working with a real external API rather than static or mock data, so most of the effort went into the fetch/async logic: making the request, waiting on the response, and handling the case where the city entered doesn't return valid data. Using emoji instead of icon images kept the project dependency-free while still giving quick visual feedback on conditions.

## What I learned

- Making asynchronous HTTP requests with the Fetch API and async/await
- Parsing a real-world JSON API response and mapping it to specific UI fields
- Handling API errors and invalid user input gracefully instead of letting the app break
- Keeping an API key in a single, clearly marked place in the code

## How it can be improved

- Move the API key out of the source file and into an environment variable
- Add a Celsius/Fahrenheit toggle
- Show additional data like wind speed and pressure
- Save recent searches so they're easy to look up again

## How to run the project

1. Clone the repo
2. Get a free API key from OpenWeather and add it in `index.js`
3. Open `index.html` directly in your browser
