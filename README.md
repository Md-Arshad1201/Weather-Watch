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

```
weather-watch/
│
├── index.html
├── style.css
├── script.js
└── README.md
```

---

## 🔧 Installation & Setup

### 🧰 Prerequisites
- A modern web browser  
- Internet connection (for API calls)

### ⚙️ Local Development

1. **Clone the repository:**
   ```bash
   git clone https://github.com/your-username/weather-watch.git
   ```

2. **Navigate to the project directory:**
   ```bash
   cd weather-watch
   ```

3. **Open `index.html`** in your web browser or start a local server:

   **Using Python:**
   ```bash
   python -m http.server 8000
   ```

   **Using Node.js:**
   ```bash
   npx http-server
   ```

4. **Visit in your browser:**
   ```
   http://localhost:8000
   ```

---

## 🌐 API Integration

This project uses the **OpenWeatherMap API** to fetch real-time weather data.

### 🧩 API Endpoints Used

**City-based weather:**
```javascript
https://api.openweathermap.org/data/2.5/weather?q={city}&appid={API_KEY}&units=metric
```

**Geolocation-based weather:**
```javascript
https://api.openweathermap.org/data/2.5/weather?lat={lat}&lon={lon}&appid={API_KEY}&units=metric
```

---

## 🎯 How to Use

1. **Search by City** — Enter any city name in the search bar and click "Search"  
2. **Auto-detection** — Allow location access to get weather for your current location  
3. **View Details** — Check temperature, humidity, wind conditions, and sunrise/sunset times  
4. **Responsive Design** — Works on all devices with adaptive layout  

---

## 📊 Weather Metrics Displayed

- 🌡️ **Temperature:** Current, Min, Max, and Feels Like  
- 💧 **Humidity:** Current humidity percentage  
- 💨 **Wind:** Speed and direction  
- ☀️ **Sun Times:** Sunrise and sunset times (local time)  
- 🎯 **Location:** City name and geolocation data  

---

## 🔒 Environment Variables

To run this project, you'll need to add your **OpenWeatherMap API key**.

1. Get a free API key from [OpenWeatherMap](https://openweathermap.org/api)  
2. Replace the API key inside `script.js`:  
   ```javascript
   const apiKey = "your_actual_api_key_here";
   ```

---

## 🚀 Deployment

This static website can be deployed on any web hosting service.

### 💡 Recommended Platforms

- **Netlify** — Drag and drop deployment  
- **Vercel** — GitHub integration  
- **GitHub Pages** — Free for public repositories  
- **Render** — Static site hosting  

### 🪄 Steps for Netlify Deployment

1. Fork this repository  
2. Go to [https://netlify.com](https://netlify.com)  
3. Connect your GitHub account  
4. Select this repository  
5. Click **Deploy**  

---

## 🤝 Contributing

Contributions, issues, and feature requests are welcome!

1. **Fork the Project**  
2. **Create your Feature Branch:**  
   ```bash
   git checkout -b feature/AmazingFeature
   ```
3. **Commit your Changes:**  
   ```bash
   git commit -m 'Add some AmazingFeature'
   ```
4. **Push to the Branch:**  
   ```bash
   git push origin feature/AmazingFeature
   ```
5. **Open a Pull Request**

---

## 📝 License

This project is licensed under the **MIT License**.

---

## 👨‍💻 Author

**Md Arshad**  
- GitHub: [@Md-Arshad1201](https://github.com/Md-Arshad1201)  
- Project Link: [Weather Watch](https://github.com/Md-Arshad1201/weather-watc)
- Live demo: [Live](file:///C:/Users/mdars/OneDrive/Desktop/Weather/index.html)

---

## 🙏 Acknowledgments

- [OpenWeatherMap](https://openweathermap.org) — for providing the weather API  
- Icons and UI inspiration from modern web design standards
