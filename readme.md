This is my Christmas Wreath!

The idea is that when you connect it to USB, the circuit board with light up its 10 LEDS. If you click one of the pressure pads on top of the baubles, it will change the LED colours (since these are RGB LEDs) or it will play music through the buzzer, based on which one you press.

Note: The Gerber has multicolour silkscreen files, so they are only order-able through JLCPCB.

<img width="983" height="1009" alt="image" src="https://github.com/user-attachments/assets/4afb0767-5b9e-4e50-b786-d1c1d2c26ab7" />


#### Here is my [BOM](https://github.com/SahasTechnologies/Christmas-Wreath/blob/main/bom.csv):
| No. | Quantity | Comment | Designator | Footprint | Value | Manufacturer Part | Manufacturer | Supplier Part | Supplier |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| 1   | 1   | 2.7kHz | BUZZER1 | BUZ-SMD_L9.6-W9.6-LS10.0-R | 2.7kHz | MLT-9650 | 华能  | C96127 | LCSC |
| 2   | 11  | 100nF | C1,C2,C3,C4,C5,C6,C7,C8,C9,C10,C11 | C0805 | 100nF | CC0805KRX7R9BB104 | YAGEO(国巨) | C49678 | LCSC |
| 3   | 10  | WS2812B-2020 | LED41,LED42,LED43,LED44,LED45,LED46,LED47,LED48,LED49,LED50 | LED-SMD\_4P-L2.0-W2.0-TL\_WS2812B-2020 |     | WS2812B-2020 | worldsemi | C965555 | LCSC |
| 4   | 1   | S8050 | Q1  | SOT-23-3_L3.0-W1.7-P0.95-LS2.9-BR |     | S8050 | MDD(辰达半导体) | C364312 | LCSC |
| 5   | 1   | 1kΩ | R1  | R0603 | 1kΩ | 0603WAJ0102T5E | UNI-ROYAL(厚声) | C25585 | LCSC |
| 6   | 1   | 330Ω | R12 | R0603 | 330Ω | RC0603FR-07330RL | YAGEO(国巨) | C105881 | LCSC |
| 7   | 2   | 22Ω | R13,R14 | R0603 | 22Ω | RC0603FR-0722RL | YAGEO(国巨) | C107701 | LCSC |
| 8   | 6   | 10kΩ | R15,R16,R17,R18,R19,R20 | R0805 | 10kΩ | 0805W8F1002T5E | UNI-ROYAL(厚声) | C17414 | LCSC |
| 9   | 5   | TTP223-BA6-TD | U1,U8,U9,U11,U13 | SOT-23-6_L2.9-W1.6-P0.95-LS2.9-BL |     | TTP223-BA6-TD | TDSEMIC(拓电半导体) | C42422127 | LCSC |
| 10  | 1   | RP2040 | U12 | LQFN-56_L7.0-W7.0-P0.4-EP |     | RP2040 | Raspberry Pi(树莓派) | C2040 | LCSC |
| 11  | 1   | 920-E52A2021S10100 | USB1 | MICRO-USB-SMD\_5P-P0.65-H-F\_C10418 |     | 920-E52A2021S10100 | 精拓金 | C10418 | LCSC |

