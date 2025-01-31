LIGHT CONNECTION WITH FASTAPI

This project allows you to control an LED using an Arduino and a FastAPI web server. The FastAPI server sends commands (ON or OFF) to the Arduino over a serial connection, enabling remote control of the LED.

Objectives: 
1. Learn how to send commands from a Python API to an Arduino.
2. Use FastAPI to create a simple web-based control system.
3. Establish serial communication between Python and Arduino.

How It Works: 
- The Arduino listens for serial input from the FastAPI server.
- The FastAPI server provides two API endpoints:
  - /led/on → Turns the LED ON.
  - /led/off → Turns the LED OFF.
- The Arduino reads the command (1 for ON, 0 for OFF) and controls pin 11 accordingly.

Instructions: 
1. Upload Arduino Code
- Open Light_Arduino.ino in the Arduino IDE.
- Connect the Arduino and upload the code.

2. Run FastAPI Server
