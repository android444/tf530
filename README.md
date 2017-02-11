# tf530

##License

This project and all the files contained are released under the GNU GPLv2.

##The TerribleFire 530 board.

I have not verified this board so please assume it does not work. 

Dirty PCB links will follow very soon.


## The BOM 


| Qty | Value           | Device             | Package              | Parts                                                  | Description                   |  |  | 
|---------|----------------------|--------------------------------------------------------|-------------------------------|
| 1   |                 | MC68030RC          | MPGA128              | IC1                                                    | 68xxx PROCESSOR               |  |  | 
| 1   |                 | MC68881FN-SOC      | PLCC68-S             | IC2                                                    | 68xxx PROCESSOR               |  |  | 
| 1   | 10K             | RESISTOR1206       | 1206                 | R3                                                     | Resistors                     |  |  | 
| 13  | 10uF            | CAP_CERAMIC1206    | 1206                 | C1, C2, C3, C4, C5, C6, C7, C8, C9, C10, C11, C12, C13 | Ceramic Capacitors            |  |  | 
| 2   | 47K             | RESISTOR1206       | 1206                 | R1, R2                                                 | Resistors                     |  |  | 
| 2   | 74LVC1G17DBV    | 74LVC1G17DBV       | SOT23-5              | IC4, IC5                                               | Single Schmitt-Trigger Buffer |  |  | 
| 1   | A500            | JUMPER-2PTH        | 1X02                 | A500                                                   | Jumper                        |  |  | 
| 4   | AS7C4096A-12TCN | AS7C4096A-12TCN    | TSOP44-II            | U$1, U$2, U$3, U$4                                     |                               |  |  | 
| 1   | AUXPINS         | JUMPER-2PTH        | 1X02                 | AUXPINS                                                | Jumper                        |  |  | 
| 1   | BYPASS          | JUMPER-2PTH        | 1X02                 | BYPASS                                                 | Jumper                        |  |  | 
| 3   | CAY16-103J4LF   | CAY16-103J4LF      | RESCAXE80P320X160-8N | RN1, RN2, RN3                                          | Res Thick Film Array 10K Ohm  |  |  | 
| 1   | CDIS            | JUMPER-2PTH        | 1X02                 | JP5                                                    | Jumper                        |  |  | 
| 1   | CLOCKSEL        | JUMPER-3PTH        | 1X03                 | JP1                                                    |                               |  |  | 
| 1   | EXT5V           | JUMPER-2PTH        | 1X02                 | JP7                                                    | Jumper                        |  |  | 
| 1   | IDE CONNECTOR   | PINHD-2X20         | 2X20                 | IDE                                                    | PIN HEADER                    |  |  | 
| 1   | JTAG            | HEADER-1X6ROUND    | 1X06_ROUND           | JTAG                                                   | PIN HEADER                    |  |  | 
| 1   | LM1117          | V_REG_LM1117SOT223 | SOT223               | U1                                                     | Voltage Regulator LM1117      |  |  | 
| 1   | MC68000         | MC68000P           | DIL64                | X1                                                     | 68xxx PROCESSOR               |  |  | 
| 1   | MMUDIS          | JUMPER-2PTH        | 1X02                 | JP3                                                    | Jumper                        |  |  | 
| 1   | SPI PORT        | PINHD-2X6          | 2X06                 | SPIPORT                                                | PIN HEADER                    |  |  | 
| 1   | X20MHZ          | OSCILLATOR         | OSC_7X5MM            | OSC1                                                   | Oscillators                   |  |  | 
| 2   | XC9572XL-VQ64   | XC9572XL-VQ64      | VQ64                 | XC9572XL(BUS), XC9572XL(RAM)                           |                               |  |  | 
