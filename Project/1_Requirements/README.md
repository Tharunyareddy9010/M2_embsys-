## Description:
This is a project, which aspects the design of an blind stick which involves the ultrasonic sensor, led, and buzzer. The embedded system when installed and given to the blind people while going out or travelling, will sense the obstacles in their way and alerts them before they hurt. The Arduino Uno continuously checks for the communication from ultrasonic sensor. The led will be ON when the obstacle ahead and the distance from ultrasonic sensor are satisfied. Otherwise the led will be in OFF position.
## Components:
•	Arduino Uno.</br>
•	Ultrasonic (HC-SR04).</br>
•	LED/ any light source.</br>
•	221 Ohms resistor.</br>
•	Buzzer.</br>
•	Bread board(optional).</br>

## Requirement Modelling:
#### High Level Requirements:
|ID|	Description|
|:---|:---|
|HR01	|Sensor shall detect person.|
|HR02	|Buzzer shall turn on.|
|HR03	|Buzzer shall turn off.|

#### Low Level Requirements:
|ID	|Description|	HLR ID|
|:---|:---|:---|
|LR01|The sensor detects whether the surrounding of a person has any obstacles.|HR01|
|LR02|The LED will be turned off if there is no obstacle ahead.	|HR03|
|LR03|The controller(Arduino) turns on the LED if the sensor detects the obstcale and if a person is detected ahead of it.|HR02|

## Working:
The power supply is given to the system then the Arduino UNO will on and the ultrasonic sensor starts detecting obstacles. When the obstacle is ahead  then the information  is sent to Arduino and the LED will be on. Whenever, LED is on then the buzzer will give the sound so that the blind people will be alert. If  the LED is off  then the buzzer goes off  so that the people can  start moving in their way. This process will goes on until and unless the power supply is given to system.

## Applications:

•	Help blind people to easily walk to destination.</br>
•	Help blind people for obstacle detection.</br>
•	Alert blind people about dig.</br>
