# ByteESP32

![6302905872166272561](https://github.com/user-attachments/assets/18ca9eef-3020-46b2-ae01-7664e94c5664)
It uses an ESP8266 to attack a WiFi network using Deauther && || Evil-Twin AP method || with a 0.96 oled display

## FEATURES :
* Deauthentication of a target WiFi access point
* Evil-Twin AP to capture passwords with password verification against the og access point
* It can do both attacks at the same time, no toggling of the deauther is required.
* it has a 0.96 oled display with adimation which shows the device is powered on if u are using a 3.3v battery without a power adaptor

  ## DISCLAIMER
The source code given in this public repo is for educational use only and should only be used against your own networks and devices!<br>
Please check the legal regulations in your country before using it.



## Install using Arduino IDE
1. Install Arduino IDE
2. In Arduino go to `File` -> `Preferences` add this URL to `Additional Boards Manager URLs` ->
   `https://raw.githubusercontent.com/SpacehuhnTech/arduino/main/package_spacehuhn_index.json`  
3. In Arduino go to `Tools` -> `Board` -> `Boards Manager` search for and install the `deauther` package  
4. Download and open (ByteESP32) https://github.com/Sumitshah00/ByteESP32/ with Arduino IDE
6. Select an `ESP8266 Deauther` board in Arduino under `tools` -> `board`
7. Connect your device and select the serial port in Arduino under `tools` -> `port`
8. Click Upload button
