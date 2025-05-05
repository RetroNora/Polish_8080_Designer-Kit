# 8080 (?) Designers Kit (?)
It seems to be a Z80 based, CP/M running computer, with FDD support, and RS232 serial interface. And a test board with 8085 CPU (although it is branded by '8080')
![alt text](https://github.com/RetroNora/Polish_8080_Designer-Kit/blob/main/PICS/cage_front.jpg)

This is the set of cards I found inside:

## Simple Riser Card
![alt text]((https://github.com/RetroNora/Polish_8080_Designer-Kit/blob/main/PICS/HiRes/Riser_front.jpg))

Just a passive riser :)


## Z80 (SIB-80) Card
![alt text](https://github.com/RetroNora/Polish_8080_Designer-Kit/blob/main/PICS/HiRes/Z80_front.jpg)

Seems to be the heart of the machine.
With:
- Z80 CPU,
- 64k RAM,
- 2k ROM.

The ROM mentions CP/M 2.2

![alt text](https://github.com/RetroNora/Polish_8080_Designer-Kit/blob/main/PICS/CPM.jpg)


## 8085 Card
![alt text](https://github.com/RetroNora/Polish_8080_Designer-Kit/blob/main/PICS/HiRes/8085_front.jpg)

This card seems to be the test card for 8080/8085 testing/debugging. 

This card comes with:
- 8085,
- 8255 - it seems to control the CPU and it is connected to system bus,
- 2K of SRAM,
- 2K of ROM.

Both SRAM and ROM are addressed by 8085 but their databus is connected to Port A of the PPI.


## ROM Card
![alt text](https://github.com/RetroNora/Polish_8080_Designer-Kit/blob/main/PICS/HiRes/ROM_front.jpg)

This card is a little mistery to me, there is less Z80 address lines connected to the backplane then the address space of the 2716s here.


## FDC Card
![alt text](https://github.com/RetroNora/Polish_8080_Designer-Kit/blob/main/PICS/HiRes/FDC_front.jpg)

An 5,25 inch floppy controller board based on WD2797A-PL


## DISC DRIVER Card
![alt text](https://github.com/RetroNora/Polish_8080_Designer-Kit/blob/main/PICS/HiRes/DISCDRIVER_front.jpg)


## UART Card
![alt text](https://github.com/RetroNora/Polish_8080_Designer-Kit/blob/main/PICS/HiRes/UART_front.jpg)

UART card based on 8251. It seems to be hardwired for 19200 bps. The back of the unit has two DB9 for serial connection. One is simple RX/TX/GND and the second one has flow control implemented.
