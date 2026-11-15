---
title: "OpenMouse"
github: "https://github.com/AKIVC/OpenMouse"
description: "OpenMouse is an open source functional gaming mouse designed to be comfortable, responsive, and easy to modify. The main mouse is built around an NRF52840 SoC and a PAW3395DM optical sensor. A dedicated USB receiver dongle will be built around a second NRF52840 SoC allowing me to create my own 2.4Ghz wireless protocol. In addition to the electronics I will design both PCBs, a 3D printable case, and all the firmware for both the mouse and receiver. This project interests me because I believe it would give me a serious challenge but not one that I can't overcome, and also I think it will be very enjoyable/informative."
created_at: "2026-11-11"
total_time: "1h 42m"
---

# November 12, 2026: Project Start/Basic progress
<!-- fabricate:entry 2776 -->

YESS FINALY I GET TO STARTTTT!!!

For the first session I gathered some more info about the NRF52840 specifically power and made the decision to run in LDO only mode over the DC-DC buck mode. After this I got the power and ground nets started in the PCB design ready for connection to the future battery management system.

Timelapse: <https://lapse.hackclub.com/timelapse/cvluVFEDbB1E>

**Total time spent: 1h**

# November 14, 2026: Basic circuit redesign to match datasheet
<!-- fabricate:entry 3021 -->

Before starting work I took a look at the datasheet for the nRF52840 and found a schematic for the exact basic setup that I needed as a base. After finding this I restarted my progress and had a much better time with the design. Now the nRF52840 should be able to power on and is technically functional. I just need to add the sensor and the BMS... That will have to wait till next time, but breaking through this challenge has given me some motivation to keep going.

Timelapse: <https://lapse.hackclub.com/timelapse/fVRQVh-SORgb>

**Total time spent: 42m**
