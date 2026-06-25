This project implements a resilient ESP32-based IoT system that reads simulated temperature and humidity data and publishes it to a public MQTT broker in JSON format. 
The firmware is designed using a non-blocking state machine for reliable operation under network failures.

 Features:
ESP32-based IoT node.
MQTT communication. 
JSON data formatting.
Simulated temperature & humidity sensor.
Non-blocking state machine design.
Automatic WiFi and MQTT reconnection.


How It Works:
 ESP32 connects to WiFi.
 MQTT connection is established.
 Sensor data is generated every 5 seconds.
 Data is serialized into JSON.
 Data is published to MQTT topic.
 System automatically recovers from failures.
