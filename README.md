# weather_data_app
# 🌦 Weather App

This project is a simple **Weather Information Application** built using **Python** and the [OpenWeatherMap API](https://openweathermap.org/api).  
It includes two versions:
1. **Command-Line Interface (CLI) version**  
2. **Graphical User Interface (GUI) version using Tkinter**

---

## 🚀 Features
- Get **real-time weather data** by entering any city name.
- Displays:
  - 🌍 City name  
  - 🌡 Temperature (°C)  
  - 💧 Humidity (%)  
  - ☁ Weather condition description  
  - 🌤 Weather icon (GUI version only)  
- Error handling for invalid city names.

---

## 📂 Project Structure
weather_app/
│
├── weather_cli.py # Command-line version
├── weather_gui.py # Tkinter GUI version
└── README.md # Project documentation


---

## ⚙️ Requirements
Make sure you have Python 3 installed.  
Install the following dependencies:
```bash
pip install requests pillow
## 📸 GUI Preview

The GUI will look like this after fetching data:

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/efdd3d33-b770-4e45-b3bb-f9f19e310a89" />

## ✅ Future Improvements

Here are some ideas to enhance the Weather App in the future:

- 🌦 Add support for a **5-day or weekly forecast**.  
- 🌬 Display additional weather details such as **wind speed, air pressure, sunrise, and sunset times**.  
- 🌍 Support for multiple cities at once (comparison mode).  
- 💾 Save **search history** and allow quick access to recent cities.  
- 🎨 Improve the design with a **modern GUI framework** like PyQt or Kivy.  
- 📱 Build a **mobile-friendly version** using Kivy or Flutter with Python backend.  
- 🔔 Add **alerts/notifications** for extreme weather conditions.  
- 🌐 Provide an option to detect the **user’s current location** automatically via IP or GPS.  

