# 2020.10.11

OC 0.6.2

发布OC引导第一版。(1.0)



# 2020.10.15

OC 0.6.2

区分`只使用核显进行视频输出`和`使用独显进行视频输出`所需要使用的EFI。(1.1)

`EFI-iGPU` used when the Desktop iGPU is used to drive a display.

`EFI-dGPU-RX570` used when the Desktop iGPU is only used for computing tasks and doesn't drive a display.	

# 2020.10.21

OC 0.6.2

优化`EFI-dGPU`配置，删除RX570属性，改为推荐使用[`RadeonBoost.kext`](https://github.com/WenvyG/ASRock-B460M-ITX-ac-Hackintosh/tree/main/RadeonBoost.kext/Contents)，使之可以适用范围更广。具体看README。（1.2）

`EFI-iGPU` used when the Desktop iGPU is used to drive a display.

`EFI-dGPU` used when the Desktop iGPU is only used for computing tasks and doesn't drive a display.	

