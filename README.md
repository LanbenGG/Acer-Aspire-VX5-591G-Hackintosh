# Acer-Aspire-VX5-591G-Hackintosh
宏碁初代暗影骑士3黑苹果CLOVER分享

电脑配置

|   规格   |               详细信息                |
| :------: | :-----------------------------------: |
| 电脑型号 |     宏碁 Acer 暗影骑士3 (VX5-591G)      |
| 操作系统 |         macOS Catalina 10.15.3        |
|  处理器  |      Intel(R) Core(TM) i5 7300HQ      |
|   内存   |          16 GB DDR4 2400MHz           |
|   硬盘   |    西部数据 WD BLUE 3D NAND固态硬盘      |
|   显卡   |         Intel HD Graphics 630         |
|   声卡   |                ALC255                 |
|   主板   |                 V1.08                 |
|  触摸板BIOS |         _SB.PCI0.I2C1.TPAD         |
| 内置有线网卡 |        Realtek RTL8100/8111         |
| 内置无线网卡 |      Qualcomm Atheros QCA61x4a       |
|  外置网卡  |           腾达U12 USB无线网卡           |

## 驱动成功的硬件部分
* Intel Core i5-7300HQ 2.5GHz CPU
* Intel HD Graphics 630 核芯显卡
* 16 GB 2400 MHz DDR4 内存
* 15.6寸 Full HD 可调节亮度屏幕
* 摄像头
* 电池电量显示
* 带背光的键盘
* 有线网卡
* HDMI输出
* 原装网卡蓝牙
* 两个USB3.0 一个USB2.0 可通过手机USB共享网络给电脑使用
* I2C HID触摸板
* 可调节音量输入输出音频

## 未成功驱动的设备
* Nvidia GTX1050 2G独立显卡
* 内置高通无线网卡的WI-FI功能 -> 更换了腾达U12外置USB网卡，官方网卡驱动[下载地址](https://www.tenda.com.cn/product/download/U12.html)
* SD 卡插槽

## 存在的缺陷
* 外放输出音频偏小
* 耳机立体声输出有杂音

## 未测试部分
* USB-C

#### 1、镜像来源：[远景论坛](http://bbs.pcbeta.com/viewthread-1836586-1-1.html),大佬的[百度网盘](https://pan.baidu.com/s/1kMmmfiDuGbB1FK27UOsnZw)链接 提取码：j2kk，个人搬运[百度网盘](https://pan.baidu.com/s/1fOuvAG9exDhwUFMkX2BPlg) 提取码: 1amx，感谢大佬！

#### 2、根据大神[@chakid](https://github.com/chakid/Acer-VX15-Hackintosh)和[@net32](https://github.com/net32/VX5-591G)的EFI文件修改，基本完美驱动（除内置网卡的WI-FI功能以外）
![01.png](https://github.com/LanbenGG/Acer-Aspire-VX5-591G-Hackintosh/blob/master/Picture/01.png)
![02.png](https://github.com/LanbenGG/Acer-Aspire-VX5-591G-Hackintosh/blob/master/Picture/02.png)
![03.png](https://github.com/LanbenGG/Acer-Aspire-VX5-591G-Hackintosh/blob/master/Picture/03.png)
![04.png](https://github.com/LanbenGG/Acer-Aspire-VX5-591G-Hackintosh/blob/master/Picture/04.png)

#### 3、触摸板与很多人不同，我的设备是I2C HID的触摸板，所以我使用了[@alexandred](https://github.com/alexandred/VoodooI2C)大神的VoodooI2C驱动，目前基本可以支持所有手势，不过由于暗影骑士的触摸板质量不是很好，有些手势不能完美操作
![touchpad01.png](https://github.com/LanbenGG/Acer-Aspire-VX5-591G-Hackintosh/blob/master/Picture/touchpad01.png)
![touchpad02.png](https://github.com/LanbenGG/Acer-Aspire-VX5-591G-Hackintosh/blob/master/Picture/touchpad02.png)
![touchpad03.png](https://github.com/LanbenGG/Acer-Aspire-VX5-591G-Hackintosh/blob/master/Picture/touchpad03.png)
