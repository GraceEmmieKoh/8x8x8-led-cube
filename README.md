# 8x8x8-led-cube
Eagle project for 8x8x8 LED Cube (v5) PCB, using ESP32

This project was largely inspired by chr's LED Cube Instructables build here: https://www.instructables.com/Led-Cube-8x8x8/

I used an ESP32 as the main microcontroller. The LED's are controlled by switching on/off columns with 74HC595's, and by alternating between layers with PN2222's. The circuit requires a 12V power supply, which is stepped down to 5V using a LM2678-ADJ.
The cube is connected to the PCB through nine 8-pin JST connectors. Eight connectors are used to control each column (8 * 8 = 64), and one connector is used to control between each layer.

This project is currently unfinished. I plan to add a Fusion 360 CAD model to house the PCB, as well as code for the cube.
