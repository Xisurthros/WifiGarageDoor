# Wifi Controlled Garage Door
> Control your garage door with an ESP8266

### Important
> Change 'ssid' and 'password' in the code to your ssid and password.\
> If you use the same wifi module as I do. It can only connect to 2.4GHz. It will **NOT** work on 5GHz.\
> Replace the power from the relay to connect with your garage door PowerIn pin and connect GND to the garage door GND pin.

### Parts
> Controller: NodeMCU 8266
> * https://www.amazon.com/HiLetgo-Internet-Development-Wireless-Micropython/dp/B010O1G1ES
> * I used the NodeMCU 8266.
> * You can sub out any 8266 or 82 WiFi chip controller.
>
> Relay: Elegoo 4 Channel Relay
> * https://www.elegoo.com/products/elegoo-8-channel-relay-module-kit
> * I used the 4 channel version of this realy. As I plan to add future automation.
> * For this project you only need a 1 channel relay. You can sub an 5V relay into this project.
>
> Power: Elegoo Power Supply Module
> * https://www.amazon.com/JBtek-Breadboard-Supply-Arduino-Solderless/dp/B010UJFVTU
> * The one I used came in an Elegoo Starter kit that was purchased a long time ago.
> * This is the closest to what I useed in this project.
> * You do not need a separate power supply for the relay as you can supply power from the board itself. I just like the extra power supply
>

![image](https://user-images.githubusercontent.com/76274780/184509127-215644ae-b091-4c1e-9964-ccf6b79b3adc.png)

### Extras
> The .ckt files are actual copies of the images above where the circuits can be viewed and edited in Cirkit Designer.\
> This program can be downloaded [here](https://www.cirkitstudio.com/).\
> This part isn't important for getting this circuit to work. This is just the software I used to model the circuits.