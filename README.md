# Current and Voltage Generator - Advantest R6142/R6144

![obraz](https://github.com/user-attachments/assets/2b5ced1c-ffb3-4773-8a42-84aace67b84a)

## Documenatation

* [Advantest R6142/R6144 - Instruction Manual](Advantest_R6142_R6144_Instruction_Manual.pdf)
* [Advantest R6142/R6144 - Maintenance Manual](Advantest_R6142_R6144_Maintenance_Manual.pdf)

## Firmware / Calibartion data

### U3 - SIS-003160 - Firmware ROM

![image](https://github.com/user-attachments/assets/dba59db6-2c98-41a3-9c0f-edc2aa0fa1b8)

* SIS-003160: BIN [Advantest_R6142_R6144_U3_v02-04_M27C512_15F1_DIP28.bin](firmware/Advantest_R6142_R6144_U3_v02-04_M27C512_15F1_DIP28.bin)
* SIS-003160: HEX [Advantest_R6142_R6144_U3_v02-04_M27C512_15F1_DIP28.hex](firmware/Advantest_R6142_R6144_U3_v02-04_M27C512_15F1_DIP28.hex)

### U5 - AT59C11- Calibartion data on 4-Wire Serial EEPROM

![image](https://github.com/user-attachments/assets/d361c846-d7b7-44ef-b5c9-784dd7870cb3)

* U5 - Calibartion data HEX [Advantest_R6142_R6144_U5_AT59C11.hex](firmware/Advantest_R6142_R6144_U5_AT59C11.hex)

#### Replacemt part

https://www.eevblog.com/forum/repair/advantest-r6144-voltcurrent-gen-bad-output-on-lower-ranges/msg5382893/#msg5382893

`
Hi,
I used a Beeprog (ELNEC) for reading and programming the AT59C11. The 93C46 is not an  exact compatible device. But you can try to replace the original AT59C11 in the R6142 with a AT93C46, which you can program with your programmer. As long as the R6142 will be used to read only the eeprom (normal operation), it will work. And you can write the content available above to the AT93C46 with your programmer.
BR,
Gyorgy
`

HEX file for U5 was downloaded from EEVBlog:
* https://www.eevblog.com/forum/repair/advantest-r6144-voltcurrent-gen-bad-output-on-lower-ranges/msg4479262/#msg4479262

## Author

* Paweł 'felixd' Wojciechowski - [FlameIT - Immersion Cooling](https://flameit.io)
