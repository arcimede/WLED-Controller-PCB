# WLED-Controller-PCB
a PCB for the ESP32 WLED Software including a Power Supply

I needed a LED stripe ilumination for my stair of my hose. But the controller i bougth did not realy work well...

Finally I took an ESP32 NODEMCU and layouted a PCB fitting in a 35mm DIN rail case.

Here the result!

The LED power is the same as Vin, so take care to choose the right poer supply! The control signal is driven by

a HCT7414 IC. this garantees the correct driving levels for the LEDs on the output and the rigth input level for the

ESP32 signals! You have to make sure to use a HCT type!

For programming please remove the jumper J302 so the ESP32 module is powered by the USB connection. After programming you

have to remove the USB cable and you must insert the jumper J302!

The documentation: http://www.systech-gmbh.ch/Files/Other/PDF/ESP32-WLED-D35-V11-za.pdf
