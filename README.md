# Redmi 9

Codename : Lancelot
Unified Codename : Lava
Released : June, 2020
Chipset : Mediatek MT6769V/CU Helio G80 (12 nm)
CPU Arch : arm64
CPU : Octa-core (2x2.0 GHz Cortex-A75 & 6x1.8 GHz Cortex-A55)
GPU : Mali-G52 MC2

Official Kernel Source : [GitHub](https://github.com/MiCode/Xiaomi_Kernel_OpenSource/tree/lancelot-q-oss)
Unified Kernel Source : [GitHub](https://github.com/Redmi-MT6768/android_kernel_xiaomi_mt6768)
TWRP Tree : [GitHub](https://github.com/rama982/android_device_xiaomi_lancelot-twrp)
Device Tree : [GitHub](https://github.com/Redmi-MT6768/android_device_xiaomi_lava)
Vendor Tree : [GitHub](https://github.com/Redmi-MT6768/android_vendor_xiaomi_lava)


# Notes

## Community

- XDA : [Redmi 9 / Poco M2](https://forum.xda-developers.com/c/redmi-9-poco-m2.11167/)
- Telegram :
  - [Redmi Note 9 / Redmi 9 Community](https://t.me/HelioG85_Unified)
  - [Xiaomi G80/G85 Unified Photography](https://t.me/HelioG85_Photography)
  - [MT6768 OC Kernel Update](https://t.me/ocmt6768c)
  - [Redmi 9 Lancelot/Lava | Indonesia](https://t.me/redmi_9)
- 4PDA : [Xiaomi Redmi 9](https://4pda.to/forum/index.php?showtopic=985518)

## Drivers
- Windows
  - [Mediatek Drivers](https://gsmusbdriver.com/install-mediatek-driver-auto-installer)
  - [ADB & Fastboot Drivers](https://github.com/fawazahmed0/Latest-adb-fastboot-installer-for-windows) 

## Debloater 
[Universal Android Debloater](https://github.com/0x192/universal-android-debloater) : Comes with descriptive instructions to help you debloat without any issues. Don't forget to install ADB drivers on your system.

[NikGapps Debloater Config](/sdcard/NikGapps/debloater.config) : This config is meant to be used exclusively with NikGapps Debloater Addon. Put the config file inside `/sdcard/NikGapps/` folder and flash the addon file in recovery.

## Unlock Bootloader
Official Method : This method is same for latest Xioami devices. Follow any of the guide available online. e.g. [Fossbyte](https://fossbytes.com/how-to-unlock-bootloader-on-xiaomi-devices-using-mi-unlock-tool/)
Instant Unlock : Instantly unlock bootloader using [mtkclient](https://github.com/bkerler/mtkclient) tool. TODO : A detail guide on how to use the tool.

## build.prop 
I tweaked `[build.prop](/system/build.prop)` per my needs, it's in messy condition and it might contain unnecessary entries. USE AT YOUR OWN RISK!
