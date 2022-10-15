# Commet Lake - H510 - RX470 - OpenCore Hackintosh

## Detail specs

| Component   | Model                    |
| ----------- | ------------------------ |
| CPU         | Intel Core i3-10100      |
| Motherboard | ASRock H510M-HVS R2.0    |
| GPU         | Sapphire RX470 4GB       |
| RAM         | 2x8GB DDR4 2666MHz       |
| SSD         | Samsung 860 EVO 250GB    |
| WiFi        | None                     |
| Audio       | Realtek ALC897           |
| Ethernet    | Realtek RTL8111          |
| Monitor     | Xiaomi Monitor 24 inches |
| OS          | macOS Monterey 12.6      |

## What's working

- [x] Mouse and keyboard
- [x] Resolution 1920x1080
- [x] Audio
- [x] Ethernet
- [x] USB 2.0 & 3.0
- [x] Shutdown & Restart
- [x] UI for OpenCore

## What's not working

- [ ] Intel UHD Graphics 630 (has problem with H510)
- [ ] WiFi & Bluetooth - I don't have any WiFi card
- [ ] HDMI Audio (Not tested)
- [ ] iMessage & Facetime
- [ ] Handoff (Not tested)
- [ ] Continuity (Not tested)
- [ ] AirDrop
- [ ] Sidecar (Not tested)
- [ ] Apple Watch Unlock (Not tested)
- [ ] Sleep & Wake (The fan is still running)

## BIOS Settings

- [x] Fast Boot
- [x] VT-d
- [x] DVMT Pre-Allocated(iGPU Memory): 64M/Auto
- [x] CFG Lock: Enabled (optional)
- [x] Secure Boot: Disabled
- [x] Intel SGX: Disabled
- [x] Intel Platform Trust: Disabled
- [x] Above 4G Decoding: Enabled
- [x] Hyper Threading: Enabled
- [x] Execute Disable Bit: Disabled
- [x] SATA Mode: AHCI
- [x] LAN PXE Boot Option ROM: Disabled
- [x] Storage Boot Option Control: UEFI
- [x] USB Configuration: XHCI Hand-off
- [x] Fast Boot: Disabled
- [x] Windows 10 Features: Other OS
- [x] Intel Virtualization Technology: Enabled

## OpenCore Settings

- [x] Add SMBIOS: iMac20,1
- [x] Add MLB, SystemSerialNumber, SystemUUID

## Note

- This shared EFI is for macOS Monterey 12.6, and it is release version of OpenCore 0.8.5. If you want to use it for other version of macOS, you need to change the config.plist file.

## Credits

- [Acidanthera](https://github.com/acidanthera)
- [Dortania](https://dortania.github.io/OpenCore-Install-Guide/)
- [RehabMan](https://github.com/RehabMan)

## Contact

- [Facebook](https://facebook.com/buiducnhat47)
- [Telegram](https://t.me/buiducnhat)
- [Reddit](https://reddit.com/user/gerpann)
- [GitHub](https://github.com/buiducnhat)

## Donate

If you like my work, you can buy me a coffee

[!["Buy Me A Coffee"](https://www.buymeacoffee.com/assets/img/custom_images/orange_img.png)](https://www.buymeacoffee.com/buiducnhat)
