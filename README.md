# ESP32 Distance Measuring System

An IoT-based distance-measuring prototype built with an ESP32 and an ultrasonic sensor. The system measures the distance to an object, displays the reading on an I2C LCD, and sends measurement data to ThingSpeak for remote viewing.

## Features

- Measures distance using an ultrasonic sensor
- Displays readings on an I2C LCD
- Shows distance in multiple units
- Sends readings to ThingSpeak over Wi-Fi

## Components

- ESP32 development board
- Ultrasonic distance sensor
- I2C LCD
- Jumper wires and breadboard
- Wi-Fi connection
- ThingSpeak account and channel

## How It Works

The ultrasonic sensor sends a sound pulse and measures the time taken for its echo to return. The ESP32 uses that time to calculate the distance, updates the LCD, and transmits the reading to ThingSpeak.

## Setup

1. Connect the ultrasonic sensor and I2C LCD to the ESP32.
2. Add your Wi-Fi details and ThingSpeak channel credentials to the code. Keep these credentials private; don’t upload them to GitHub.
3. Install any libraries required by the sketch.
4. Upload the code to the ESP32.
5. Open the ThingSpeak channel to view incoming readings.

## Learning Outcomes

This project gave me practical experience with ESP32 programming, sensor integration, LCD output, Wi-Fi connectivity, IoT data transmission, and hardware troubleshooting.
