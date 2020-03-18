# 惠普星14青春版黑苹果安装配置

### 主要配置信息

| 配件名       | 型号                       |
| ------------ | -------------------------- |
| CPU          | Intel(R) Core(TM) i7-8565U |
| 显卡         | Intel UHD Graphics 620     |
| 网卡         | 转接板 + BCM943224PCIEBT2  |
| 声卡         | ALC236                     |
| 硬盘         | Intel 760p 256G nvme       |
| 内存         | 16G samsung 2666 * 2       |
| 显示器       | 1920x1080(14 英寸)         |
| MacOSVersion | 10.14.6                    |

### 说明

1.安装请使用pcbeta论坛大佬或黑果小兵整合的安装包，安装完成后再使用该EFI替换，并修改EFI中的机型和三码

2.目前只兼容到macOS10.14.6

3.内置硬盘、内存和网卡均已替换

4.无线网卡替换为BCM943224PCIEBT2 + NGFF转接卡，转接卡需注意长度可能需要截取掉尾部超出的部分

### 工作的功能

1.喇叭外放最大音量正常，麦克风正常

2.集显驱动正常

3.电池驱动正常

4.无线网卡，蓝牙正常(BCM943224PCIEBT2，添加启动参数`brcmfx-country=#a`解决 5GWiFi无法识别问题，添加AirportBrcmFixup.kext解决隔空投送问题)

5.摄像头正常

6.打印机正常

7.小太阳亮度调节正常(FN + F2，F3调节)


### 待完善功能

1.HDMI外接显示器待测试（身边无外接显示器）

2.触摸板无法正常驱动（个人不用触摸板）

