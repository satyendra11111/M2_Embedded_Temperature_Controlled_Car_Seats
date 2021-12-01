
# M2_Embedded_Temperature_Controlled_Car_Seats
Project Based On The Heat Control System Of Car Seat
The Temperature control system in this project is basically used to control the temperature of a car seat. When a user or driver of the car gets seated on a car, the button sensor gets activated. After that, the user gets access to turn on the heater. The temperature sensor keeps monitoring the temperature and sends the analog value to the microcontroller. The microcontroller processes the analog input of the temperature sensor and outputs a temperature value through serial communication. All the activities of the control system are done on a microcontroller called Atmega328.

SIMULATION:>



The functionality of the heat control system is coded in embedded c and the working is demonstrated using simuation in a software called SimulIDE. Below shows two images where in the 1st image shows the status of the simulation when the system is OFF and the second image shows the status of the system when it is ON.

ON

![Gif (1)](https://user-images.githubusercontent.com/94337093/144182795-892c5829-ecd9-464e-9b6a-342f43967548.gif)

OFF

![Simulation_OFF](https://user-images.githubusercontent.com/94337093/144182520-65cac631-e5b0-4795-8e09-fd7c5de0aaef.png)

Outputs

Circuit	RAM Table
![Circuit (1)](https://user-images.githubusercontent.com/94337093/144183093-92dc1485-cf51-4490-8e0f-71589b5d48e1.gif)

CIRCUIT	RAM_TABLE
![RAM_table (1)](https://user-images.githubusercontent.com/94337093/144183831-d442492d-c37b-42b4-89b9-1abbcb8627af.gif)

CRO
![Oscilloscope (1)](https://user-images.githubusercontent.com/94337093/144183934-4beff1f7-9f47-49d3-89b6-8ae073d1052c.gif)

Serial Monitor
![Serial_Monitor](https://user-images.githubusercontent.com/94337093/144183970-60966b15-ee18-4cfa-9360-3eedea62e271.gif)



Functionality
When the two switches are closed, the first LED glows indicating the actuation of the system and the heater.
Next the analog input from the temperature sensor is received and digitized.
The digitized temperature input is visualized using Pulse Width Modulation.
The corresponding temperature values based on the digitized temperature input is transmitted by the UART protocol. Here the data is displayed on the serial monitor.
