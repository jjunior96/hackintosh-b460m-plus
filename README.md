![monterey](https://user-images.githubusercontent.com/30422190/139580561-1e5f9d93-c896-498e-baae-ccdefc985de4.png)

## The Build

| Part         | Specs                                          |
| ------------ | ---------------------------------------------- |
| CPU          | Intel® Core™ i7-10700                          |
| iGPU         | Intel® UHD Graphics 630                        |
| Water Cooler | PCYes Sangue Frio V2 (240mm)                   |
| dGPU         | Asus Radeon RX 5600 XT 6GB EVO OC              |
| RAM          | HyperX FURY DDR4 16GB @2666 (X2)               |
| Motherboard  | ASUS TUF Gaming B460M Plus BIOS Version 1401   |
| Audio        | Realtek S1200A codec _layout-id: 1_            |
| Ethernet     | Intel® I219-V LAN                              |
| SSD_01       | XPG S41 TUF Gaming 512GB (NVME M.2)            |
| SSD_02       | XPG S11 PRO 512GB (NVME M.2)                   |
| SSD_03       | Samsung 850 Evo 250GB                          |
| SSD_04       | Crucial Bx500 240GB                            |
| HDD_01       | WD Blue 4TB (7200RPM)                          |
| HDD_02       | Seagate 1TB (7200RPM)                          |
| Power Supply | Corsair CX600M                                 |
| Case         | Cooler Master MASTERBOX TD500 MESH ARGB        |
| Monitor_01   | LG 29wk600 29" Ultra Wide LED FreeSync Monitor |
| Monitor_02   | LG E2060 20" Wide LED                          |
| Keyboard     | Xanova Magnetar RGB XK700 Switch Cherry Brown  |
| Mouse        | Logitech G300s                                 |

## Gather Kexts

- [AppleALC.kext](https://github.com/acidanthera/AppleALC/releases)
- [IntelMausiEthernet.kext](https://onedrive.live.com/?authkey=%21APjCyRpzoAKp4xs&id=FE4038DA929BFB23%21455134&cid=FE4038DA929BFB23)
- [FakePCIID_Intel_HDMI_Audio](https://github.com/the-darkvoid/OS-X-Fake-PCI-ID)
- [FakePCIID](https://github.com/RehabMan/OS-X-Fake-PCI-ID)
- [IntelMausi](https://github.com/acidanthera/IntelMausi)
- [LucyRTL8125Ethernet](https://github.com/Mieze/LucyRTL8125Ethernet)
- [NVMeFix](https://github.com/acidanthera/NVMeFix)
- [SMCProcessor](https://github.com/acidanthera/VirtualSMC)
- [SMCSuperIO](https://github.com/acidanthera/VirtualSMC)
- [USBPorts](https://github.com/headkaze/Hackintool)
- [Lilu.kext](https://github.com/acidanthera/Lilu/releases)
- [VirtualSMC.kext](https://github.com/acidanthera/VirtualSMC/releases)
- [WhateverGreen.kext](https://github.com/acidanthera/WhateverGreen/releases)
- [XHCI-unsupported](https://github.com/RehabMan/OS-X-USB-Inject-All)

You'll use MacOS Monterey

- Rename `EFI-Monterey` to `EFI`

1. Use Clover Configurator (or ESP Mounter Pro, in project folder ) to mount the EFI partition of the USB drive
2. Copy the downloaded .kexts to `EFI/CLOVER/kexts/` on the USB drive EFI partition

## Boot

Fast Boot → Disabled
CSM → Launch CSM → Disabled
Secure Boot → OS Type → Other OS

> For Big Sur: Search "serial" and disable!
