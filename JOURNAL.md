---
title: "OpenMouse"
github: "https://github.com/AKIVC/OpenMouse"
description: "OpenMouse is an open source functional gaming mouse designed to be comfortable, responsive, and easy to modify. The main mouse is built around an NRF52840 SoC and a PAW3395DM optical sensor. A dedicated USB receiver dongle will be built around a second NRF52840 SoC allowing me to create my own 2.4Ghz wireless protocol. In addition to the electronics I will design both PCBs, a 3D printable case, and all the firmware for both the mouse and receiver. This project interests me because I believe it would give me a serious challenge but not one that I can't overcome, and also I think it will be very enjoyable/informative."
created_at: "2026-11-11"
total_time: "6h 48m"
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

# November 21, 2026: Added mouse sensor, BMS, and rotary encoder
<!-- fabricate:entry 3670 -->

During this session I finally added the mouse sensor YAY, the schematic is starting to look like a functional design. I also added the Lithium Ion Battery Management System to protect/charge the battery I will be putting in here along with the rotary encoder for the scroll wheel.

Timelapse: <https://lapse.hackclub.com/timelapse/oycs3rXanCYY>

**Total time spent: 1h 12m**

# November 22, 2026: Added mouse sensor, BMS, and rotary encoder
<!-- fabricate:entry 3724 -->

During this session I finally added the mouse sensor YAY, the schematic is starting to look like a functional design. I also added the Lithium Ion Battery Management System to protect/charge the battery I will be putting in here along with the rotary encoder for the scroll wheel.

Timelapse: <https://lapse.hackclub.com/timelapse/oycs3rXanCYY>

**Total time spent: 1h 12m**

# November 22, 2026 (entry 2): Finished the Schematic
<!-- fabricate:entry 3725 -->

During this session I finished the schematic by adding the left/right buttons along with the middle button and two auxiliary buttons. I also started the PCB design and I got all the components into a rough place where I think I want them.

Timelapse: <https://lapse.hackclub.com/timelapse/IenzZnoxjK1z>

**Total time spent: 1h**

# November 27, 2026: Routed Antenna and Crystals
<!-- fabricate:entry 4065 -->

During this session I began the routing of the main MCU after finishing my first draft of the component layout. I got the antenna trace down and also added the keep out zones to isolate the antenna line. After this I routed both the high speed crystal oscillator and the slower one. I also added the silkscreen markings for the flashing header.

Timelapse: <https://lapse.hackclub.com/timelapse/yRqlMV4U_MYT>
Timelapse: <https://lapse.hackclub.com/timelapse/-JKXgqcgVCvn>

**Total time spent: 1h 42m**
