Name: PALURI SRAVANI Company: CodTech IT Solutions Pvt. Ltd Intern ID: CT12EFN Domain: Embedded Systems Duration: December 17, 2024, to February 17, 2025

Project Overview Objective To design and implement a system using an Arduino microcontroller to display real-time temperature readings on an LCD screen by integrating a temperature sensor.

Components Required Arduino: Arduino Uno or Nano. LCD: 16x2 LCD (with or without an I2C module). Temperature Sensor: LM35, DHT11, or DHT22. Potentiometer: For contrast adjustment of the LCD (if not using I2C). Breadboard: For prototyping. Jumper Wires: For connections.

Hardware Setup

Temperature Sensor LM35: Connect VCC to 5V, GND to GND, and OUT to an analog pin (e.g., A0) on the Arduino. DHT11/DHT22: Connect VCC to 5V, GND to GND, and DATA to a digital pin (e.g., D2) on the Arduino.
LCD with I2C Module Connections: SDA: A4 (Arduino Uno) or the appropriate SDA pin for other boards. SCL: A5 (Arduino Uno) or the appropriate SCL pin for other boards. VCC: Connect to 5V. GND: Connect to GND.
LCD without I2C Module Connections: Connect RS, E, and D4-D7 pins of the LCD to corresponding digital pins on the Arduino. Connect the potentiometer's center pin to the LCD's V0 pin for contrast adjustment.
Functionality The temperature sensor measures the surrounding temperature. The Arduino processes the sensor data and outputs it to the LCD. The LCD displays the real-time temperature in a readable format.

![WhatsApp Image 2025-01-08 at 11 02 28 AM](https://github.com/user-attachments/assets/7817873f-8d16-45bb-a219-cb264fc9cb17)
