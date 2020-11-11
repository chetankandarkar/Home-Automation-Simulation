# Home-Automation-Simulation
Proteus Simulation Project

Aim : Simulate Home Automation using Proteus Software

Require Software  :
- Proteus 8  
- Arduino

Components Use : 
- Arduino Uno
- Bluetooth Module HC-05	
- Diode 1N4007
- Transistor 2N2222
- Relay
- Lamp
- AC Source
- DC Source
- Resistors
- Motor

Circuit Connection : 

![](Images/Circuit%20Connection.png)

Procedure :
1) Install Proteus 8 and Arduino Software
2) Add Arduino and Bluetooth Library file in Proteus software
3) Open Proteus software click on new project
4) Select Schematic Capture and add Devices on it
5) Do the Circuit Connection as per given
6) Open Arduino Software and Write a code 
7) In File section click on preferences and select on compilation
8) Run the code
10) After Successful compiling we get location of ino.hex file 
11) Copy the path location of ino.hex file 
12) Open Proteus 8 project Double Click on Arduino Paste path location of ino.hex file in Program file 
13) Open Bluetooth Setting on computer and add COM Port 
14) Double Click on Bluetooth module in Proteus Software Select same COM Port in Physical port section
15) Now Create Bluetooth Application for create buttons to operate simulation using [https://appinventor.mit.edu](https://appinventor.mit.edu)
16) Now Run the Proteus project and Connect the Bluetooth using Bluetooth Application
17) Click on Buttons on application and see the Simulation on Project Screen

Arduino Software Code:

![](Images/Arduino%20Software.png)

Bluetooth Application :

<img src="Images/Bluetooth%20Application.jpg" width="200"/>

Working :
- After Running Project on Proteus software Connect Bluetooth application to Bluetooth of Computer.
- When Click on “Light On” Button then Lamp of Proteus software will turn On. 
- When Click on “Light Off” Button then Lamp of Proteus software will turn Off. 
- When Click on “Fan On” Button then Fan of Proteus software will turn On. 
- When Click on “Fan Off” Button then Fan of Proteus software will turn Off. 
- When Click on “Both On” Button then Light and Fan of Proteus software both will turn On. 
- When Click on “Both Off” Button then Light and Fan of Proteus software both will turn Off.

Video Demonstration :
[Click Here](https://youtu.be/raa76qWIKoM)

Result :
Hence Perform Simulation of Home Automation Successfully .
