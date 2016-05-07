Yabbo is a general purpose BLE board with Over The Air (OTA) Device Firmware Update (DFU) built-in. 

(Yabbo stands for "Yet Another BLE Breakout" - in the naming tradition of Unix tools like yacc.) 

Yabbo is based on the RayTac Nordic nRF51822 module MDBT40. 

There are many nRF51 BLE breakout modules out there, and they vary from being a pain to use (Chinese modules with dual 1.27mm headers) to expensive mbed based ones which have a secondary uC to upload code via USB. 

My goal is to create < $15 board that comes with bootloader that supports OTA DFU so you can straightaway upload code without any other hardware. For this to work, I also plan to develop cross platform tools (Win, OS X, Linux) to upload the firmware. (You will also have the option to upload code via SWD.) 

I am thinking that Yabbo will have placeholders for (optional) accelerometer, LDR, MEMS Mic, and a buzzer. 

This is an Open Source Hardware/Software project. 

https://hackaday.io/project/11590-yabbo
