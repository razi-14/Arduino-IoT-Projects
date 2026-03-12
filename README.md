# Arduino IoT Projects

A collection of Arduino and ESP32 projects built while learning embedded 
systems and IoT from scratch. Projects range from basic sensor readings 
and hardware control to a fully encrypted MQTT-based IoT system.

## Structure
```
Arduino-IoT-Projects/
├── SparkProjects/        # Beginner projects — sensors, LEDs, motors
└── Random/
    ├── Bluetooth/        # BLE LED control
    ├── HardwareTimer/    # Precision timing without delay()
    ├── InterruptServiceRoutine/  # Hardware interrupt on button press
    └── Wifi/
        ├── AccessPoint/          # ESP32 as a WiFi access point
        ├── SimpleWiFiServer/     # ESP32 web server on local network
        ├── SimpleOTA/            # Wireless firmware updates
        └── MQTT/                 # MQTT projects — see progression below
```

## MQTT Progression
The MQTT folder is the most developed part of this repo, built step by 
step from a basic connection to a fully secure production-ready system:

| # | Project | Key Feature |
|---|---|---|
| 1 | simplemqtt | Basic publish/subscribe |
| 2 | nonblockingmqtt | Non-blocking reconnection |
| 3 | TaskSchedulingMQTT | JSON + scheduled publishing |
| 4 | MosquittoWorks | Local Mosquitto broker |
| 5 | LWTandHB | Last Will + heartbeat |
| 6 | SensorMosquitto | Sensor data pipeline |
| 7 | OTAandSimpleSecurityMQTT | OTA + authentication |
| 8 | Complete | Full TLS encryption |

## Hardware Used Across Projects
- ESP32
- Arduino Mega
- DHT11 Temperature Sensor
- HC-SR04 Ultrasonic Sensor
- Servo Motor
- Relay Module
- LCD Display (16x2)
- Joystick Module
- Various LEDs, buttons, resistors

## Tech Stack
- Arduino IDE
- Mosquitto MQTT Broker
- Node-RED
- SQLite