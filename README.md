# Gameboy Printer Emulator - ESP32 PCB

<a href="https://www.buymeacoffee.com/zenaro147" target="_blank"><img src="https://cdn.buymeacoffee.com/buttons/v2/default-yellow.png" alt="Buy Me A Coffee" style="height: 60px !important;width: 217px !important;" ></a>

A simple PCB design using EasyEDA to work with this projects by me:
* [NeoGB Printer](https://github.com/zenaro147/NeoGB-Printer)
* [WiFi GBP Emulator - ESP32 Version](https://github.com/zenaro147/wifi-gbp-emulator/tree/feature/v3-esp32)

[![Order from OSH Park](https://oshpark.com/packs/media/images/badge-5f4e3bf4bf68f72ff88bd92e0089e9cf.png)](https://oshpark.com/shared_projects/Y6LBKwvG)

## BOM list 
| Component | Where to buy |
| --- | --- |
| ESP32 Dev Board (38 pins) | [AliExpress](https://a.aliexpress.com/_mKXR5OW) |
| OLED Display 128x32 (0.91 inch) (optional) | [AliExpress](https://a.aliexpress.com/_mOHbftG) |
| SD Card/MicroSD Card Module (Choose only one! I recommend the Standard SD module) | [AliExpress - SD Card](https://a.aliexpress.com/_mMWz2km) / [AliExpress - MicroSD](https://a.aliexpress.com/_m0SS4P4) |
| 4 channel Logical Level Shifter (highly recommended) | [AliExpress](https://a.aliexpress.com/_m07pFpU) |
| Female Pin Header with 40 pins (you need at least 38 pins, or 2 with 20pins) | [AliExpress](https://www.aliexpress.com/item/4000096276148.html) |
| PushButton 4.5x4.5mm (any height) - ONLY REV. 1  | [AliExpress](https://www.aliexpress.com/item/1005001629344310.html) |
| PushButton 6x6mm (any height) - ONLY REV. 2 (still W.I.P.) | [AliExpress](https://www.aliexpress.com/item/1005003251295065.html) |
| 5k or 10k resistor | [AliExpress](https://www.aliexpress.com/item/4001082088353.html) |
| MicroUSB Female (optional, but mandatory if you want the charging module)| [AliExpress](https://www.aliexpress.com/item/4000385426649.html) |
| Charging Module with StepUp (5V) - DD05CVSA (optional) | [AliExpress](https://www.aliexpress.com/item/33034500618.html) |
| Micro Switch - SS-12D00G3 (optional, but mandatory if you want the charging module) | [AliExpress](https://www.aliexpress.com/item/1005003938856402.html) |
| 1500mah Li-Po Battery (optional, but mandatory if you want the charging module) | [AliExpress](https://www.aliexpress.com/item/1005003235425542.html) |
| AGB Link Port Connector (optional) | [AliExpress](https://www.aliexpress.com/item/32858521427.html) |
| RGB LED 5mm (optional) | [AliExpress](https://www.aliexpress.com/item/1005002535018824.html) |
| 220R resistor (if you want the LED) | [AliExpress](https://www.aliexpress.com/item/4001082088353.html) |

## Inspirations/References
* [Game Boy -related custom hardware by gekkio](https://github.com/Gekkio/gb-hardware)
* [Game Boy WiFi Printer - D1 Mini Shield](https://github.com/cristofercruz/gbp-esp-shield-pcb)
* [Gameboy Link Cable Breakout PCB](https://github.com/Palmr/gb-link-cable)

## External References
* [ESP32-DEVKITC-32D](https://www.snapeda.com/parts/ESP32-DEVKITC-32D/Espressif%20Systems/view-part/)
* [ESP32 Pinout](https://4.bp.blogspot.com/-nGLtB2nUrDg/Wp6DQbzcJMI/AAAAAAAABq0/A6Z46p0SQSEdERWocWL94oUmeATMQre4wCLcBGAs/s1600/3.png)
* [ESP32 dev kit power options](https://techexplorations.com/guides/esp32/begin/power/)
* [Power Supply for ESP32 with Battery Charger & Boost Converter](https://how2electronics.com/power-supply-for-esp32-with-boost-converter-battery-charger/#37V_to_5V_Step-Up_Boost_Converter_Module)
* [ESP32 – Getting Battery charging level](https://www.pangodream.es/esp32-getting-battery-charging-level)
