# 🌤️ Weather App

A simple and interactive **Weather Application** that allows users to search for any city and view real-time weather information. The app fetches weather data using the **OpenWeatherMap API** and displays important weather details in a clean and responsive UI.

---

# 📌 Features

- 🔍 Search weather by **city name**
- 🌡️ Displays **current temperature**
- 🌥️ Shows **weather condition with icons**
- 💧 Displays **humidity**
- 🌬️ Shows **wind speed**
- 📊 Displays **atmospheric pressure**
- 🌡️ Shows **feels like temperature**
- 📅 Displays **current date**
- ⏳ **Loading animation** while fetching data
- ❌ **Error handling** for invalid city names
- 🎨 **Modern UI design with gradients and animations**

---

# 🛠️ Technologies Used

- **HTML5** – Structure of the application  
- **CSS3** – Styling and animations  
- **JavaScript (Vanilla JS)** – Application logic and API calls  
- **OpenWeatherMap API** – Real-time weather data  

---

# ⚙️ How It Works

1. The user enters a **city name** in the search box.
2. When the **Search button** is clicked (or Enter is pressed):
   - A request is sent to the **OpenWeatherMap API**.
3. The API returns weather data in **JSON format**.
4. JavaScript extracts important information such as:
   - Temperature
   - Weather description
   - Humidity
   - Wind speed
   - Pressure
5. The app dynamically updates the UI and displays the weather information.

---

# 📡 API Used

This project uses the **OpenWeatherMap Current Weather API**.

Example request format:

```
https://api.openweathermap.org/data/2.5/weather?q={city}&appid={API_KEY}&units=metric
```

Example:

```
https://api.openweathermap.org/data/2.5/weather?q=London&appid=YOUR_API_KEY&units=metric
```

---

# 📂 Project Structure

```
Weather-App
│
├── index.html     # Main application file (HTML, CSS, JS)
└── README.md      # Project documentation
```

---

# ▶️ How to Run the Project

1. Download or clone the repository

```
git clone https://github.com/your-username/weather-app.git
```

2. Open the project folder.

3. Open the **index.html** file in your browser.

4. Enter a **city name** and view the weather.

---

# 🖥️ User Interface Components

### Search Section
- Input field to enter city name
- Search button

### Weather Information
- City name and country
- Current date
- Temperature
- Weather icon
- Weather description

### Weather Details
- Feels Like Temperature
- Humidity
- Wind Speed
- Atmospheric Pressure

---

# ⚠️ Error Handling

The application handles common errors such as:

- Invalid city name
- Network issues
- API response errors

If a city is not found, an error message is displayed to the user.

---

# 🚀 Future Improvements

Possible improvements for the project:

- 🌍 Detect **user's current location**
- 📅 **5-day weather forecast**
- 🌙 **Dark mode**
- 📱 Improved **mobile responsiveness**
- 🗺️ Weather **map integration**

---

# 📸 Demo

When the application loads, it automatically displays the weather for **London** by default.

Users can then search for any city worldwide to view its current weather conditions.