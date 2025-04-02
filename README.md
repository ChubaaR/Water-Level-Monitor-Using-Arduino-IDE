# IoT-Based Water Level Indicator System

# Overview
This project presents an IoT-based solution for monitoring and managing bathtub water levels. Using an ultrasonic sensor and the NodeMCU ESP8266 microcontroller, the system automatically measures the water level in a bathtub and sends real-time data to the cloud. Users can monitor the water level remotely via their mobile phones and receive alerts when the water level reaches a specified threshold to prevent overflows and water wastage.

# Features
**Real-time Water Level Monitoring:** Measures the water level in a bathtub using an ultrasonic sensor.

**Cloud Connectivity:** Sends water level data to the cloud for remote monitoring via a mobile application.

**Automatic Alerts:** Sends notifications to the user when the water level exceeds the predefined threshold.

**Energy Efficient:** Reduces the need for manual intervention and saves water and energy.

**LED Indicators:** Provides visual feedback on the current water level and system status.

# Technologies Used
**NodeMCU ESP8266:** A Wi-Fi enabled microcontroller used for connecting the ultrasonic sensor and sending data to the cloud.

**Ultrasonic Sensor:** Measures the water level by emitting and receiving sound waves to calculate the distance from the sensor to the water surface.

**Cloud Storage:** Stores water level data for remote access and monitoring.

**LEDs:** Provides visual indicators for the water level and system status.

**Mobile Application:** Allows users to monitor the water level remotely via a mobile phone.

# Installation
Prerequisites
NodeMCU ESP8266 microcontroller.

Ultrasonic sensor (HC-SR04 or similar).

LEDs for water level indicators.

Arduino IDE for programming the NodeMCU ESP8266.

Wi-Fi connection for cloud communication.

# Steps
Clone the repository:

bash
Copy
Edit
git clone https://github.com/yourusername/iot-water-level-indicator.git

# Hardware Setup:

Connect the ultrasonic sensor to the NodeMCU ESP8266.

Connect the LEDs to indicate water levels (optional, but recommended for real-time feedback).

**Programming the NodeMCU:**

Open the project in Arduino IDE.

Select NodeMCU ESP8266 as the target board in the Tools menu.

Upload the provided code to the NodeMCU.

**Configure Cloud Settings:**

Set up a cloud storage platform (e.g., Firebase, ThingSpeak, or custom server).

Update the cloud configuration in the code to connect your NodeMCU to the cloud platform.

**Mobile Application Setup (Optional):**

You can develop or use an existing mobile app to view water level data and receive notifications.

**Run the System:**

Once everything is connected and uploaded, power on the system.

The ultrasonic sensor will start measuring the water level, and the data will be sent to the cloud.

The LED indicators will provide feedback, and the mobile app will notify the user when the water level reaches the threshold.

# Usage
Once the system is running, you can monitor the water level via the mobile application or cloud dashboard. When the water level is detected to be high, an alert will be sent to the user. This allows the user to take action promptly, preventing overflow and reducing water wastage.

# License
This project is licensed under the MIT License - see the LICENSE file for details.

# Acknowledgements
The IoT-based Water Level Indicator concept was inspired by IoT applications in home automation.
Special thanks to the contributors of the ultrasonic sensor libraries and NodeMCU community for their support.

