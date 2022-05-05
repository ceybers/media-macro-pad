# media-macro-pad

## 📻 Project Description

A wireless macro pad for controlling media playback and volume control.

![Photo of the macro pad](images/20220505-IMG_1290.jpg)

[More images...](images/gallery.md)

## 🧰 Features

- 6× programmable keys via [MK32 firmware](https://github.com/Galzai/MK32)
- Volume dial
- Connects via BLE
- 500mAh battery
- Charges via USB-C

## ⚠️ Issues

> Current STL/FreeCAD models are not suitable for actual use!

- Heat set inserts on top shell poorly placed - head of screw collides with walls of shell
- Holes for heat set inserts were too small (Ø3.0mm in CAD)
- Holes for heat set did not have fillets to help guide placement
- Walls for heat set inserts too thin (1.5mm) - melted during placement
- Power switch slightly too tall for height of middle shell
- Insufficient clearance between contacts of power switch and rotary encoder base
- Incorrect spacing for standoffs for the MCU board
- Placement of MCU's battery connect (JST-PH) collides with heat set column
- Wall around opening for LED would have helped with alignment

## 🛒 Bill of Materials (BOM)

| Item | Size | Qty | 
| ---- | ---- | --- |
| [DFrobot FireBeetle ESP32-E](https://www.dfrobot.com/product-2231.html) | N/A | 1 |
| KCD11 Rocker Switch | N/A | 1 | 
| Battery LiPo 500mAh 3.7V | 38.5×29.5×5mm | 1 |
| EC11 Rotary Encoder | 15mm shaft, 4.5mm base | 1 |
| MX switches | N/A | 6 |
| LED, Red |5mm | 1 |
| Resistor | 220 Ohm | 1 |
| Heat Set Inserts | M2.5×6mm | 6 |
| Screws | M2.5×6mm | 6 |
| 3D printed shell | N/A | 4 pcs |


![Photo of the macro pad](images/Screenshot%202022-04-27%20193904.png)
## 🔗 References

- [MK32 firmware](https://github.com/Galzai/MK32)
- [Firebeetle ESP32-E (DFR0654) wiki](https://wiki.dfrobot.com/FireBeetle_Board_ESP32_E_SKU_DFR0654)
- [EspressIf API Reference](https://docs.espressif.com/projects/esp-idf/en/latest/esp32/api-reference/index.html)