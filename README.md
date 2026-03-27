# EXPERIMENT--06-IoT-Based-Relay-Control-System-Using-LoRaWAN-and-Application-Server
## Aim
To configure a LoRaWAN end device and monitor IR sensor data using a network server and dashboard visualization.

## Components Required
- LoRaWAN End Device-STM32
- LoRaWAN Gateway
- Application Server Dashboard
- Serial Port Utility
- Development Tools (STM32CubeIDE, STM32CubeProgrammer)

## Procedure
1. Open STM32CubeIDE and import the project from the realy-control project directory.
2. Select the LoRaWAN End Node project for the NUCLEO-WLE5JC board.
3. Clean all previous build files using the Clean Project option in the build configuration.
4. Build the project to generate the firmware files.
5. Flash the compiled firmware into the STM32 board using STM32CubeProgrammer with baud rate set to 9600.
6. Open the network server console and login using your registered email ID and password.
7. Register the device by selecting Device Types and adding the LoRaWAN device in the network server.
8. Open the Serial Port Utility  give the AT commands and verify device connection through the serial port utility
9. Create a dashboard on the application server by clicking the Add Dashboard option.
10. Add widgets and commands to visualize the relay status data.
11. Send control commands from the dashboard to control the relay.

## Output
### 1. Serial Port Utility – Network Server Connection
<img width="1919" height="1079" alt="image" src="https://github.com/user-attachments/assets/8055c3d2-201c-4b92-9d38-04bd59c84fe6" />

### 2. Network Server – Recent Events
<img width="1906" height="1063" alt="image" src="https://github.com/user-attachments/assets/b5698e51-f732-413c-b453-9e143fe684e1" />
<img width="1919" height="1038" alt="image" src="https://github.com/user-attachments/assets/a33b453c-6b90-4a77-9cac-2c192fd9e699" />

### 3. Dashboard Command Sending
<img width="1914" height="970" alt="image" src="https://github.com/user-attachments/assets/2942ddd0-cd73-471a-83a5-f292b969d247" />

### 4. Relay Status Dashboard Output

### Bulb ON → Relay ON  
<img width="1919" height="1020" alt="image" src="https://github.com/user-attachments/assets/8b3ad4b1-4c2b-460a-a77e-35630a5faced" />

### Bulb OFF → Relay OFF
<img width="1918" height="1012" alt="image" src="https://github.com/user-attachments/assets/9c0825a6-cf33-4d18-8547-e6c55aecb322" />


## Conclusion
The experiment demonstrates successful relay monitoring and control using LoRaWAN communication with real-time visualization on the dashboard.
