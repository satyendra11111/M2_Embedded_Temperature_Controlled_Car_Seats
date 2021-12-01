
# M2_Embedded_Temperature_Controlled_Car_Seats
Project Based On The Heat Control System Of Car Seat
The Temperature control system in this project is basically used to control the temperature of a car seat. When a user or driver of the car gets seated on a car, the button sensor gets activated. After that, the user gets access to turn on the heater. The temperature sensor keeps monitoring the temperature and sends the analog value to the microcontroller. The microcontroller processes the analog input of the temperature sensor and outputs a temperature value through serial communication. All the activities of the control system are done on a microcontroller called Atmega328.

### SIMULATION:>



The functionality of the heat control system is coded in embedded c and the working is demonstrated using simuation in a software called SimulIDE. Below shows two images where in the 1st image shows the status of the simulation when the system is OFF and the second image shows the status of the system when it is ON.

### ON

![Gif (1)](https://user-images.githubusercontent.com/94337093/144182795-892c5829-ecd9-464e-9b6a-342f43967548.gif)

### OFF

![Simulation_OFF](https://user-images.githubusercontent.com/94337093/144200480-ebcfc35a-62b5-4ed9-8816-58f8d810c945.png)


#### Outputs

|Circuit| RAM Table|
|:--|:--:|
|![Circuit (1)](https://user-images.githubusercontent.com/94337093/144183093-92dc1485-cf51-4490-8e0f-71589b5d48e1.gif)|![RAM_table (1)](https://user-images.githubusercontent.com/94337093/144183831-d442492d-c37b-42b4-89b9-1abbcb8627af.gif)|
|CRO|Serial Monitor|
|![Oscilloscope (1)](https://user-images.githubusercontent.com/94337093/144183934-4beff1f7-9f47-49d3-89b6-8ae073d1052c.gif)|![Serial_Monitor](https://user-images.githubusercontent.com/94337093/144183970-60966b15-ee18-4cfa-9360-3eedea62e271.gif)|

### Functionality


When the two switches are closed, the first LED glows indicating the actuation of the system and the heater.
Next the analog input from the temperature sensor is received and digitized.
The digitized temperature input is visualized using Pulse Width Modulation.
The corresponding temperature values based on the digitized temperature input is transmitted by the UART protocol. Here the data is displayed on the serial monitor.


### CI and Code Quality

|Code Quality Score|Code Grade|Codacy|
|:--:|:--:|:--:|
|![Code Quality Score](https://api.codiga.io/project/30146/score/svg)||![Code Grade](https://api.codiga.io/project/30146/status/svg)||[![Codacy Badge](https://app.codacy.com/project/badge/Grade/16717604904c4660bd6d2c39bced1115)](https://www.codacy.com/gh/VatsalKr/M2_Embedded_Temperature_Controlled_Car_Seats/dashboard?utm_source=github.com&amp;utm_medium=referral&amp;utm_content=VatsalKr/M2_Embedded_Temperature_Controlled_Car_Seats&amp;utm_campaign=Badge_Grade)|
