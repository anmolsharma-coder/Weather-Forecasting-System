![Application screenshot](./public/screenshot.png)

<br/>
<br/>

🌦️ Weather Forecasting Application

The Weather Forecasting Application allows users to search weather information by city name and view detailed forecasts for the next 5–6 days with 3-hour interval data.
The application is built using React.js and Material-UI, providing a modern, responsive user interface.

🚀 Features

🔍 Search weather by city name

📅 5–6 day weather forecast

⏱️ 3-hour interval weather updates

🌡️ Displays temperature, humidity, wind speed, and weather conditions

🎨 Responsive UI using Material-UI

⚠️ Error handling for invalid locations

💻 Live Demo

🔗 Live Application:
https://the-weather-forecasting.netlify.app

🛠️ Tech Stack

Frontend: React.js

UI Library: Material-UI

Languages: JavaScript, HTML, CSS

API: OpenWeatherMap API

✨ Getting Started

Follow the steps below to run the project locally.

✅ Prerequisites

Node.js

npm

OpenWeatherMap API Key

⚙️ Installation
1️⃣ Clone the Repository
git clone [[https://github.com/Anmol-Sharma/Weather-Forecasting-System.git]](https://github.com/anmolsharma-coder/Weather-Forecasting-System)

2️⃣ Navigate to Project Directory
cd the-weather-forecasting

3️⃣ Install Dependencies
npm install

🔑 API Configuration

Create an account on OpenWeatherMap

Generate your API key

Navigate to the following file:

src/api/OpenWeatherService.js


Replace:

WEATHER_API_KEY = "your_api_key_here"


📌 Note:
api/OpenWeatherService.js handles all API requests and acts as the backend service layer for the application.

▶️ Run the Application
npm start


The application will run on:

http://localhost:3000


📙 Used Libraries

react-js

material-ui

📌 Refer to package.json for the complete list of dependencies.

📄 TODOs / Future Enhancements

✅ Styled-components integration

🔄 Convert entire project to TypeScript

🧪 Add Unit Testing

📍 Detect user location using Geolocation API / Geocoding

🌡️ Celsius / Fahrenheit conversion

🌙 Dark / Light Mode support
