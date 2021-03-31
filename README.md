![hack](https://user-images.githubusercontent.com/30422190/113218486-f843cb00-9255-11eb-99eb-a6fd1872b04e.png)

## The Build

| Part         | Specs                                          |
| ------------ | ---------------------------------------------- |
| CPU          | Intel® Core™ i7-10700                          |
| iGPU         | Intel® UHD Graphics 630                        |
| dGPU         | Asus Radeon RX 5600 XT 6GB EVO OC              |
| RAM          | HyperX FURY DDR4 16GB @2666 (X2)               |
| Motherboard  | ASUS TUF Gaming B460M Plus BIOS Version 1401   |
| Audio        | Realtek S1200A codec _layout-id: 1_            |
| Ethernet     | Intel® I219-V LAN                              |
| SSD_01       | Samsung 850 Evo 250GB                          |
| SSD_02       | Crucial Bx500 240GB                            |
| HDD          | WD Blue 4TB                                    |
| Power Supply | Corsair CX600M                                 |
| Case         | Cooler Master HAF 912 Black Edition            |
| Monitor_01   | LG 29wk600 29" Ultra Wide LED FreeSync Monitor |
| Monitor_02   | LG E2060 20" Wide LED                          |
| Keyboard     | Fortrek G Pro K7 Plus                          |
| Mouse        | Logitech G300s                                 |

## Gather Kexts

- [AppleALC.kext](https://github.com/acidanthera/AppleALC/releases)
- [IntelMausiEthernet.kext](https://onedrive.live.com/?authkey=%21APjCyRpzoAKp4xs&id=FE4038DA929BFB23%21455134&cid=FE4038DA929BFB23)
- [Lilu.kext](https://github.com/acidanthera/Lilu/releases)
- [USBInjectAll.kext](https://bitbucket.org/RehabMan/os-x-usb-inject-all/downloads/)
- [VirtualSMC.kext](https://github.com/acidanthera/VirtualSMC/releases)
- [WhateverGreen.kext](https://github.com/acidanthera/WhateverGreen/releases)
- [RealtekRTL8111.kext](https://github.com/Mieze/RTL8111_driver_for_OS_XRealtekRTL8111.kext) (v2.3.0)
- [VoodooHDA.kext](https://github.com/chris1111/VoodooHDA-2.9.2-Clover-V15t)

1. Use Clover Configurator to mount the EFI partition of the USB drive
2. Copy the downloaded .kexts to `EFI/CLOVER/kexts/` on the USB drive EFI partition

## Configure Clover
