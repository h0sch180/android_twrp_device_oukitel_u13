TWRP Device Tree for Oukitel U13 
===========
Unoffical Build for MT6753 TWRP 
------------------

the way to do:
```
- repo init -u git://github.com/minimal-manifest-twrp/platform_manifest_twrp_omni.git -b twrp-6.0

- repo sync

- git clone https://github.com/h0sch180/android_twrp_device_oukitel_u13 device/OUKITEL/U13

- . build/envsetup.sh

- lunch omni_U13-eng

- make -j# recoveryimage [# : no. of cpu core]
```

