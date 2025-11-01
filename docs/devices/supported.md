# Supported devices

**Z2M device name** usually represents a collection of devices.  
Even if they work the same, rebranded versions have different internals and different pinouts (and therefore require custom builds).  

**Zigbee Manufacturer** is the most reliable unique device identifier. If the TZ3000 id of your device is not on this list, it requires porting. 

For devices that contain a **supported Tuya Zigbee module** (ZTU, ZT2S, ZT3L), porting is relatively simple.  
It consists of tracing (or guessing) the **board pinout**, adding an entry in the `device_db.yaml` file and running the build action. 

Also read:  
- [contribute/porting_to_new_device.md](/docs/contribute/porting_to_new_device.md)
- [recommended.md](./recommended.md)
- [not_recommended.md](./not_recommended.md)

| Z2M device name | Vendor name | Zigbee Manufacturer | Type | Status | Issue |
| --- | --- | --- | --- | --- | --- |
| [ZS-EUB_1gang](https://www.zigbee2mqtt.io/devices/ZS-EUB_1gang.html) | Moes 1-gang switches (button or touch)  | _TZ3000_hhiodade | router / end_device | Supported |   [link](https://github.com/romasku/tuya-zigbee-switch/issues/14)  | 
| [ZS-EUB_2gang](https://www.zigbee2mqtt.io/devices/ZS-EUB_2gang.html) | Moes 2-gang switches (buttons or touch)  | _TZ3000_18ejxno0 | router / end_device | Supported |   [link](https://github.com/romasku/tuya-zigbee-switch/issues/14)  | 
| [TS0013](https://www.zigbee2mqtt.io/devices/TS0013.html) | Moes 3-gang switches (buttons or touch)  | _TZ3000_qewo8dlz | router / end_device | Supported |   [link](https://github.com/romasku/tuya-zigbee-switch/issues/14)  | 

