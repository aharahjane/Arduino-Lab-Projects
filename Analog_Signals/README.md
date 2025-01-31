Analog Signals Activity

This folder contains an Arduino project that controls LED brightness using Pulse Width Modulation (PWM). The LEDs light up one by one and then turn off in reverse order.

Objectives:
1. Learn how analog signals work in Arduino.
2. Use PWM (analogWrite) to adjust LED brightness.
3. Understand how while loops and arrays can control multiple LEDs.

How It Works:
- Five LEDs are connected to pins 8, 9, 10, 11, and 12.
- The program slowly increases each LED's brightness one by one.
- After all LEDs are fully on, they slowly fade out in reverse order.
- A 1-second delay is added after all LEDs turn on or off.

Instructions: 
1. Upload the code (analog_signals.ino) to an Arduino.
2. Build the circuit on a breadboard using the provided pin setup.
3. Run the program and observe the LEDs lighting up and fading out.


Files Included: 
- Analog_Signals.ino – The Arduino sketch file.
- Breadboard_Diagram – A breadboard layout (made with Tinkercad).
