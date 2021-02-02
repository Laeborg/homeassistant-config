# Laeborg's Home Assistant configuration

[Home Assistant OS (HassOS)](https://github.com/home-assistant/operating-system) as a virtual machine on a VMWare ESXi host. The VM is currently allocated 2 CPU cores, 2 GB of RAM and 32 GB disk space. Local DNS ensures same hostname both internal and external. Network is powered by Ubiquiti.

🛠️ **This setup is work-in-progress** 🛠️

Inspired by [frenck](https://github.com/frenck/home-assistant-config) and [matt8707](https://github.com/matt8707/hass-config) - check out their awesome configurations too.

## Adapters
- Zigbee: CC2652RB from Slaeh's iot stuff
- Bluetooth: Logilink BC8510

## Devices
**Zigbee**
- 10 SmartThings Multipurpose Sensor (IM6001-MPP01)
- 4 SmartThings Motion Detector (IM6001-MTP01)
- 2 Xiaomi MiJia light intensity sensor (GZCGQ01LM)
- 3 Xiaomi MiJia door & window contact sensor (MCCGQ01LM)
- 2 Xiaomi MiJia temperature & humidity sensor (WSDCGQ01LM)
- 2 Xiaomi Aqara wireless switch (WXKG11LM)
- 4 IKEA TRADFRI LED bulb E14 600 lumen (LED1733G7)
- 5 IKEA TRADFRI LED bulb E27 1000 lumen (LED1732G11)
- 1 IKEA FLOALT LED light panel (L1527)
- 2 IKEA TRADFRI wireless dimmer (ICTC-G-1)
- 1 IKEA TRADFRI driver for wireless control (ICPSHC24-10EU-IL-1)
- 1 LIDL Livarno Lux E27 bulb CCT (HG06492C)
- 2 LIDL Livarno Lux E14 candle RGB (HG06106B)
- 1 LIDL Silvercrest 3 gang switch (HG06338)
- 1 LIDL Silvercrest smart plug (HG06337)
- 1 LIDL Silvercrest smart motion sensor (HG06335)
- 3 LIDL Livarno Lux smart LED light strip (HG06104A)

**Bluetooth**
- Linak DPG Desk

**WiFi**
- Roborock S60
- 2 Wiz light bulbs
- 2 Ubiquiti UniFi® Protect G3 Bullet
- Samsung UE43TU7005
- Samsung UE55TU7005