<img width="953" height="1276" alt="image" src="https://github.com/user-attachments/assets/140680a4-d77d-4e9d-926c-50eb6acfbf17" />
# 🌦️ Weather App

A simple and elegant weather application built with React that displays current weather conditions for any city worldwide.

---

## 🚀 Demo

🔗 **[Live Demo](https://weather-app-seven-liard-73.vercel.app/)**

## ✨ Features

- **City Search** - Find weather by city name
- **Live Temperature** - Displays in °C with feels-like
- **Visual Weather Icons** - Clear, cloud, rain, snow etc.
- **Humidity Level** - Current air moisture percentage
- **Wind Speed** - Current wind conditions in km/h
- **Responsive Design** - Works on mobile and desktop

---

## 🛠️ Technologies Used

<div align="center">

| Frontend  | API       | Tools       |
|-----------|-----------|-------------|
| React     | OpenWeatherMap | Vite       |
| CSS3      |           | Git         |
| JavaScript|           | npm         |

</div>

⚙️ How It Works
User Search — The user types a city name and clicks the search icon.
API Request — Sends a fetch request to OpenWeatherMap API with the city name.
Data Processing — Extracts temperature, humidity, wind speed, and weather icon.
UI Update — Displays the fetched data with a clean and responsive design.

## 📦 Installation  
1. **Clone the Repository**  
   git clone https://github.com/yourusername/react-weather-app.git
   cd react-weather-app
   
2.Install Dependency
  npm install

3.Add Environment Variables
Create a .env file in the project root and add your API key:
  VITE_APP_ID=your_openweathermap_api_key

4.Run the App
   npm run dev

📌 API Reference
OpenWeatherMap API — https://openweathermap.org/api
Example request:https://api.openweathermap.org/data/2.5/weather?q=London&units=metric&appid=YOUR_API_KEY
   
📜 License
This project is free to use and open source.
