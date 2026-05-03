Designed by Hydrance Robotics

**ESP32 Climate Monitor**

This project turns an ESP32 and a DHT11 sensor into a live climate tracker that displays real-time data on a 0.96" I2C OLED screen.

**Required Libraries**

Before uploading the code, install these via the Arduino Library Manager:

Adafruit SSD1306 (for the display)

Adafruit GFX Library (core graphics)

DHT sensor library by Adafruit

Adafruit Unified Sensor (required dependency for DHT)

**Quick Setup**

Wire it up: Follow the table above.

Install Libraries: Use the Arduino Library Manager (Ctrl + Shift + I).

Flash the Code: Open your .ino file, select your ESP32 board, and hit upload.

Check Display: If the screen is blank, double-check your I2C address (usually 0x3C).

<img width="1671" height="863" alt="image" src="https://github.com/user-attachments/assets/17fe6485-ddf0-4e58-a0e5-dc2cd3ba96d8" />
<img width="1408" height="768" alt="Wiring Diagram" src="https://github.com/user-attachments/assets/4ef3e782-abc8-41de-9ce0-676529f7a00f" />

