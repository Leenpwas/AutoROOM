# AutoROOM
Esp32 based room control and automation Project
The ESP32 Smart Light Automation System is a low-cost, energy-efficient IoT solution designed to automate lighting control based on human presence and ambient lighting conditions. The system integrates multiple sensors — an ultrasonic distance sensor, a digital LDR module, and a DHT11 temperature and humidity sensor — to intelligently determine when to activate or deactivate a connected light source.

This project eliminates the need for manual switching by employing distance measurement to detect human presence in a room and using the LDR sensor to detect low-light conditions. If both conditions are satisfied (someone is present and it is dark), the light turns ON automatically. Otherwise, it stays OFF. The automation logic is handled locally on the ESP32, ensuring low latency and offline functionality.

Additionally, the system features a web-based user interface hosted on the ESP32 itself. This UI allows users to monitor real-time sensor data and switch between manual and automatic operating modes. In manual mode, users can override the automation and control the light directly from any smartphone or browser on the same network.

The UI is built using responsive HTML/CSS and JavaScript, ensuring compatibility with both mobile and desktop platforms without the need for external libraries or cloud infrastructure. The live sensor values, including distance, light level, temperature, and humidity, are updated in real time.

This project is ideal for smart homes, hostel rooms, classrooms, or any environment where intelligent energy management is desired.









# Schematic 

<img width="382" height="586" alt="image" src="https://github.com/user-attachments/assets/f6e7d12a-4983-4ae0-bb98-ffc525751e4c" />

