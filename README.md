# Acer-Aspire-VX5-591G-Hackintosh
Clover folder based in: Acer Aspire VX15 VX5-591G

[English](README.md) | [中文](README-zh-CN.md)

|   Specification   |               Details                |
| :------: | :-----------------------------------: |
| Computer Model |     Acer Aspire VX15 VX5-591G      |
| Operating System |         macOS Catalina 10.15.4        |
|  CPU  |      Intel(R) Core(TM) i5 7300HQ      |
|   RAM   |         16 GB DDR4 2400MHz           |
|   Hard Disk   |    WD BLUE 3D NAND SSD      |
|   Graphics card   |         Intel HD Graphics 630         |
|   Sound card   |                ALC255                 |
|   Motherboard   |                 V1.08                 |
|  Touchpad BIOS |         _SB.PCI0.I2C1.TPAD         |
| WLAN |        Realtek RTL8100/8111         |
| LAN |      Qualcomm Atheros QCA61x4a       |
|  USB WLAN  |           Tenda U12 USB Wireless           |

## Working hardware
* Intel Core i5-7300HQ 2.5GHz
* Intel HD Graphics 630
* 16 GB 2400 MHz DDR4
* 15.6' Full HD with Screen Brightness
* WebCam
* Battery
* Keyboard with Backlight
* LAN network
* HDMI
* Bluetooth
* 2xUSB 3.0 1xUSB 2.0
* I2C HID touchpad
* Audio

## Not working hardware
* Nvidia GTX1050 2G
* Qualcomm Wireless -> Tenda U12 USB wireless，Official driver：[Download](https://www.tenda.com.cn/product/download/U12.html)
* SD Slot

## Existing flaws
* Output audio is low
* Noise from headphone output

## Not tested
* USB-C

#### 1、Mirror source：[PCbeta](http://bbs.pcbeta.com/viewthread-1836586-1-1.html), [BaiduNetdisk](https://pan.baidu.com/s/1kMmmfiDuGbB1FK27UOsnZw) Extraction code：j2kk，Personal transport [BaiduNetdisk](https://pan.baidu.com/s/1fOuvAG9exDhwUFMkX2BPlg) Extraction code: 1amx，Thanks for Developer！

#### 2、According to [@chakid](https://github.com/chakid/Acer-VX15-Hackintosh) and [@net32](https://github.com/net32/VX5-591G)‘s EFI
![01.png](https://github.com/LanbenGG/Acer-Aspire-VX5-591G-Hackintosh/blob/master/Picture/01.png)
![02.png](https://github.com/LanbenGG/Acer-Aspire-VX5-591G-Hackintosh/blob/master/Picture/02.png)
![03.png](https://github.com/LanbenGG/Acer-Aspire-VX5-591G-Hackintosh/blob/master/Picture/03.png)
![04.png](https://github.com/LanbenGG/Acer-Aspire-VX5-591G-Hackintosh/blob/master/Picture/04.png)

#### 3、My touchpad is different from others，My touchpad is I2C HID，So I use [@alexandred](https://github.com/alexandred/VoodooI2C)‘s VoodooI2C Drive，supported all gestures, （⚠️To use this driver, you need to delete the AppleIntelLpssI2C.kext and AppleIntelLpssI2CController.kext in S/L/E）
![touchpad01.png](https://github.com/LanbenGG/Acer-Aspire-VX5-591G-Hackintosh/blob/master/Picture/touchpad01.png)
![touchpad02.png](https://github.com/LanbenGG/Acer-Aspire-VX5-591G-Hackintosh/blob/master/Picture/touchpad02.png)
![touchpad03.png](https://github.com/LanbenGG/Acer-Aspire-VX5-591G-Hackintosh/blob/master/Picture/touchpad03.png)

### Thanks
* [CloverBootloader](https://github.com/CloverHackyColor/CloverBootloader)
* [WhateverGreen](https://github.com/acidanthera/WhateverGreen)
* [Lilu](https://github.com/acidanthera/Lilu)
* ......
