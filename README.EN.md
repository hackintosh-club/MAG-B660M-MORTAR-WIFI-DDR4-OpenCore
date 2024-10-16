# [MSI-MAG-B660M-MORTAR-WIFI-DDR4](https://www.msi.com/Motherboard/MAG-B660M-MORTAR-WIFI-DDR4) Hackintosh OpenCore EFI

![image](ScreenShot/Motherboard.png)

### [简体中文](https://github.com/hackintosh-efi/MAG-B660M-MORTAR-WIFI-DDR4-OpenCore)

[OpenCore 1.0.2](https://github.com/acidanthera/OpenCorePkg)

### OS Version Tested

- macOS Sequoia    15.x  **(Intel WiFi Need [OCLP](https://github.com/hackintosh-club/intel-nuc10/releases/tag/oclp) Patch)**   **(Broadcom WiFi Need [OCLP](https://github.com/dortania/OpenCore-Legacy-Patcher/releases/tag/2.0.2) Patch)** 
- macOS Sonoma    14.x  **(Broadcom WiFi Need [OCLP](https://github.com/dortania/OpenCore-Legacy-Patcher/releases/tag/2.0.2) Patch)** 
- macOS Ventura     13.x
- macOS Monterey  12.x

### Hardware

- Motherboard: MSI-MAG-B660M-MORTAR-WIFI-DDR4
- Bios Version: 7D42v1C（2023-06-04)
- CPU: Intel i5-13400
- RAM: KingBank 2x16GB DDR4 3600MHz
- SSD: ZHITAI Ti7100Plus 1TB Windows
- SSD: WD_BLACK SN770 1TB MacOS
- iGPU: Intel UHD730 (Only work in Windows)
- GPU: DATALAND Radeon RX 5600 XT 6GB X-Serial War
- Audio: Realtek ALC256
- Ethernet: Realtek 8125
- Wireless: Intel Wi-Fi 6E AX211
- Display:SANC G7c 2k 27inch 165Hz
- PSU: COOLERMASTER GX650W 80Plus Gold
- CASE:Jonsbo D31

### Bios Setup

| Name        | Option   |
|-------------|----------|
| Secure Boot | Disabled |
| CFG Lock    | Disabled |
| Fast Boot   | Disabled |

### Notes

- Use [OCAuxiliaryTools](https://github.com/ic005k/OCAuxiliaryTools) build your SMBIOS
- If you want to use a CPU without  Efficient-Core, you must uncheck the option in the config.plist file Kernel--ProvideCurrentCpuinfo
- Intel WiFi driver [AirportItlwm.kext](https://github.com/OpenIntelWireless/itlwm/releases) in this EFI is only applicable to MacOS 13 Ventura. Please download and replace this driver yourself when installing other MacOS versions
- Intel WiFi Not Supported  Airdrop

### ScreenShot

- Geekbench5 Score i5-13400

![image](ScreenShot/Geekbench5.png)

- Geekbench5 Score Metal DATALAND Radeon RX 5600 XT 6GB X-Serial War

![image](ScreenShot/metal.png)

- Geekbench5 Score OpenCL DATALAND Radeon RX 5600 XT 6GB X-Serial War

![image](ScreenShot/opencl.png)

### Contact Us

- QQ Group: 23304408

![image](ScreenShot/QRCode.png)
