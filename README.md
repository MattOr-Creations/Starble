# Starbie
<img width="608" height="527" alt="image" src="https://github.com/user-attachments/assets/07f62c86-4063-4f4d-b944-1d6177f37175" />

A motion controlled digital pet with 2 custom keys, basically a Tamagotchi, built for the PCB design week of the 10 week Half Life program.

## Why Starbie?
It's a very interesting build, I haven't really experimented much with motion sensors and wanted to know how to use them, and having the ability to customize the Tamagotchi just makes it even better, that's why I included my cat as the digital pet.

## Parts
+ XIAO ESP32-C3 microcontroller
+ 128x64 OLED display (I2C)
+ MPU6050 accelerometer/gyro for tilt and shake detection
+ DHT11 temperature and humidity sensor
+ 2 buttons

## Customizations
+ Changed the template sprite for my 32x32 sprite of my cat, made using Aseprite and converted with image2cpp.
+ Modified the 4 menu items to match my cat's preferred actions: NAP / PLAY / FEED / PET -> NAP / CHASE / TREAT / PET
+ Most actions give increased hunger(Hardmode??)

## PCB
Used KiCad for the schematic and PCB design
<img width="1843" height="864" alt="SchematicPNG" src="https://github.com/user-attachments/assets/a01b7d77-61fd-4fdf-a05a-f1fce16eeb56" />
<img width="705" height="654" alt="PCBIMG" src="https://github.com/user-attachments/assets/f3ab8610-2f44-445d-afc1-88bc2a7df153" />

## Credits
Custom libraries and based on the Starbie guide by SharKingStudios:https://github.com/SharKingStudios/Starbie
