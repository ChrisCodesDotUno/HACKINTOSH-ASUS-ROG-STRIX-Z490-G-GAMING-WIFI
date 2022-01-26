# Monterey 12.1 on Intel i7 11700KF & ASUS ROG STRIX Z490-G GAMING WIFI

## Configuration
### Hardware
| Device       | Model                                 |
| -----------  | ------------------------------------- |
| CPU          | Intel Core i7-11700KF                 |
| Motherboard  | ASUS ROG STRIX Z490-G GAMING WIFI     |
| RAM          | Kingston HyperX KHX2133C14/8G x3      |
| GPU          | AMD Radeon HD 7770                    |
| Audio codec  | SupremeFX S1220A                      |
| Ethernet card| Intel® I225-V 2.5Gb Ethernet          |
| Wifi         | Intel® Wi-Fi 6 AX201                  |
| BIOS revision| 2403                                  |

## IMPORTANT
YOU MUST modify SN/UUID/MLB/ROM values in config.plist file. Run GenSMBIOS.bat on Windows or GenSMBIOS.command on mac from the GenSMBIOS-master folder.

### Software
- Bootloader: OpenCore 0.7.7
- OS: macOS Monterey 12.1

OpenCore setup was made according to https://dortania.github.io/OpenCore-Install-Guide/

### BIOS settings
**Note:** some settings are different from OpenCore guide.

#### Disable
- Fast Boot
- Serial/COM port
- Secure Boot
- VT-d (can be enabled if you set DisableIoMapper to YES)
- CSM
- CFG lock is already unlocked on this motherboard

#### Enable
- VT-x
- Above 4G decoding
- Hyper-Threading
- EHCI/XHCI Hand-off
- Set OS type to Other OS 
- SATA Mode: AHCI

### Working
- [x] Audio
- [x] Intel® I225-V 2.5Gb Ethernet 
- [x] Intel® Wi-Fi 6 AX201 
- [x] Shutdown/restart
- [x] Sleep/wake
- [x] USB
- [x] Power management
- [x] Bluetooth
- [x] HDMI & DP-port on external GPU
- [x] iCloud, App Store
- [x] Handoff / Continuity, Unlock with Apple Watch, AirDrop
- [x] FaceTime, Messages
- [x] Quick Look, Preview

### Issues

- DVI port on external GPU doesn't work

### Screenshot
![Screenshot](https://i.imgur.com/ivjtdBe.png "Screenshot")

![Screenshot](https://i.imgur.com/ku5GbdF.png "Screenshot")
