🌧️ Smart Flood Monitoring with Real-Time Rainfall Analysis
Welcome to the Smart Flood Monitoring with Real-Time Rainfall Analysis project! This system is designed to monitor rainfall intensity and water levels in real-time, providing early flood alerts to help mitigate risks and ensure safety. The project leverages IoT sensors, Firebase for data storage, and a user-friendly website to display real-time data and alerts.

🚀 Features
Real-Time Monitoring:

Measures rainfall intensity using a rain sensor.
Tracks water level distance using an ultrasonic sensor.
Flood Alerts:

Provides alerts when water levels or rainfall intensity exceed predefined thresholds.
Triggers a buzzer alarm during flood conditions for immediate attention.
Cloud Integration:

Real-time sensor data is stored in Firebase.
Data is accessible globally via the hosted web interface.
Web Visualization:

A dynamic website hosted on GitHub Pages displays sensor readings, flood alerts, and historical data.
Includes graphs and visualizations of rainfall and water level trends.
⚙️ Technology Stack
Hardware
ESP32: For processing and IoT connectivity.
Rain Sensor: Measures rainfall speed and intensity.
HC-SR04 Ultrasonic Sensor: Calculates water level by measuring the distance to the water surface.
Buzzer: Provides audible flood alerts.
16x2 LCD Display: Shows rainfall intensity and water level in real-time.
Software
Firebase: Stores and retrieves real-time sensor data.
HTML, CSS, JavaScript: For website design and interactivity.
GitHub Pages: For hosting the project website.
📊 How It Works
Rainfall Detection:

The rain sensor calculates the intensity of rainfall and sends the data to the ESP32.
Water Level Monitoring:

The ultrasonic sensor measures the distance to the ground or water surface and calculates the water level.
Data Processing:

ESP32 processes sensor readings and determines whether a flood condition exists based on predefined thresholds.
Alerts:

If flood conditions are detected, the system triggers a buzzer and updates Firebase with the alert condition.
Web Display:

Real-time data (rainfall intensity, water level, and alerts) is fetched from Firebase and displayed on the website.
