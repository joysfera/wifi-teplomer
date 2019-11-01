# wifi-teplomer
PCB for my WiFi thermometer based on AI Thinker ESP8266-07 module. Can be used for any ESP8266 project. Below you'll find the few necessary components to get it running. SMD resistors are sized 0805, one SMD capacitor is 0805 (100 nF) and the other one is 1206 (100 µF).

Microswitch, barrel jack and the stereo jack connector are from https://www.official.cz/

All you really need to get it up and running is just three resistors - 10k, 10k and 1k and that button (that drives GPIO 0 to ground, useful for flashing).

You can power it either with stable 3.3 V voltage (up to 300 mA) via separate pins at left bottom corner, or with any voltage via the barrel jack: then you need to also add either linear voltage regulator like the SMD HT7333 or anything THT in the three holes next to HT7333 - I use a step-down converter module.

![bottom](https://github.com/joysfera/wifi-teplomer/blob/master/PCB_bottom.png)

![top](https://github.com/joysfera/wifi-teplomer/blob/master/PCB_top.png)
