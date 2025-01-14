Realme C3/Realme Narzo 10A Device Tree - RMX2020/RMX2027
================================================================

![Realme C3](https://user-images.githubusercontent.com/47187468/130330695-234069ce-9895-4535-860f-4c8ea57fbb80.png)

Basic   | Spec Sheet
-------:|:-------------------------
CPU     | Octa-core (2x2.0 GHz Cortex-A75 & 6x1.7 GHz Cortex-A55)
Chipset | MediaTek Helio G70 (12 nm)
GPU     | Mali-G52 2EEMC2
Memory  | 3/4 GB
Shipped Android Version | Android 10, realme UI 1.0 
Storage | 32/64 GB (eMMC type)
MicroSD | Up to 512 GB 
Battery | Li-Po 5000 mAh, non-removable
Dimensions | 164.4 x 75 x 9 mm (6.47 x 2.95 x 0.35 in)
Display | 720 x 1560 pixels, 6.50" IPS LCD, 20:9 ratio (~270 ppi density)
Rear Camera  | Dual : 13 MP; 2MP(depth); 2MP(Macro- only Narzo 10A and C3 Global)
Front Camera | Single: 5 MP
Release Month | 2020, February 14 | 2020, May 22 


Patches needed for building:

1. Needed to boot: https://github.com/PixelExperience/external_selinux/commit/9d6ebe89430ffe0aeeb156f572b2a810f9dc98cc

Repos needed for building:

1. https://github.com/Realme-G70-Series/android_packages_apps_RealmeParts
2. https://github.com/Realme-G70-Series/android_packages_apps_RealmeDirac
3. https://github.com/PixelExperience/device_mediatek_sepolicy_vndr
4. https://github.com/Realme-G70-Series/vendor_mediatek_ims
5. https://github.com/Realme-G70-Series/vendor_mediatek_interfaces

Copyright (C) 2021 Lineage OS
