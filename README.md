# SODA IDE
Compact Flash Card Interface for MSX based on [SC729 RCBus Compact Flash Module]( https://smallcomputercentral.com/sc729-rcbus-compact-flash-module/) originally designed by [Tadeusz Pycio](http://www.vtsys.pl/interface-compact-flash/) and [Beer IDE 232](https://github.com/b3rendsh/msxdos2s) by b3rendsh 

![Picture](/doc/Soda_IDE_top.jpg)
### BILL OF MATERIALS

#### Semiconductors

| Reference | Value | Description            |
|:---:|:-------: |:----------------------------------------- |
|  U1 | 27C512   | EEPROM 64Kb x 8 (512kbits)                |
|  U2 | 74HCT32  | TTL chip, can be either LS, HC or HCT     |
|  U3 | 74HCT74  | TTL chip, can be either LS, HC or HCT     |
|  U4 | 74HCT138 | TTL chip, can be either LS, HC or HCT     |
|  U5 | 74HC245  | TTL chip, can be either LS, HC or HCT     |
|  Q1 | BC548    | NPN transistor                            |
| LD1 | --       |     Diameter 3.0mm, Red                   |
|  D1 | 1N4148   | Fast diode, Sillicon (alternatives 1N914) |



#### Capacitors

| Reference | Value | Description            |
|:---:|:-------: |:----------------------------------------- |
|C1,C2,C3,C4,C5| 100nF | Capacitor, Ceramic disc or Polyester |
|C6| 100uF/16V | Electrolytic Capacitor (preferrable low profile) |
		
#### Resistors		
| Reference | Value | Description            |
|:---:|:-------: |:----------------------------------------- |
| R1,R2,R3,R6 | 4K7 | Resistor, ¼ Watt | 
| R4 | 1K | Resistor, ¼ Watt | 
| R5 | 10K | Resistor, ¼ Watt | 
		
#### Miscellaneous		
| Reference | Value | Description            |
|:---:|:-------: |:----------------------------------------- |
|SW1	| -- | SPDT Switch, slide, right angle (reference OS102011MA1QN1) |
|CN1	| -- | Printed Circuit Board [Gerbers](https://github.com/Danjovic/Soda-IDE/tree/main/hardware/Gerber) |
|JP1	| -- | Pin Header, 1x3 pin, pitch 2.54mm, straight (Vertical) |
|JP2,JP3,JP4 | -- | Pin Header, 1x2 pin, pitch 2.54mm, straight (Vertical) |
		
		
#### 44 pin CF adapter option		
| J1	|	Pin Header, 2x22 pin, pitch 2.0mm, right angle (Horizontal) |
|:---:| :----------------------------------------- |
		
#### 40 pin CF adapter option		
|J2	|	Pin Header, 2x20 pin, pitch 2.54mm, right angle (Horizontal)
|:---:| :----------------------------------------- |
		
#### CF Socket Option		
|J3	|	CF Card Connector (reference 3M_N7E50-E516xx-30)
|:---:| :----------------------------------------- |


