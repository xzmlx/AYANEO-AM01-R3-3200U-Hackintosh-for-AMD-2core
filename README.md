# AYANEO-AM01-R3-3200U-Hackintosh-for-AMD-2core
基于AMD锐龙双核处理器的黑苹果安装实践。Hackintosh Installation Practice Based on AMD Ryzen Dual Core Processor.

配置说明
--------------------------------------------------------------------------
CPU：AMD Ryzen 3 3200U（2核） ✅ ≈R3 2200U

核显：AMD Radeon Vega 3       ✅

有线网卡：RealtekRTL8111      ✅

无线网卡：RealtekRTL8851（可更换）WIFI❌/蓝牙✅

HDMI/DP输出/HDMI音频✅

声卡：ALC269 暂未尝试驱动/3.5耳机接口 未测试

说明/存在的问题
--------------------------------------------------------------------------
本EFI仅在Ventura（13）与Sonoma（14）测试，其余版本请自行测试，理论可支持（11.x-14.x）；

在安装MacOS前请在禁用nootedred.kext（AMD核显驱动）；

机型信息选MacbookPro 16,3，三码已删除，请自行生成更换；

受核显驱动影响（nootedred.kext），VCN（硬件编解码）暂时还有问题，只适合日常使用。

因上传限制，请自行解压kexts驱动文件夹，其中缺乏AirportItlwm.kext(因特尔wifi驱动)，若有需要请自行前往 https://github.com/OpenIntelWireless

--------------------------------------------------------------------------

![微信图片_20240812172613](https://github.com/user-attachments/assets/4c6ff6e7-6b54-43e5-ae7e-a8ffa6b5bc15)

