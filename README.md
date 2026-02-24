# Virtual Fencing Using IoT

An IoT-based smart security system that replaces physical fencing with an intelligent laser-LDR boundary detection mechanism integrated with ESP32-CAM surveillance.

##  Features
- Laser–LDR Intrusion Detection
- RFID Authentication (RC522)
- Keypad Password Access
- Real-Time Clock (RTC) Logging
- Servo Motor Response
- ESP32-CAM Live Monitoring

##  Hardware Used
- Arduino Mega
- ESP32-CAM
- Laser Module
- LDR Sensor
- RC522 RFID
- DS1307 RTC
- SG90 Servo Motor
- 4x4 Keypad
- Buzzer

##  Working
When the laser beam is interrupted, the system:
1. Detects intrusion
2. Activates buzzer
3. Logs timestamp
4. Moves servo
5. Captures image using ESP32-CAM

##  Applications
- Agricultural Fields
- Industrial Security
- Restricted Areas
- Wildlife Monitoring
