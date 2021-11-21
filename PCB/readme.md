# Adalyn PCB
After the development of the handwired Adalyn case, it was clear this great combination needed a formalized pcb. This is that PCB. Designed by tominabox1, the pcb features an ATmega32u4a, USB-C, and ESD protection. The pcb is supported in QMK and VIAL. 

# BOM
The bill of materials is listed below, with LCSC parts where possible. Total unique part count: 14. Total parts: 37. 

| Ref                                                                                                        | Qnty | Value              | Part     | Footprint                                                          |
|------------------------------------------------------------------------------------------------------------|------|--------------------|----------|--------------------------------------------------------------------|
| C1, C2, C4, C101                                                                                           | 4    | 100nF              | C187860  | 0603                                                               |
| C5                                                                                                         | 1    | 10uF               | C97885   | 0603                                                               |
| C6                                                                                                         | 1    | 1uF                | C302042  | 0603                                                               |
| D101, D102, D103, D104, D105, D106, D107, D108, D109, D110, D111, D112, D113, D114, D115, D116, D117, D118 | 18   | BAV70              | C181110  | SOT-23                                                             |
| F101                                                                                                       | 1    | 700mA              | C182438  | 0603                                                               |
| L101                                                                                                       | 1    | 600R@100MHz        | C139183  | 0603                                                               |
| R2, R3                                                                                                     | 2    | 22                 | C96423   | 0603                                                               |
| R4, R5                                                                                                     | 2    | 10k                | C73809   | 0603                                                               |
| R101, R102                                                                                                 | 2    | 5.1k               | C415096  | 0603                                                               |
| SW1                                                                                                        | 1    | SW_Push            | C589220  | 4.9x4.9                                                            |
| U101                                                                                                       | 1    | ATmega32U4-A       | C44854   | TQFP-44_10x10mm_P0.8mm                                             |
| U102                                                                                                       | 1    | PRTR5V0U2X         | C2827688 | SOT-143                                                            |
| USB101                                                                                                     | 1    | HRO-TYPE-C-31-M-12 | C165948  | HRO-TYPE-C-31-M-12                                                 |
| Y1                                                                                                         | 1    | 16MHz              | C341521  | Crystal:Resonator_SMD_Murata_CSTxExxV-3Pin_3.0x1.1mm_HandSoldering |