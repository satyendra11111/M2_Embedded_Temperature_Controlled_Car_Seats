# M2_Embedded_Temperature_Controlled_Car_Seats
Project Based On The Heat Control System Of Car Seat
The Temperature control system in this project is basically used to control the temperature of a car seat. When a user or driver of the car gets seated on a car, the button sensor gets activated. After that, the user gets access to turn on the heater. The temperature sensor keeps monitoring the temperature and sends the analog value to the microcontroller. The microcontroller processes the analog input of the temperature sensor and outputs a temperature value through serial communication. All the activities of the control system are done on a microcontroller called Atmega328.

SIMULATION:>
The functionality of the heat control system is coded in embedded c and the working is demonstrated using simuation in a software called SimulIDE. Below shows two images where in the 1st image shows the status of the simulation when the system is OFF and the second image shows the status of the system when it is ON.

ON
ON

OFF
OFF

Outputs
Circuit	RAM Table
CIRCUIT	RAM_TABLE
CRO	Serial Monitor
CRO	ON
Functionality
When the two switches are closed, the first LED glows indicating the actuation of the system and the heater.
Next the analog input from the temperature sensor is received and digitized.
The digitized temperature input is visualized using Pulse Width Modulation.
The corresponding temperature values based on the digitized temperature input is transmitted by the UART protocol. Here the data is displayed on the serial monitor.
