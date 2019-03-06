# 6bits RDAC Design and Simulation
This is a Final Project of Introduction to IC Design class.
* A 6-bit RDAC(R-digital to analog converter) with a unity-gain amplifier. 
* The unity-gain amplifier is used to drive a capacitive load of 3 pF. 
* The voltage levels on the resistor string are 2.5 V and 5 V.
* PMOS transistors as pass transistors in the RDAC and use NMOS input differential amplifier to fit the input range.

# Schematic Circuit Design
* The design of the 6-bit RDAC circuit is based on a 3-bit RDAC circuit as the figur below.
* But the 6-bit RDAC circuit will contain 6 layers :
  * 64 MOS in the 1st layer
  * 32 MOS in the 2snd layer
  * 16 MOS in the 3rd layer
  * 8 MOS in the 4th layer
  * 4 MOS in the 5th layer
  * 2 MOS in the 6th layer
* The input will be <img width = "30%" height = "30%" src = "https://github.com/willy850329/6bits-RDAC/blob/master/6-bit_RDAC_img/input.png">

<img width = "500" height = "500" src = "https://github.com/willy850329/6bits-RDAC/blob/master/6-bit_RDAC_img/schematic.png">

# Performance Summary
<img width = "500" height = "500" src = "https://github.com/willy850329/6bits-RDAC/blob/master/6-bit_RDAC_img/performance.png">


******* For more information, please refer to the pdf file ****************************
