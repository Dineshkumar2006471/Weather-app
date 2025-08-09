
# 🌦 Weather App API

This is a Node.js-based Weather App API that fetches current weather information using the [OpenWeatherMap API](https://openweathermap.org/api). It is built using Express.js and Axios, and provides weather data for user-input locations.

## 🚀 Features

- Get real-time weather updates for any city.
- Uses OpenWeatherMap API for accurate and up-to-date data.
- Secure API key management with .env file.
- Clean and modular folder structure (MVC-style).

## 🛠 Tech Stack

- *Backend:* Node.js, Express.js
- *HTTP Client:* Axios
- *Environment Management:* dotenv
- *Template Engine:* (if used) EJS / Handlebars / etc.

## 📁 Project Structure

weather-app-API/ │ ├── apps/                 # Main application logic ├── public/               # Static files (CSS, JS, images) ├── views/                # Frontend templates (if applicable) ├── node_modules/         # Dependencies ├── .env                  # API key (ignored in Git) ├── package.json          # Project metadata and dependencies └── server.js / app.js    # Entry point

## 🌐 API Endpoint

GET /weather?city=London

### Example Response:
```json
{
  "location": "London",
  "temperature": "18°C",
  "description": "Clear Sky",
  "humidity": "70%",
  "windSpeed": "12 km/h"
}

🧪 How to Run Locally

1. Clone the repo

git clone https://github.com/Dineshkumar2005k7/weather-app-API.git
cd weather-app-API


2. Install dependencies

npm install


3. Set up .env file Create a .env file in the root directory and add your OpenWeatherMap API key:

WEATHER_API_KEY=your_openweathermap_api_key


4. Start the server

node app.js


5. Open your browser or Postman and test the API:

http://localhost:3000/weather?city=London



📦 Deployment

This app can be easily deployed using:

Render

Vercel (for front-end)

Railway

Heroku

GitHub Pages (only for front-end if any)


🔒 Security Note

Ensure your .env file is added to .gitignore to avoid exposing your API key.

✨ Contributions

Feel free to fork the repo, make changes, and create pull requests. Contributions are welcome!