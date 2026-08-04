## August 2nd: Beginning the project!
I'll be using the ESP32-C3 developed by expressif as the MCU/brains of this devboard!
I began researching the datasheet and forgot that I had something to do. I quickly installed flash memory for the esp32-c3 using a quad spi module while also adding a button for setting cs to low and adding decoupling capacitor for the Power of the fash memory. 
Current Schematic:![image](https://cdn.hackclub.com/019fc4cf-07d3-77a1-893f-f0d826e25eab/paste-1785713329872.png)
### Lapse Link: https://lapse.hackclub.com/timelapse/lOYapriT_lcY

## August 3rd: Adding USB along with battery
I added a USB C Receptacle along with starting to implement battery charging but I don't think its done yet. It was a pain to go through all of the datasheets and understand each component and wiring them but it is what it is..
Current Schematic: ![image](https://cdn.hackclub.com/019fc9f6-bb51-7d2d-b0cd-7582e0d6a316/paste-1785799817867.png)
### Lapse Link: https://lapse.hackclub.com/timelapse/0mVoWRxlGfGC

## August 4th: Adding pull up resistorsa and EN reset button
Went through the datasheet again and realized that certain pins needed to be pulled up along with the CHIP_EN being pulled high or low turning off the chip so I made that into a button
![image](https://cdn.hackclub.com/019fce9e-e7fd-75f1-8205-ea0275a373bb/paste-1785877947883.png)
### Lapse Link: https://lapse.hackclub.com/timelapse/Z4B6Hk9UXLxQ