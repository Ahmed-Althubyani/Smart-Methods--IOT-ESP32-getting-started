# Wasdom ESP32 starting guide
1- Download and install Arduino IDE from: https://www.arduino.cc/en/software  
2- Open Arduino IDE then go to File > Preferences  
3- In Additional Boards Manger URLs add: (https://dl.espressif.com/dl/package_esp32_index.json) then click OK  
4- Open Boards Manager by going to Tools > Board > Boards Manager  
5- Type "esp32" then install "ESP32 by Espressif Systems"  
6- plug the ESP32 to your pc  
7- Choose the board by going to Tools > Board > ESP32 Arduino > WEMOS D1 MINI ESP32  
8- If Tools > Port is not available check for the computer Device Manager > other devices > CP2104 USB to UART Bridge Controller for update driver  
9- if the above did not work download the driver from here: https://www.silabs.com/developers/usb-to-uart-bridge-vcp-drivers  
10- Unzip the file and copy its address then go to Device Manager and click update deriver on CP2104 USB to UART Bridge Controller  
11- Choose Browse my computer for drivers then add the address then install  
12- Now in Arduino IDE go Tools > Port > COM3  
13- Finally to Test the Wasdom ESP32 go to File > Examples > Basics > Blink  
14- Now Click upload to see the led on Wasdom ESP32 blink
