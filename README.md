# Dell Latitude 7490 Hackintosh EFI 
# macOS 11.x BigSur with Intel Wireless via AirportItlwm

Currently using the same build, but never test all features yet.
Any new builds will be pushed to here too if possible.

## Tested macOS version:
macOS 11.3 / 11.3.1 / 11.4 Big Sur using OpenCore 0.6.8

## System configuration

Intel Core i7-8650U

24GB DDR4-2400MHz RAM (16GB+8GB)

Intel UHD 620 Graphics

Samsung SSD 970EVO 500GB

Intel Dual-Band Wireless-AC 8265 (standard config)

## Confirm working
1) Loudspeaker
2) 3.5mm headphone jack
3) Battery Management
4) Backlight Control (Fn+B & Fn+S)
5) Ethernet
6) Sleep and Wake 
7) Touchpad with Gestures
8) WiFi (5GHz) and Bluetooth Audio*
9) USB-C Power Delivery for Charging (Apple 61W)
10) Barrel Plug for Charging (Dell 90W)
11) FileVault
12) CPU SpeedStep
13) iGPU Acceleration
14) Native hotkey support with Fn keys
15) Dual-booting with Windows (Native dual-boot, not through BootCamp)

*Note: Could not connect to Logitech M590 Bluetooth Mouse, and WiFi/BT Chip might not be able to turn on sometimes, especially if you dual-boot with Windows and fast startup on Windows is enabled.

## Not working
1) Trackpad Keys (unreliable)
2) TrackPoint
3) SideCar
4) DHCP Support still broken for AppleItlwm (use Itlwm & HeliPort instead if you do not need to use WPA2-Enterprise / 802.11X)

## Unknown (not tested)
1) Intel TurboBoost (Need to do monitoring)
2) WiFi (2.4GHz)
3) Handoff and Airdrop (Likely not working due to AppleItlwm Limitations)
4) Display Port over USB-C
5) HDMI (video and audio)
6) USB-C Data Transfer
7) WWAN
8) SD Card Reader
9) ThunderBolt (Config does not support)
10) Touchscreen (Config does not support)


## Credit
1) Swung0x48/Dell-Latitude-7390-7490-Hackintosh-EFI: https://github.com/Swung0x48/Dell-Latitude-7390-7490-Hackintosh-EFI/tree/Catalina-OpenCore
2) niiknow/Hackintosh-Latitude-7390: https://github.com/niiknow/Hackintosh-Latitude-7390
3) dortania/OpenCore-Install-Guide: https://dortania.github.io/OpenCore-Install-Guide/
4) OpenIntelWireless/itlwm: https://github.com/OpenIntelWireless/itlwm/
5) xzhih/one-key-hidpi：https://github.com/xzhih/one-key-hidpi
