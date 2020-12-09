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



# 2020.11.6

**`OC 0.6.3`**
add EFI--OC-Drivers--ExFatDxe.efi

# 2020.12.9

**`OC 0.6.4`**

OC 0.6.3 ---> 0.6.4

AppleALC 1.5.4 ---> 1.5.5

Lilu 1.4.9 ---> 1.5.0

VirtualSMC 1.1.8 ---> 1.1.9

Whatevergreen 1.4.4 --->1.4.5

