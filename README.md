# Home-Automation-using-ESP8266-IOT-Project
Home automation IOT Project using ESP8266 and relay. A system that you will be able to control using your mobile phone/PC. A system that will automate the electronic and electrical tasks within the home. We can control almost everything using our mobile. We can control it by connecting to same WiFi. So why not we can control our home electronics instruments like light fan AC etc using Home Automation Using ESP8266 and in Arduino IDE.

Components Used:
1. NodeMCU ESP8266
2. Relay Module
3. Jumper Wires

Connections:
1. To Connect with AC line we need a small wire. The neutral line will be connected directly to the bulb. Live wire first go to COM port of Relay. Then one small wire will be connected to the bulb from Normally Open(NO) Port.
2. Connection with ESP8266 NodeMCU is very simple one. Just we have to connect 3.3V to the VCC and Ground to the GND and we have to connect data line to D2.

Diagram:
For Simple understanding we have used a 9V battery instead of AC supply.


![Home_automation_ESP8266](https://user-images.githubusercontent.com/95209278/144179736-f0e30dd4-c68e-42d9-a763-420e8cd97b60.JPG)

Code:
1. How to control ESP8266 via HTML page:
The web interface is designed using simple HTML.
Using hyperlinks, led ON or led OFF functions are called.

2. How to connect ESP8266 to home WiFi Router:
Just add your WiFi router Ssid name on Line 13 and password on Line 14.

3. After running the code open the Serial Monitor and you will get a IP Address. Simply just copy and then paste the IP Address on your browser and there you are you can now control home appliances using your mobile phone.



