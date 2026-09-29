### Smart Helmet for Industrial Workers
An IoT-based safety helmet designed to protect industrial workers in hazardous environments like mining, construction, and factories.
### Problem
Workers in industries face risks like head injuries, toxic gas leakage, high temperature, and accidents with no quick alert system.
### Solution
This smart helmet monitors the worker's safety in real-time and sends alerts to the supervisor.
### Key Features
- Impact Detection: Detects if worker falls or helmet gets a hit
- Gas Detection: MQ2/MQ135 sensor detects toxic gases (CO, LPG)
- Temperature & Humidity Monitoring: DHT11 sensor
- GPS Location Tracking: Live location of worker
- Emergency SOS Button: Worker can press button for help
- Buzzer & LED Alert: Immediate alert on helmet
- IoT Dashboard: All data sent to cloud (Blynk) for supervisor to monitor
### Technology Used
- Hardware: Arduino / ESP32, Sensors (MQ2, DHT11, Accelerometer), GPS Module, Buzzer
- Software: Arduino IDE, IoT Cloud Platform
- Communication: Wi-Fi
### How it Works
1. Sensors collect data from helmet.
2. ESP32 processes data.
3. If value crosses threshold (e.g., gas high, impact detected), buzzer alerts and location is sent to cloud.
4. Supervisor gets notification on mobile/web app.
