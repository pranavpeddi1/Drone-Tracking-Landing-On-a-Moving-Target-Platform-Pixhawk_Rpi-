# Drone-Tracking-Landing-On-a-Moving-Target-Platform-Pixhawk_Rpi-

>>Quadcopter using Pixhawk mini–Flight Controller along with Raspberry pi-3 Model B as a Companion computer is built. 

>>U-blox GPS is used for Pixhawk Mini Flight controller for better GPS Values. 

>>GPS Coordinates of Mobile Robot Platform will be received by Quadcopter through a receiver of 3DR Radio Telemetry Module.

>>Following Figure Shows the Quadcopter that I built for this Autonomous Tracking and Landing 

![image](https://user-images.githubusercontent.com/54229744/151697057-287f3f4e-0bcf-4f20-b8bc-469ab97473a0.png)

Fig : Quadcopter 

>>I have used Ardupilot Firmware in the Pixhawk Mini Flight Controller. 

>>For Autonomous control of Flight Controller without Radio Transmitter I used Dronekit python API which sends the high-level commands to the Flight controller through the UART Interface between Raspberry Pi and Pixhawk Mini. It uses the MAVLINK protocol for communication.

>> Following Figure shows the Algorithm that is Implemented using DroneKit Python API.

![image](https://user-images.githubusercontent.com/54229744/151697221-58c4406a-06bf-41c5-9a9c-4e234b84bdfe.png)

>> In this experiment we set the mobile robot platform speed of 0.05 meters per second and 0.1 meters per second.

>>This Experiment is performed several times and every time drone is landed with an offset of 0.4 to 1 meter range from the center of the platform.



![alt text](https://github.com/pranavpeddi1/Drone-Tracking-Landing-On-a-Moving-Target-Platform-Pixhawk_Rpi-/blob/main/Drone_Land_Part1_Giff.gif)
![alt text](https://github.com/pranavpeddi1/Drone-Tracking-Landing-On-a-Moving-Target-Platform-Pixhawk_Rpi-/blob/main/Drone_Land_Part2_Giff.gif)
