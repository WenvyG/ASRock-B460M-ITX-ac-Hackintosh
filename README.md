# 华擎-B460M-ITX-ac-Hackintosh

# 中文版｜[English]( README-EN.md)

## 电脑配置

|   规格   |                           详细信息                           |
| :------: | :----------------------------------------------------------: |
|   主板   |                      华擎 B460M-ITX/ac                       |
| 支持系统 | macOS Catalina 10.15.x / Windows 10（使用Boot Camp）/ macOS Big Sur 11 |
|  处理器  |                    英特尔 酷睿 i3 - 10100                    |
|   内存   |                          协徳 8GB*2                          |
|   硬盘   |                         三星 970EVO                          |
|   显卡   |        蓝宝石 Redeon RX570 4GB/Intel UHD Graphics 620        |
|  显示器  |                      优派 VX2478-4K-HD                       |
|   声卡   |                Realtek ALC887  AppleALC ID=12                |
|   网卡   |                      更换为BCM94360CS2                       |
|   机箱   |                           酷鱼 S3                            |

## 引导概况

- `OpenCore`  OC目前版本0.6.2，基于[Acidanthera](https://github.com/acidanthera)官方[Release](https://github.com/acidanthera/OpenCorePkg/releases)，理论上在每月初官方版本OC新发布后，会在一周内跟进更新。
  
    ###### 注：`（新版OC 0.6.2已经支持安装macOS Big Sur，但由于尝试安装BETA版系统所造成的数据丢失或其他一切损失,本人不负任何责任）`
  
- ### 安装前准备
  
  - 开机按`F2`或`Del`进入`BIOS`
  - 设置 `Secure Boot` 为 `Disabled`;
  - 设置`CSM`为`Disable`
  - 设置`CFGLock`为`Disable`
  - `F10` 保存设置并重启

- ### 安装后操作

  - 安装好系统，进入系统
  - 找到`终端`执行一下：`sudo spctl --master-disable`以允许打开第三方应用。

- 镜像下载
  
  - [[**黑果小兵的部落阁**] :【黑果小兵】原版镜像](https://blog.daliansky.net/categories/下载/镜像/)
  - 使用[**gibMacOS**](https://github.com/corpnewt/gibMacOS)
  
- EFI下载
  
<<<<<<< Updated upstream
  - [Releases](https://github.com/WenvyG/ASRock-B460M-ITX-ac-Hackintosh)
=======
  - [Releases](https://github.com/WenvyG/ASRock-B460M-ITX-ac-Hackintosh/releases)
>>>>>>> Stashed changes

- 更新日志  
  
  - [Changelog](Changelog.md)

## 正常工作

- Intel核心显卡
<<<<<<< Updated upstream
- AMD Redeon RX570（已在`config.plist`中注入Mac的`Redeon Pro RX575X`的驱动信息
=======
- AMD Redeon RX570（已注入正版Mac的`Redeon Pro 575X`驱动信息）
>>>>>>> Stashed changes
- Wi-Fi与蓝牙（已将原装的高通网卡替换为`BCM94360CS2`）
- 显示器亮度调节（使用[MonitorControl](https://github.com/MonitorControl/MonitorControl/releases)）
- USB定制
- 声卡
- 有线网卡（Intel I219V12 PCI Express Gigabit Ethernet）
- `OpenCore`下`NVRAM`正常，可以使用`Boot Camp`在macOS和Windows10之间自由切换

## 不正常工作

<<<<<<< Updated upstream
- 任何问题可以在[Issues](https://github.com/WenvyG/Lenovo-ideapad-110-15IKB-Hackintosh/issues)中跟我反馈。
=======
有任何问题可以在[Issues](https://github.com/WenvyG/ASRock-B460M-ITX-ac-Hackintosh/issues)
>>>>>>> Stashed changes

## 鸣谢

- 感谢[Apple](https://www.apple.com/cn/)的macOS
- 感谢 [Acidanthera](https://github.com/acidanthera) 提供 [AppleALC](https://github.com/acidanthera/AppleALC)，[Lilu](https://github.com/acidanthera/Lilu)，[OpenCorePkg](https://github.com/acidanthera/OpenCorePkg)，[VirtualSMC](https://github.com/acidanthera/VirtualSMC)，和 [WhateverGreen](https://github.com/acidanthera/WhateverGreen)。
- 感谢 [daliansky](https://github.com/daliansky) 提供[macOS Catalina镜像下载](https://blog.daliansky.net/categories/下载/镜像/)。
- 感谢[corpnewt](https://github.com/corpnewt)提供[gibMacOS](https://github.com/corpnewt/gibMacOS)和[ProperTree](https://github.com/corpnewt/ProperTree)
- 感谢[MonitorControl](https://github.com/MonitorControl/MonitorControl/releases)

# 注：

- **我所分享的EFI引导文件的目标人群是拥有一定黑苹果基础的的同机型用户，需要自己修改`config.plist`的中的三码。**

  

