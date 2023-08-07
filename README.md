# B150M-PRO4-HYPER-Hackintosh

- B150M-PRO4/HYPER OpenCore EFI Firmware

## 规格 

- EFI 适用于 B150M-PRO4/HYPER
- 使用 OpenCore v0.6.6

## 配置

- CPU：英特尔酷睿i5-6600
- 主板：Asrock b150m pro4/hyper
- 内存：DDR4 2133 24GB（8+8+4+4）
- 显卡：超频 Radeon RX570 4GB
- SSD：三星 850 evo SATA SSD 250 GB（适用于 macOS）
- SSD：西数 Black SN700 NVMe 500GB（适用于Win10）
- 硬盘：西数 Blue WD20EZAZ 2TB（用于数据）
- 声音：瑞昱ALC892
- 网卡：英特尔I219-V
- Wi-Fi/BT：博通 BCM94350ZAE

## 有效

- Wi-Fi/BT（安装单独无线网卡）
- 3.5音频
- USB端口
- 以太网
- QE/CI
- 无头

## 无效

- 睡眠

## BIOS 设置

- 

## EFI 配置

### 内核扩展

- [AirportBrcmFixup](https://github.com/acidanthera/AirportBrcmFixup) v2.1.2
- [AppleALC](https://github.com/acidanthera/AppleALC) v1.5.7
- [BrcmBluetoothInjector](https://github.com/acidanthera/BrcmPatchRAM) v2.5.6
- [BrcmFirmwareData](https://github.com/acidanthera/BrcmPatchRAM) v2.5.6
- [BrcmPatchRAM3](https://github.com/acidanthera/BrcmPatchRAM) v2.5.6
- [IntelMausi](https://github.com/acidanthera/IntelMausi) v1.0.5
- [Lilu](https://github.com/acidanthera/Lilu) v1.5.1
- [SMCProcessor](https://github.com/acidanthera/VirtualSMC) v1.2.0
- [SMCSuperIO](https://github.com/acidanthera/VirtualSMC) v1.2.0
- [VirtualSMC](https://github.com/acidanthera/VirtualSMC) v1.2.0
- [VoodooPS2Controller](https://github.com/acidanthera/VoodooPS2) v2.2.1
- [WhateverGreen](https://github.com/acidanthera/WhateverGreen) v1.4.7

### EFI

- HfsPlus
- OpenCanopy
- OpenRuntime
- Ps2KeyboardDxe
- Ps2MouseDxe

### SSDT

- SSDT-EC-USBX : fake ec, usb controller
- SSDT-GPRW : GPRW method hotpatch
- SSDT-OSYS : macOS check fix
- SSDT-PLUG : Enable XCPM

