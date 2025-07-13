---
title: "MiniMesh"
author: "krunch"
description: "Tiny, low-power mesh node with gps, and an OLED display"
created_at: "2025-07-10"
---

# July 12 - Schematic (2 hours)

I made the schematic today, I wanted a low-power device so I went with the nRF52840, it only uses around 10mA on average so it's perfect since this device would spent alot of time on battery power.

For the RF trasnceiver, I chose the HT-RA62, it uses the SX1262 chip which is widely supported by the Meshtastic firmware.

For the OLED display, I chose one that uses SSD1306 drivers, these are plug and play with the Meshtastic firmware.

<img width="653" height="423" alt="image" src="https://github.com/user-attachments/assets/3cc9b4e9-e2a7-4535-90e5-5398c52d7ee5" />

Tomorrow, I will see if I can integrate a on-board GPS chip.

# July 13 - Layout and Wiring (1.5 hours)

Today I did the PCB layout, since I wanted this PCB to be as small as possible, I made it so that the OLED sits on top of the pro micro like this

<img width="604" height="498" alt="image" src="https://github.com/user-attachments/assets/d139ad14-65c5-4aa6-bd41-97a3cb7b5eb3" />

I also quickly made a model of the radio transceiver in OnShape since I couldn't find one.

| 3D Model | Real |
|----------|------|
| <img width="150" height="148" alt="image" src="https://github.com/user-attachments/assets/6c427d35-d60b-4817-8b20-8bb36175ca95" /> | <img width="169" height="148" alt="image" src="https://github.com/user-attachments/assets/ddcb8d92-8ebb-4777-a7a3-ff51c7ad8a30" /> |

And then I wired everything up, I managed to slip a few traces on the edge of the board

This took quite a while but I managed to make it look good

<img width="338" height="620" alt="image" src="https://github.com/user-attachments/assets/bef4bb34-f839-431c-a063-0dca262d8967" />
<img width="324" height="619" alt="image" src="https://github.com/user-attachments/assets/3c7fa5f7-8f5d-439f-a823-ff53db81eaf9" />

<img width="556" height="592" alt="image" src="https://github.com/user-attachments/assets/1b3ac05d-f5b4-4555-a22c-38d219efb6ab" />

I'm going model the case tomorrow!
