# Smart Irrigation System

IoT based automatic irrigation system using Arduino. Saves water by monitoring soil moisture and tank level in real-time.

## Features
- **Auto Pump Control**: Turns ON when soil < 30% and tank > 10%
- **Tank Monitoring**: HC-SR04 ultrasonic sensor for water level
- **DHT11**: Temperature and humidity readings
- **LCD Display**: Live Soil %, Tank %, Temp
- **Low Water Alert**: Buzzer + Red LED
- **Manual Button**: Override pump control
- **IoT Ready**: Serial output for NodeMCU/Blynk integration

## Components
- Arduino Uno
- Soil Moisture Sensor
- DHT11 Sensor
- HC-SR04 Ultrasonic Sensor
- 16x2 I2C LCD
- Relay Module + Water Pump
- Buzzer, LEDs

## How to Run
1. Upload `smart_irrigation.ino` to Arduino
2. Connect sensors as per circuit
3. Power on and monitor LCD

## Documentation
[📄 Download Full Project Report PDF](Smart_Irrigation_System_Final.pdf)

## Demo Video
[▶️ Watch Project Demo](WhatsApp%20Video%202026-07-06%20at%202.39.27%20AM.mp4)
