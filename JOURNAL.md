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
