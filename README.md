# The-Devboard
Later

---

# Overview:

A custom DevBoard inspired from the RP2040 devboard. Made with the same specs but in a creative way and beautiful design theme following the guide from Stasis HackClub event.

I simply choosed to make this project because I see that I can learn a lot from it since I'm dealing with small components on a tiny surafce and It will better help me understanding the working process of a DevBoard.

---

# 3D Overview :
## Front View
<img width="1318" height="801" alt="image" src="https://github.com/user-attachments/assets/da449787-6d51-4f88-99b3-d9adb1a09892" />

## Rear View
<img width="1556" height="825" alt="image" src="https://github.com/user-attachments/assets/91b2e55a-50f3-4320-bf81-a721be5f174b" />

## Schematics
<img width="1225" height="864" alt="image" src="https://github.com/user-attachments/assets/a419a9f6-8be1-4125-9c01-7a3dd897884d" />

---

# BOM :

| Id | Designator                          | Footprint                                         | Quantity | Comment                     | Datasheet                                                                                                                                                                                                        |
| -- | ----------------------------------- | ------------------------------------------------- | -------- | --------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| 1  | C1,C10                              | Capacitor_SMD:C_0402_1005Metric                   | 2        | 1uF                         | ~                                                                                                                                                                                                                |
| 2  | C2,C3,C4,C5,C6,C7,C8,C9,C11,C12,C17 | Capacitor_SMD:C_0402_1005Metric                   | 11       | 0.1uF                       | ~                                                                                                                                                                                                                |
| 3  | C13,C14                             | Capacitor_SMD:C_0603_1608Metric                   | 2        | 10uF                        | ~                                                                                                                                                                                                                |
| 4  | C15,C16                             | Capacitor_SMD:C_0402_1005Metric                   | 2        | 33pF                        | ~                                                                                                                                                                                                                |
| 5  | J1                                  | Connector_USB:USB_C_Receptacle_HRO_TYPE-C-31-M-12 | 1        | USB_C_Receptacle_USB2.0_14P | [https://www.usb.org/sites/default/files/documents/usb_type-c.zip](https://www.usb.org/sites/default/files/documents/usb_type-c.zip)                                                                             |
| 6  | L1                                  | Inductor_SMD:L_0603_1608Metric                    | 1        | 10uH                        | ~                                                                                                                                                                                                                |
| 7  | R1                                  | Resistor_SMD:R_0402_1005Metric                    | 1        | 5.1k                        | ~                                                                                                                                                                                                                |
| 8  | R2                                  | Resistor_SMD:R_0402_1005Metric                    | 1        | 10k                         | ~                                                                                                                                                                                                                |
| 9  | R3                                  | Resistor_SMD:R_0402_1005Metric                    | 1        | 1k                          | ~                                                                                                                                                                                                                |
| 10 | SW1                                 | Button_Switch_SMD:SW_SPST_TL3342                  | 1        | RESET                       | ~                                                                                                                                                                                                                |
| 11 | U1                                  | Package_QFN:QFN-48-1EP_6x6mm_P0.4mm_EP4.4x4.4mm   | 1        | ESP32-S3-WROOM-1            | [https://www.espressif.com/sites/default/files/documentation/esp32-s3-wroom-1_wroom-1u_datasheet_en.pdf](https://www.espressif.com/sites/default/files/documentation/esp32-s3-wroom-1_wroom-1u_datasheet_en.pdf) |
| 12 | U2                                  | Package_TO_SOT_SMD:SOT-23-5                       | 1        | AMS1117-3.3                 | ~                                                                                                                                                                                                                |
| 13 | Y1                                  | Crystal:Crystal_SMD_3225-4Pin_3.2x2.5mm           | 1        | 40MHz                       | ~                                                                                                                                                                                                                |
| 14 | D1                                  | LED_SMD:LED_0603_1608Metric                       | 1        | Power LED                   | ~                                                                                                                                                                                                                |
| 15 | TP1,TP2                             | TestPoint:TestPoint_Pad_D1.0mm                    | 2        | GPIO Test Points            | ~                                                                                                                                                                                                                |
| 16 | H1,H2,H3,H4                         | MountingHole:MountingHole_2.2mm_M2                | 4        | Mounting Holes              | ~                                                                                                                                                                                                                |
