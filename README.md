## GBA SP Charge + Audio (Minipanel)

Simple mod board to add usb charging to the GBA while maintaining audio output provided by EXT2 connector. 
Other folks have created similar projects before, but none that are compliant enough to work for:
- USB-C charging on any USB cable (C <-> C, A --> C)
- USB-C Audio Accessory support

Since the audio accessory standard and PD standard both use the CC lines, a dedicated IC is required to 
negotiate charging and detect when headphones or a 3.5mm jack adapter are connected.


TODO: assembly pictures

TODO: thanks to prior GBA schematic and usb-c projects

TODO: project next steps, active ADC for audio host, etc
