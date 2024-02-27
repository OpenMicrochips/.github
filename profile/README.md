# OpenMicrochips

## Description
The open-source Microchips (ASICs) from the department of Computer Science (CS) at Hochschule RheinMain (HSRM) are at home in this GitHub orgranization. 

##  Content
The names of the repositories hint to the content:

### Prefixes

__TTXX__ Tinytapeout XX

__GF180-MPWX__ GlobalFoundry 180nm PDK in Shuttlerun MPW-X

__SKY130-MPWX__ Skywater 130nm PDK in Shuttlerun MPW-X

__IHP130-SHUTTLE__ IHP 130nm PDK in Shuttlerun SHUTTLE


### Postfixes

__bringup__ Files and docs for bringing a chip to life (installation in Lab)

__NAME__ Name of the chip. Contains the design files and/or the GDS

## Calendar
This is an overview of all the open-source microchips, in chronological order. Each row displays the information of a single microchip design. The columns are explained below the list. Some of the fields link to external sites. 

Work-in-progress:
Empty fields will get filled over time, the infos are not ready available by now. The whole thing is updated from time to time.

| TO    | Del   | I | PDK    | SR    | Ser  | Name                    | Code | GDS | BU  |
|:------|:------|:----|:-------|:------|:-----|:------------------------|:-------|:----|:-----|
|       |       |     | SKY130 | MPW-5 | ZtoA | ALU 74181               | [Git](https://github.com/ThorKn/alu74181) |     |      |
| 22/05 | 24/02 |     | SKY130 | MPW-8 | EF   | VGA clock 01            | [Git](https://github.com/ThorKn/vga_clock_1) | [Git](https://github.com/ThorKn/tiny_user_project_vgaclock_mpw8) |      |
| 22/12 | 23/06 | Y   | GF180  | MPW-0 | EF   | 8x8 Bit Mem Player      | [Wokwi](https://wokwi.com/projects/341620484740219475) | [Git](https://github.com/ThorKn/tiny_user_project_8x8_player) |      |
| 22/12 | 23/06 | Y   | GF180  | MPW-0 | EF   | ALU 74181               | [Git](https://github.com/ThorKn/alu74181) | [Git](https://github.com/ThorKn/tiny_user_project_74181_alu) |      |
| 22/12 | 24/01 | Y   | SKY130 | 2211Q | TT02 | 8x8 Bit Mem Player      | [Wokwi](https://wokwi.com/projects/341620484740219475) | [Git](https://github.com/ThorKn/tinytapeout02_pattern_player)    |     |
| 22/12 | 24/01 | Y   | SKY130 | 2211Q | TT02 | Shiftreg Chall. 40 Bit  | [Wokwi](https://wokwi.com/projects/341516949939814994) | [Git](https://github.com/ThorKn/tinytapeout02_shiftregister_challenge) |     |
| 23/04 | 24/03 |     | SKY130 | 2304C | TT03 | Skinny SBox 8 Bit       | [Wokwi](https://wokwi.com/projects/359372419264319489) | [Git](https://github.com/ThorKn/tt03_sbox_8bit_skinny) |      |
| 23/04 | 24/03 |     | SKY130 | 2304C | TT03 | 8x8 Bit Mem Player      | [Wokwi](https://wokwi.com/projects/341620484740219475) | [Git](https://github.com/ThorKn/tinytapeout02_pattern_player) |     |
| 23/04 | 24/03 |     | SKY130 | 2304C | TT03 | Shiftreg Chall. 40 Bit  | [Wokwi](https://wokwi.com/projects/341516949939814994) | [Git](https://github.com/ThorKn/tinytapeout02_shiftregister_challenge) |     |
| 23/06 |       |     | SKY130 |   ?   | TT03.5 | VGA clock 02            | [Git](https://github.com/ThorKn/vga_clock_1) | [Git](https://github.com/ThorKn/tt03p5-vgaclock-02) |      |
| 23/09 | 24/04 |     | SKY130 | 2309  | TT04 | Audio PWM Synth         | ? | [Git](https://github.com/ThorKn/tt04-audio-pwm-synth) |      |
| 23/12 | 24/06 |     | GF180  | MPW-1 | EF   | AudioChip               | [Git](https://github.com/ThorKn/icestick_spinalHDL_pwmAudio) | [Git](https://github.com/ThorKn/AudioChip) |      |

#### Calendar columns

__TO:__ Tapeout deadline dates. The commit of the design files for production.
 
__Del:__ Delivery date. The chip gets delivered to me.

__I:__ The chip is __In my hands__ (Yes/No).

__PDK:__ Process Design Kit (Open Source).

__SR:__ Shuttlerun name and number.

__Ser:__ Serviceprovider for the Shuttlerun. EF = Efabless, ZtoA = ZeroToAsic, TT = Tinytapeout.

__Name:__ Name of the chipdesign.

__Code:__ Link to the sourcecode of the chipdesign.

__GDS:__ Link to the repository of the Tapeout GDS.

__BU:__ Link to the Bring-Up and testing process, after receiving the microchips.