# 2020.10.11

**`OC 0.6.2`**

发布OC引导第一版。(1.0)



# 2020.10.15

**`OC 0.6.2`**

区分`只使用核显进行视频输出`和`使用独显进行视频输出`所需要使用的EFI。(1.1)

`EFI-iGPU` used when the Desktop iGPU is used to drive a display.

`EFI-dGPU-RX570` used when the Desktop iGPU is only used for computing tasks and doesn't drive a display.	



# 2020.10.21

**`OC 0.6.2`**

优化`EFI-dGPU`配置，删除RX570属性，改为推荐使用[`RadeonBoost.kext`](https://github.com/WenvyG/ASRock-B460M-ITX-ac-Hackintosh/tree/main/RadeonBoost.kext/Contents)，使之可以适用范围更广。具体在[README](https://github.com/WenvyG/ASRock-B460M-ITX-ac-Hackintosh#引导概况)了解。（1.2）

Optimize `EFI-dGPU`'s configuration to make it more applicable. Get more details from [README](https://github.com/WenvyG/ASRock-B460M-ITX-ac-Hackintosh#引导概况).

`EFI-iGPU` used when the Desktop iGPU is used to drive a display.

`EFI-dGPU` used when the Desktop iGPU is only used for computing tasks and doesn't drive a display.	



# 2020.11.03

**`OC 0.6.3`**

OC 0.6.2 ---> 0.6.3

AppleALC 1.5.3 ---> 1.5.4

Lilu 1.4.8 ---> 1.4.9

VirtualSMC 1.1.7 ---> 1.1.8

Whatevergreen 1.4.3 --->1.4.4



# 2020.11.06

**`OC 0.6.3`**
add EFI--OC-Drivers--ExFatDxe.efi



# 2020.12.09

**`OC 0.6.4`**

OC 0.6.3 ---> 0.6.4

AppleALC 1.5.4 ---> 1.5.5

Lilu 1.4.9 ---> 1.5.0

VirtualSMC 1.1.8 ---> 1.1.9

Whatevergreen 1.4.4 --->1.4.5

得益于OC对macOS新特性的适配，现在可以在`设置--声音--启动时播放声音`选择是否在启动时播放Mac灵魂的`Duang~`



# 2020.12.11

**`OC 0.6.4`**

Misc--Boot--PickerAttributes 1--->17

Misc--Boot--PollAppleHotKeys False--->True

OC 选择磁盘界面现在可以使用鼠标



# 2021.01.09

**`OC 0.6.5`**

OC 0.6.4 ---> 0.6.5

AppleALC 1.5.5 ---> 1.5.6

CPUFriend 1.2.2 ---> 1.2.3

IntelMausi 1.0.4 ---> 1.0.5

NVMeFix 1.0.4 ---> 1.0.5

Whatevergreen 1.4.4 --->1.4.5

OC图形化界面图标更新到Big Sur样式。



# 2021.03.17

`OC 0.6.7`

OC 0.6.5 ---> 0.6.7

AppleALC 1.5.6 ---> 1.5.8

Lilu 1.5.0 ---> 1.5.1

Whatevergreen 1.4.5 ---> 1.4.8

VirtualSMC  1.1.9 ---> 1.2.1

更新OC GUI 样式



# 2021.04.06

`OC 0.6.8`

OC 0.6.7 ---> 0.6.8

AppleALC 1.5.8 ---> 1.5.9

Lilu 1.5.1 ---> 1.5.2

Whatevergreen 1.4.8 ---> 1.4.9

VirtualSMC  1.1.1 ---> 1.2.2

NVMeFix 1.0.5 ---> 1.0.6

更新OC GUI 样式



# 2021.04.20

I’m sorry to inform you that this project has stopped maintenance and and the Repository is archived.

