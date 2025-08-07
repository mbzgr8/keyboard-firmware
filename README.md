# README  
*This repo contains QMK firmware + VIA support for a TKL or 80% keyboard with an extra f13 key in an ANSI layout.*  
*The PCB and STL case files can be found here as well.*<br>    
*Manufacturer: [Marcus Zaens](https://github.com/mbzgr8)*  
### Hardware used:
* Pyratype PCB
* [RP2040 Pro Micro](https://www.amazon.com/Rp2040-Development-Dual-Core-Supports-Python/dp/B0FBS8R3G1/ref=sr_1_3?crid=23R0KFXC1JYY&dib=eyJ2IjoiMSJ9.OYm7dv190fl2e0bBdTu_A7jPaT9skWXiFTOOQxBleNhgXyELMuBr4fsGGwUMkBFo2JyEDWwPn_JKyuBYyB119x1nlZtc1tkQO_in1sDSpBJZcL_6j4ziKG9oi1-63EvThKxvT0KvL1vbD29hE82ieXYYIXoTGxOEzcQlaPYMrapP28NUH3-UxDm6loO4Vvw0APo2jZavs5cnz3CZk5VPFpJalNm2CnyvSfw4YZW3T_QSb4QqyZQJXtwhO1tUI41oO0s0b5SX-szipMNMLJibVeJbjRn1OIOjPa6anHLqS6Q.PKKn4kqPUeqFUDg_9P9DJlLy2ComMHfYfNx7hXzXJkE&dib_tag=se&keywords=rp2040+pro+micro&qid=1754536727&s=electronics&sprefix=rp2040+pro+micr%2Celectronics%2C142&sr=1-3)
* [1N14148 DO-35 Diodes](https://www.digikey.com/en/products/detail/onsemi/1N4148/458603)
* [Gateron Sea Salt Smoothie Linear Switches](https://www.amazon.com/GATERON-Smoothie-Keyboard-Pre-lubed-Mechanical/dp/B0CYL16PM6/ref=sr_1_1_pp?crid=AMPQ5S3LEA0T&dib=eyJ2IjoiMSJ9.s4XYtsFTLBIC6uNLeZXx2CcCMiUsXWuTqDewkwabyOU8PmoZBCXX32NAuKHGEk5_n_ivpMBl4BYRCRVJIEiQVITrTAbecOz6vV7UoJLEPo5t29pWUPHwvU-DOc6jl4Ve.VirT---6raKau63VBSV0KktMcQoo-Hyp0QVi4Pl9b78&dib_tag=se&keywords=gateron%2Bsea%2Bsalt%2Bsmoothie%2Bswitch%2Bset&qid=1754536978&sprefix=gateron%2Bsea%2Bsalt%2Caps%2C131&sr=8-1&th=1)  
### NOTES: 
* YOU WILL HAVE TO HIJACK THE TWO GND PINS BENEATH GPIO PIN 1 AND REWIRE TO GPIO PINS 16 and 21 (ON FRONT) OR GPIO PINS 12 AND 13 (ON BACK)
* You will need 1 PCB, 1 RP2040 Pro Micro, 88 DO-35 diodes, 88 mechanical switches, wire to hijack the pins, flush cutters, and solder
