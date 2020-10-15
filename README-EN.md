# ASRock-B460M-ITX-ac-Hackintosh

# [中文版](README.md)｜English

## Detail of my computer

| Specifications |                            Detail                            |
| :------------: | :----------------------------------------------------------: |
|      M/B       |                     ASRock-B460M-ITX/ac                      |
|     System     | macOS Catalina 10.15.x / Windows10 (Boot Camp) / macOS Big Sur 11 |
|      CPU       |                 Intel Core i3 - 10100(4C8T)                  |
|     Memory     |                      2*8GB DDR4 2666MHz                      |
|      SSD       |                        Samsung 970EVO                        |
|    Graphics    |           AMD Redeon RX570/Intel UHD Graphics 620            |
|    Monitor     |                    ViewSonic VX2478-4K-HD                    |
|     Audio      |                Realtek ALC887  AppleALC ID=21                |
| Wireless Card  |                         BCM94360CS2                          |
|      Case      |                         METALFISH S3                         |

## Situation of EFI

- `OpenCore`   OpenCore' s version is 0.6.2, It's base on the [Acidanthera](https://github.com/acidanthera)'s offical [Release](https://github.com/acidanthera/OpenCorePkg/releases), theoretically I will update the latest version of OC in a week after it is released.

- `EFI-iGPU` used when the Desktop iGPU is used to drive a display.

- `EFI-dGPU-RX570` used when the Desktop iGPU is only used for computing tasks and doesn't drive a display. It has the real Mac's dGPU-Radeon Pro 575X information under `DeviceProperties` -->`PciRoot(0x0)/Pci(0x1,0x0)/Pci(0x0,0x0)`. It might make my RX570 perform better, but you can also delete it without fear and use other graphics cards.

  ##### PS. OC 0.6.2 now is support to install macOS Big Sur to your disk, it's a good news for Hackintosh. `However, it should be noted that I am not responsible for any data loss or all other losses caused by trying to install the BETA version of the software on your computer. `

- ### BIOS Settings
  
  #### Disable
  
  - `Secure Boot` 
  - `CSM`
  - `CFG Lock` (recommended)

- ### EFI
  
  - [Releases](https://github.com/WenvyG/ASRock-B460M-ITX-ac-Hackintosh/releases)

  ### Changelog
  
  - [Changelog](Changelog.md)

## What works:

- Intel UHD Graphins 620
- AMD Redeon RX570
- Wi-Fi and Bluetooth（using `BCM94360CS2`）
- Monitor (Using [MonitorControl](https://github.com/MonitorControl/MonitorControl/releases))
- USB
- Audio
- Intel I219V12 PCI Express Gigabit Ethernet
- NVRAM

## What not woks

- Any other issues you may have can be feed back to me in [Issues](https://github.com/WenvyG/ASRock-B460M-ITX-ac-Hackintosh/issues).

## Credits

- Thanks to [Apple](https://www.apple.com/cn/) for providing macOS
- Thanks to [Acidanthera](https://github.com/acidanthera)  for providing  [AppleALC](https://github.com/acidanthera/AppleALC), [Lilu](https://github.com/acidanthera/Lilu), [OpenCorePkg](https://github.com/acidanthera/OpenCorePkg), [VirtualSMC](https://github.com/acidanthera/VirtualSMC) and [WhateverGreen](https://github.com/acidanthera/WhateverGreen).
- Thanks to [corpnewt](https://github.com/corpnewt) providing [gibMacOS](https://github.com/corpnewt/gibMacOS) and [ProperTree](https://github.com/corpnewt/ProperTree).
- Thanks to [MonitorControl](https://github.com/MonitorControl/MonitorControl/releases).



# This README may not go into details, if you have any questions, just ask me.

