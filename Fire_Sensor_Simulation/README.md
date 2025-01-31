FIRE SENSOR SIMULATION

This Arduino project simulates a fire detection system using a temperature sensor and a photoresistor (light sensor). If both temperature and brightness exceed certain thresholds, an LED blinks to indicate a fire alert.

Objectives:
Understand how to use temperature sensors and photoresistors in Arduino.
Learn how to read analog values and set thresholds for detection.
Implement LED alerts for fire detection.

How It Works: 
- The temperature sensor (A0) measures the surrounding heat.
- The photoresistor (A2) detects brightness levels.
- If the temperature > 50°C and brightness > 220, the LED (pin 12) blinks as an alarm.
- If conditions are normal, the LED stays off.

Instructions: 
1. Upload the code (Fire_Sensor_Simulation.ino) to an Arduino.
2. Connect the sensors to the correct analog pins.
3. Observe the Serial Monitor for real-time temperature and brightness readings.
4. Trigger the fire alert by increasing temperature and brightness.
