# 🌤️ Weather Watch - Real-Time Weather Application

A modern, responsive weather application that provides real-time weather information for any city worldwide. Built with pure **HTML**, **CSS**, and **JavaScript**.

![Weather App Screenshot](https://github.com/user-attachments/assets/1ef7023d-d7ec-4e59-96f3-af8ebbf1ddc7)

---

## 🚀 Live Demo

*[Add your live deployment link here when available]*

---

## ✨ Features

- 🌍 **Real-time Weather Data** — Get current weather conditions for any city  
- 📍 **Auto-location Detection** — Automatically detects and shows weather for your current location  
- 📱 **Responsive Design** — Works perfectly on desktop, tablet, and mobile devices  
- 🎨 **Modern UI/UX** — Clean, intuitive interface with smooth animations  
- 📊 **Comprehensive Metrics** — Display temperature, humidity, wind speed, sunrise/sunset times, and more  
- ⚡ **Fast & Lightweight** — Built with vanilla JavaScript for optimal performance  

---

## 🛠️ Technologies Used

- **Frontend:** HTML5, CSS3, JavaScript (ES6+)  
- **API:** OpenWeatherMap API  
- **Icons:** Custom CSS design  
- **Deployment:** Static web hosting compatible  

---

## 📁 Project Structure

weather-watch/
│
├── index.html
├── style.css
├── script.js
└── README.md

yaml
Copy code

---

## 🔧 Installation & Setup

### 🧰 Prerequisites
- A modern web browser  
- Internet connection (for API calls)

### ⚙️ Local Development

1. **Clone the repository:**
   ```bash
   git clone https://github.com/your-username/weather-watch.git
Navigate to the project directory:

bash
Copy code
cd weather-watch
Open index.html in your web browser or start a local server:

Using Python:

bash
Copy code
python -m http.server 8000
Using Node.js:

bash
Copy code
npx http-server
Visit http://localhost:8000 in your browser.

🌐 API Integration
This project uses the OpenWeatherMap API to fetch real-time weather data.

🧩 API Endpoints Used
City-based weather:

javascript
Copy code
https://api.openweathermap.org/data/2.5/weather?q={city}&appid={API_KEY}&units=metric
Geolocation-based weather:

javascript
Copy code
https://api.openweathermap.org/data/2.5/weather?lat={lat}&lon={lon}&appid={API_KEY}&units=metric
🎯 How to Use
Search by City — Enter any city name in the search bar and click "Search"

Auto-detection — Allow location access to get weather for your current location

View Details — Check temperature, humidity, wind conditions, and sunrise/sunset times

Responsive Design — Works on all devices with adaptive layout

📊 Weather Metrics Displayed
🌡️ Temperature: Current, Min, Max, and Feels Like

💧 Humidity: Current humidity percentage

💨 Wind: Speed and direction

☀️ Sun Times: Sunrise and sunset times (local time)

🎯 Location: City name and geolocation data

🔒 Environment Variables
To run this project, you'll need to add your OpenWeatherMap API key:

Get a free API key from OpenWeatherMap

Replace the API key inside script.js:

javascript
Copy code
const apiKey = "your_actual_api_key_here";
🚀 Deployment
This static website can be deployed on any web hosting service.

💡 Recommended Platforms
Netlify — Drag and drop deployment

Vercel — GitHub integration

GitHub Pages — Free for public repositories

Render — Static site hosting

🪄 Steps for Netlify Deployment
Fork this repository

Go to https://netlify.com

Connect your GitHub account

Select this repository

Click Deploy

🤝 Contributing
Contributions, issues, and feature requests are welcome!

Fork the Project

Create your Feature Branch

bash
Copy code
git checkout -b feature/AmazingFeature
Commit your Changes

bash
Copy code
git commit -m 'Add some AmazingFeature'
Push to the Branch

bash
Copy code
git push origin feature/AmazingFeature
Open a Pull Request

📝 License
This project is licensed under the MIT License.

👨‍💻 Author
Md Arshad

GitHub: @Md-Arshad1201

Project Link: https://github.com/Md-Arshad1201/weather-watch

🙏 Acknowledgments
OpenWeatherMap — for providing the weather API

Icons and UI inspiration from modern web design standards
