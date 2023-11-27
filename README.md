# Dell Inc. Latitude 7480 Hackintosh

This was an comissioning for a dell laptop, I just got bored and wanted to share it with you, hope it helps.

Spoofed as a MacBookPro14,1, Current Running OS: macOS Monterey 12.0.1

## Hardware

- DualCore Intel Core i5-7200U, 2718 MHz
- Intel HD Graphics 620
- Intel Kaby Lake HDMI
- Audio Realtec Realtek ALC256
- Ethernet Intel I219-LM
- Intel Dual Band Wireless-AC 8265 WiFi Adapter 

### What's working
- [x] Intel HD Graphics 620
- [x] Audio Realtec Realtek ALC256
- [x] Ethernet Intel I219-LM
- [x] Bluetooth
- [x] USB Ports
- [x] Battery
- [x] Trackpad
- [x] Keyboard
- [x] Brightness
- [x] Sleep
- [x] iMessage Services

### What's not working
- AirDrop

## Credits

- [Acidanthera](https://github.com/acidanthera) for OpenCore and all the kexts
- [Dortania](https://dortania.github.io/OpenCore-Install-Guide/) for the OpenCore guide
- [RehabMan](https://github.com/RehabMan) for the ACPI patching guides
- [daliansky](https://github.com/daliansky) for the ACPI patching guides
- [Apple](https://www.apple.com) for macOS
- [Dell](https://www.dell.com) for the laptop
- [Me](https://github.com/Noe-ali) for the config.plist

## Installation

1. Download the latest release of OpenCore,  ProperTree and GenSMBIOS
2. Follow the [Dortania's guide](https://dortania.github.io/OpenCore-Install-Guide/installer-guide/) to create the USB installer
3. Mount the EFI partition of the USB installer and copy the EFI folder from this repo to the EFI partition
4. Boot from the USB installer and install macOS
5. Mount the EFI partition of the installed macOS and copy the EFI folder from the USB installer to the EFI partition of the installed macOS
6. Follow the [Dortania's guide](https://dortania.github.io/OpenCore-Post-Install/universal/iservices.html#generate-a-new-serial) to generate a new serial number for iMessage services
7. Enjoy!


