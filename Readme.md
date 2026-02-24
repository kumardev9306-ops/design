
# Smart Safety Valve for Gas Cylinders

## 1. Project Overview

The **Smart Safety Valve System** is an IoT-based safety solution designed to detect gas leakage from LPG cylinders and automatically initiate preventive actions. The system enhances safety by combining real-time gas monitoring, automated valve control, electrical power cutoff, and remote alert notifications.

This project aims to reduce the risk of fire accidents, explosions, and health hazards caused by gas leakage in residential and industrial environments.

---

## 2. Problem Statement

Gas leakage from cylinders poses significant safety risks, including:

* Fire outbreaks
* Explosions
* Health hazards due to inhalation
* Electrical short circuits

Existing safety measures often rely on manual detection and intervention, which can lead to delayed response. Therefore, an automated and intelligent system is required to detect leaks early and take immediate corrective actions.

---

## 3. Proposed Solution

The Smart Safety Valve System provides an integrated safety mechanism that:

* Detects gas leakage using a gas sensor
* Automatically shuts off the gas supply
* Sends real-time alerts via Wi-Fi
* Cuts off electrical power to prevent sparks
* Activates an audible alarm

This multi-layered safety approach ensures rapid detection and immediate response without human intervention.

---

## 4. System Architecture

### 4.1 Key Components

| Component                                   | Description                                          |
| ------------------------------------------- | ---------------------------------------------------- |
| Gas Leak Sensor (MQ Series)                 | Detects gas concentration in the surrounding air     |
| Microcontroller (Arduino / ESP8266 / ESP32) | Processes sensor data and controls system operations |
| Wi-Fi Module                                | Sends alerts to a smartphone or cloud platform       |
| Shut-Off Valve (Servo/Solenoid)             | Automatically stops gas flow                         |
| Relay Module                                | Disconnects electrical supply during leakage         |
| Buzzer/Siren                                | Provides audible warning                             |

---

## 5. Working Principle

1. The gas sensor continuously monitors ambient air for gas concentration.
2. Sensor data is processed by the microcontroller.
3. When gas concentration exceeds predefined thresholds:

   * A notification is sent to the user's smartphone via Wi-Fi.
   * The relay module disconnects the electrical supply.
   * The shut-off valve closes to stop gas flow.
   * The alarm system is activated.

The system operates in real-time and follows predefined alert levels.

---

## 6. Alert Levels

| Level  | Leak Severity | System Response                               |
| ------ | ------------- | --------------------------------------------- |
| Low    | Minor Leak    | Wi-Fi notification                            |
| Medium | Moderate Leak | Electrical power cutoff                       |
| High   | Severe Leak   | Alarm activation and automatic valve shutdown |

---

## 7. Features

* Continuous real-time gas monitoring
* Automated gas shutoff mechanism
* Remote alert notification via Wi-Fi
* Multi-level safety response system
* Compact and scalable design

---

## 8. Benefits

* Prevents gas-related accidents
* Reduces response time during emergencies
* Enhances residential and industrial safety
* Cost-effective and scalable solution
* Minimizes human dependency for leak detection

---

## 9. Technologies Used

* Embedded Systems
* Internet of Things (IoT)
* MQ Series Gas Sensors
* Arduino / ESP8266 / ESP32
* Relay Modules
* Servo or Solenoid Valves
* Wireless Communication (Wi-Fi)

---

## 10. Future Enhancements

* Dedicated mobile application with real-time gas level monitoring
* Cloud-based data logging and analytics
* SMS-based emergency alerts
* Battery backup for power failure scenarios
* AI-based predictive gas leakage analysis

---

## 11. Project Setup (Prototype)

1. Connect the gas sensor to the microcontroller.
2. Integrate the relay module for electrical cutoff control.
3. Attach a servo or solenoid valve for automatic gas shutoff.
4. Configure Wi-Fi credentials within the firmware.
5. Upload the program to the microcontroller.
6. Test the system under controlled conditions.

---

## 12. Author

Dev Kumar
B.Tech Computer Science and Engineering

---
