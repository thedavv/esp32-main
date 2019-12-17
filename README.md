# esp32-main
Main esp32 code and tutorials


 **Tutorial:**  

 **1. Install Arduino IDE:**  
   **1.1** Download Arduino IDE from: https://www.arduino.cc/en/main/software    
   **1.2** Choose **Windows Installer, for Windows XP and up** for Windows OS.

 **2. Setting up Arduino IDE:**  
   **2.1** Install packages with help of tutorial:  
      https://randomnerdtutorials.com/installing-the-esp32-board-in-arduino-ide-windows-instructions/  
      Steps 1-5 in **Installing ESP32 Add-on in Arduino IDE**   
   **2.2** Set up ESP board as show in picture: 

   ![alt text](https://github.com/CyberPunkLabBratislava/esp32-main/blob/master/pictures/ArduinoIDEConf.png)  

**3. Uploading Code to ESP32**  

   **3.1** Connect ESP to Arduino board:  
      Arduino 5V  -> 5V  ESP  
      Arduino GND -> GND ESP  
      Arduino RX  -> RX  ESP  
      Arduino TX  -> TX  ESP  
      Arduino GND -> IO0 ESP  

   ![alt text](https://github.com/CyberPunkLabBratislava/esp32-main/blob/master/pictures/connected.png)  

   If the Arduino board don't have removable Microchip(Atmega328P), RST pin needs to be shorted to GND:  

   ![alt text](https://github.com/CyberPunkLabBratislava/esp32-main/blob/master/pictures/connectedNonRemovable.png)  

   **(If you are using different external programmer (other then Arduino board) pin configuration will be same as on top.)**  

   **3.2** Uploading code:  

      For uploading code just hit **Upload** button in Arduino IDE and code will start to compile.  
      After finishing compiling Arduino   IDE will try to upload code to **ESP board**.  

      If the output in console is simillar to this:  

   ![alt text](https://github.com/CyberPunkLabBratislava/esp32-main/blob/master/pictures/CodeUpload.png)  

      Arduino IDE is waiting for reseting of the board, just press Reset on ESP board.:  

   ![alt text](https://github.com/CyberPunkLabBratislava/esp32-main/blob/master/pictures/connectedRst.png)  

      After this code should start to upload to ESP board.



