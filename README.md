# Flood Monitoring System – Project Report

## 1. Aim
To develop a real-time flood monitoring and alert system using IoT technologies that continuously monitors water levels and sends alerts when levels exceed a critical threshold.

## 2. Problem Statement
Floods cause significant damage worldwide. Traditional systems lack automated real-time monitoring and alerting. This project simulates a low-cost IoT solution to mitigate flood risks by monitoring water levels and sending immediate alerts.

## 3. Scope of Solution
- Applicable to dams, reservoirs, rivers.
- Scalable for multiple monitoring points.
- Utilizes open-source and low-cost hardware/software.
- Cloud integration for real-time alerts.

## 4. Required Components
### Hardware
- ESP32 Dev Board  
- HC‑SR04 Ultrasonic Sensor  
- Buzzer  
-Serial Monitor
- LEDs (optional)

### Software
- Arduino IDE  
- Wokwi simulator  
- Firebase/ThingSpeak (for cloud)

### Cloud
- Firebase Realtime DB or ThingSpeak IoT Platform

## 5. Flowchart
        
[Start]
   ↓
[Initialize Sensor & WiFi]
   ↓
[Read Water Level]
   ↓
[Is Water Level > Threshold?]
   ↓                        ↓
 [YES]                            [NO]
 ↓                                     ↓
[Send Alert]                 [Level Safe]
 ↓                                         ↓
[Sound Buzzer]              [Repeat]