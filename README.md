# Wokwi Project - Simulating ESP-NOW Protocol Using Serial Communication

This repository showcases a simulation of a dual-stage motorcycle safety system. While inspired by the [YouTube video by dian artanto](https://www.youtube.com/watch?v=K74WRW9XY8c), which helped establish serial connections between two ESP32 modules, this project adapts and expands the approach to simulate communication between an STM32 microcontroller and an ESP32 module, as well as between two ESP32 modules.

### Project Overview
The project is designed in two stages to represent a motorcycle safety system:

1. **Stage 1: Motorcycle Unit**  
   - An STM32 microcontroller is connected to an ESP32 module via serial communication.  
   - Additional sensors, including an alcohol sensor, are integrated to monitor the rider's condition.
   - [STM32](https://wokwi.com/projects/415449632817614849).

2. **Stage 2: Helmet Unit**  
   - Another ESP32 module is mounted on the helmet and equipped with an alcohol sensor for continuous monitoring.  
   - This ESP32 would ideally communicate with the motorcycle's ESP32 via the ESP-NOW protocol.  
   - However, since Wokwi does not support Wi-Fi or Bluetooth simulation, the communication between the ESP32 modules is represented visually with serial communication as a substitute.
   - [ESP-Receive](https://wokwi.com/projects/415092125747458049), [ESP-Send](https://wokwi.com/projects/415092094254523393)

### Key Insights
- The YouTube video by Tech StudyCell was instrumental in understanding serial communication between two ESP32 modules.  
- Adapting this knowledge, the communication between the STM32 and ESP32 is implemented differently due to their distinct protocols.  
- Serial communication is used creatively in Wokwi to simulate the ESP-NOW protocol, enabling a functional visualization of the system's architecture.

### Limitations
- Wokwi does not currently support Wi-Fi or Bluetooth simulation, preventing a true ESP-NOW implementation.  
- The project visually demonstrates the system's design and communication flow but does not replicate practical functionality.  

### Getting Started
1. Clone this repository.  
2. Open the project in [Wokwi](https://wokwi.com/).  
3. Explore the system's simulation and communication flow.  

### Credits
- Serial communication implementation between ESP32 modules was inspired by the [dian artanto YouTube video](https://www.youtube.com/watch?v=K74WRW9XY8c).  
- Simulation and system design were implemented using Wokwi.  

Feel free to explore, modify, and expand upon this project. Suggestions for improving the simulation or bridging current limitations are always welcome!
