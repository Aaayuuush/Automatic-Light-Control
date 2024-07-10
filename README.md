Automatic Street Light Control
The project focuses on controlling street lights using an IR sensor. When a person walks under a street light, the sensor triggers it to automatically turn on. The project simulation was conducted using Proteus, and the coding was done using Keil. The project includes three sensors, but additional IR sensors can be incorporated to increase the number of parking slots by modifying the code accordingly.

Components Used:
Microcontroller (AT89C51)
Button
Relay (5V)
AC Voltage Source
Ground
Transistor (BC547)
Power
Lamp
Project Working
Each sensor is paired with a load (lamp). Relays are connected to the microcontroller using port P2, while sensors are connected to port P1. Initially, all sensors and loads are set to 0. An infinite while loop runs until a condition is met, testing various scenarios: all sensors off, one sensor on, two sensors on, and all sensors on. After testing, the HEX code file is compiled and generated. Three relays drive the electrical load, with the AC source providing alternating current. Each relay has a corresponding sensor, with one end connected to the microcontroller and the other to power. A transistor interfaces between the relays and the microcontroller, with the collector connected to the relay, the base to the microcontroller, and the emitter to the ground. The lamp is connected to the AC source and the relay, with the relay needing to be 5V since the microcontroller cannot handle other voltages.

Circuit Diagram:
![image](https://github.com/Aaayuuush/Automatic-Light-Control/assets/127843057/78bdc4b8-97c9-4079-816a-0717cb9d8175)


Source Code:

![image](https://github.com/Aaayuuush/Automatic-Light-Control/assets/127843057/42660b61-ce04-46ae-882e-5d4cec82a1b4)

![image](https://github.com/Aaayuuush/Automatic-Light-Control/assets/127843057/b1ca5d47-2c17-4c88-b7e9-b62d2133c676)

All screenshots, the PowerPoint presentation, the synopsis, and other files have been included.
 
 
