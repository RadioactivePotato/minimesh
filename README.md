# minimesh
A tiny, low-power Meshtastic compatible device with GPS, enviroment sensor and an OLED display powered by nRF52840

# About

I made this because I found that alot of pre-made Meshtastic nodes are too big and too power hungry, this node uses the nRF52840 chip instead of the ESP32-S3 since it's much more power efficient, while only sacrificing the Wi-Fi feature.

# Images

<details>
<summary>Schematic (click to expand)</summary>

| Schematic |
|-----------|
| ![Schematic](assets/schematic.png) |

</details>

| PCB | 3D Preview | Case |
|-----|------------|------|
| ![PCB](assets/pcb.png) | ![3D-Front](assets/3dfront.png) | ![Baseplate](assets/cad.png) |
| | ![3D-Back](assets/3dback.png) | |

# BOM

| Qty | Item                            | Notes                         | Cost (GBP) | URL |
|-----|---------------------------------|-------------------------------|------------|-----|
| 1   | HT-RA62 Transceiver Module      | Can be replaced with RA-01SH  | 6.59       | [AliExperss](https://www.aliexpress.com/item/1005005543917617.html)                         |
| 1   | nRF52840 ProMicro               | MCU (incl vat+shipping)       | 5.23       | [Elecrow](https://www.elecrow.com/pro-micro-nrf52840-development-board-compatible-with-nice-nano-v2-0.html) |
| 1   | 0.96" OLED Display              | Pinout needs to be GND,VCC... | 1.82       | [AliExpress](https://www.aliexpress.com/item/1005008738379315.html)                         |
| 2   | Switches                        |                               | 1.32       | [AliExpress](https://www.aliexpress.com/item/4001125532910.html)                            |
| 1   | GP-02-KIT GPS Module            |                               | 3.35       | [AliExpress](https://www.aliexpress.com/item/1005008346885630.html)                         |
| 1   | Slide Switch                    | For GPS module (5mm)          | 1.37       | [AliExpress](https://www.aliexpress.com/item/1005007162182882.html)                         |
| 1   | 868MHz antenna (SMA M)          |                               | 4.52       | [AliExpress](https://www.aliexpress.com/item/1005006712636707.html)                         |
| 1   | BME280 Module                   | Telementary data              | 0.76       | [AliExpress](https://www.aliexpress.com/item/1005008511564094.html)                         |
|-----|---------------------------------|-------------------------------|------------|-----|
| 5   | PCB                             | Min order qty - 5             | 1.11       | JLCPCB                                                                                      |
|-----|---------------------------------|-------------------------------|------------|-----|
|-----|---------------------------------|-------------------------------| 33.47GBP   |-----|
|-----|---------------------------------|-------------------------------| 44.91USD   |-----|

![A badge of a Cerberus and a raccoon laughing together, with the text "HIGHWAY" and "HACK CLUB" beside them.](https://hc-cdn.hel1.your-objectstorage.com/s/v3/0bbcca68ffa3845300bb76940f8ad91fd53d2d68_06-30-2025-1618.png)