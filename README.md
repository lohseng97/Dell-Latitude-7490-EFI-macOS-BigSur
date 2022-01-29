# Dell Latitude 7490 Hackintosh EFI
# macOS 11.x BigSur with Intel Wireless via AirportItlwm

As of Jan 2022: Using the macOS 11.6, but will be updating to macOS 12.2 soon.

## Tested macOS version:
macOS 11.3 - 11.6 Big Sur using OpenCore 0.6.8

## System configuration
- Intel Core i7-8650U
- 24GB DDR4-2400MHz RAM (16GB+8GB)
- Intel UHD 620 Graphics
- Samsung SSD 970 EVO 500GB
- Intel Dual-Band Wireless-AC 8265

## Confirm working
1) Loudspeaker
2) 3.5mm headphone jack^
4) Battery Management
5) Backlight Control (Fn+B & Fn+S)
6) Ethernet
7) Touchpad with Gestures
8) WiFi (2.4/5GHz) via AppleItlwm) _(Update: Updated kexts to v2.1.0)_
9) Bluetooth Audio*
10) USB-C Power Delivery for Charging (Apple 61W, Ugreen 65W)
11) Barrel Plug for Charging (Dell 90W)
12) FileVault
13) CPU SpeedStep
14) iGPU Acceleration
15) Native hotkey support with Fn keys
16) Dual-booting with Windows (Native dual-boot, not through BootCamp / Parallels)
17) HDMI output
18) SideCar using USB-A to lightning _(tested on iPad 7th/9th generation, WiFi+Cellular)_

^_3.5mm headphone jack might not work properly after system wakes from sleep, reboot will resolve the issue._

*_Could not connect to Logitech M590 Bluetooth Mouse, and WiFi/BT Chip might not be able to turn on sometimes, especially if you dual-boot with Windows and fast startup on Windows is enabled. _

## Not working
1) TrackPoint

## Unknown (not tested)
1) Intel TurboBoost (Unable to monitor)
2) Handoff and Airdrop (Likely not working due to AppleItlwm Limitations)
3) Display Port over USB-C
4) USB-C Data Transfer
5) WWAN
6) SD Card Reader
7) ThunderBolt and Touchscreen (SKU did not include)
8) SideCar over WiFi

## Credits
1) Swung0x48/Dell-Latitude-7390-7490-Hackintosh-EFI: https://github.com/Swung0x48/Dell-Latitude-7390-7490-Hackintosh-EFI/tree/Catalina-OpenCore
2) niiknow/Hackintosh-Latitude-7390: https://github.com/niiknow/Hackintosh-Latitude-7390
3) dortania/OpenCore-Install-Guide: https://dortania.github.io/OpenCore-Install-Guide/
4) OpenIntelWireless/itlwm: https://github.com/OpenIntelWireless/itlwm/
5) xzhih/one-key-hidpi：https://github.com/xzhih/one-key-hidpi
