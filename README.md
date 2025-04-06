# GreenX Basic
This project is a simple yet effective solution for automating key aspects of greenhouse management using Arduino. 
This is our basic version or the Level 1 Version. The system integrates multiple sensors and actuators to monitor and control environmental factors such as light, soil moisture, and temperature, ensuring optimal conditions for plant growth.


Features
- Light Control: Monitors ambient light levels using an LDR (Light Dependent Resistor) and automatically turns on/off an LED strip to maintain visibility.
- Soil Moisture Regulation: Uses a soil moisture sensor to check soil dryness and activates a water pump for irrigation as needed.
- Temperature & Humidity Management: Utilizes a DHT11 sensor to measure temperature and humidity, and activates a fan to maintain a comfortable environment when thresholds are exceeded.
- Custom Serial Monitor Interface: Displays real-time sensor readings and system statuses for easy monitoring and debugging.



Hardware Requirements
- Arduino board (e.g., Uno or Nano)  
- DHT11 Temperature and Humidity Sensor  
- Soil Moisture Sensor  
- LDR Sensor  
- Relays (1x Three-channel or 3x Single-channel)  
- LED Strip (5V/12V)  
- DC Motor (12V) and Water Pump  
- Fan (5V/12V)  
- Breadboard and Connecting Wires  
- Power Supply (Battery 9V/12V)



How It Works
1. Light Monitoring:  
   - If the light level is low, the LED strip is automatically activated to provide illumination.  
2. Soil Moisture Monitoring:  
   - When soil moisture drops below the threshold, the water pump is triggered to irrigate the plants.  
3. Temperature & Humidity Monitoring:  
   - If temperature or humidity exceeds the set limits, the fan is turned on to cool and ventilate the greenhouse.  
4. Serial Interface:  
   - Sensor data and system states are printed on the Serial Monitor for easy troubleshooting and visualization.



Applications
- Small-scale greenhouses and nurseries.  
- Educational projects to understand IoT-based agricultural solutions.  
- Prototype for advanced greenhouse automation systems.
