PHOTORESISTOR SIMULATION

This project simulates a light-sensitive alarm using an Arduino and a photoresistor. When the brightness level exceeds a set threshold, the LED starts blinking. The blinking can be stopped via a serial command.

Objectives: 
1. Learn how to read brightness levels using a photoresistor.
2. Use threshold-based activation to control an LED.
3. Implement serial commands to stop blinking.

How It Works: 
- The photoresistor measures brightness and sends the value to the Arduino.
- If the brightness exceeds 220, the LED starts blinking.
- The LED will keep blinking until a "stop" command is received via serial input.
- If the brightness is below the threshold, the LED remains OFF.

Instructions: 
1. Setup the Circuit
- Connect the photoresistor to A2.
- Connect an LED to pin 12.

2. Upload the Code
- Open Photoresistor_Simulation.ino in the Arduino IDE.
- Upload the code to your Arduino board.

3. Run the Simulation
- Open the Serial Monitor in the Arduino IDE (9600 baud rate).
- Observe the brightness readings.
- If the brightness exceeds 220, the LED will blink.
- Type "stop" in the Serial Monitor and press Enter to turn off the blinking.

4. Expected Behavior
- If the light level is high, the LED blinks.
- If the light level is low, the LED stays off.
- If you send "stop" via Serial Monitor, the LED stops blinking.
