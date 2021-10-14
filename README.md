# PWM-LED-Controller

A custom LED controller created using PCA9685 and SOIC-8 mosfets.

Has 16 channels availble. can be used by common anode LEDs. 
Works with single color sttrips or CCT, RGB, RGBWW, RGBCCT or any combination their of.

IDC connection and code compatible with the URC home automation system being developed by Jon Oxer of superhouse.tv

Video Demo: https://youtu.be/LjtU8Q2ln_A

<a href="https://github.com/austinscreations/PWM-LED-Controller/blob/main/Pictures/Info%20Graphic.png?raw=true"><img src="https://github.com/austinscreations/PWM-LED-Controller/blob/main/Pictures/Info%20Graphic.png?raw=true" alt="Info Graphic" width="400" height="324"/></a>


<a href="https://github.com/austinscreations/PWM-LED-Controller/blob/main/Pictures/Dimensional%20Drawing.png?raw=tru"><img src="https://github.com/austinscreations/PWM-LED-Controller/blob/main/Pictures/Dimensional%20Drawing.png?raw=tru" alt="Dimensional Drawing" width="400" height="245"/></a>

2021-10-13 --- added files for 3d printable cases that can hold the PWM Controller and the room8266 - an esp8266 based controller with POE and ethernet support for controlling the PWM controller via an IDC i2c connection

cases were printed as is with no supports, tehy have interconnecting dove tails and keyslots for mounting each device / case uses 4x m3 jam nuts and 2x m3x10 hex head screws and 2x m3x25 hexhead screws - a small pice of pmma fiber optic is used for the status light on the room8266 case.

2021-08-13 --- added 2 types of code, one requires you to change the config for your needs. the other config is done via OTA+AP mode. code tested on esp8266, both codes work on esp8266, the OTA shoudl work on esp32 whiel the other would need wifi changes for that to work. for the OTA to work correctly when uploading via arduino IDE, be sure to set upload to clear all flash contents.

2021-08-05 --- added files for Info graphic, and dimensional drawing - along with 1:1 pdf drawing. added pcb files and gerbers from first production run.
