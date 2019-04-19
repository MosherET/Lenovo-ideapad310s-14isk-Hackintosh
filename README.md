# Lenovo-ideapad310s-14isk-Hackintosh
## Lenovo-ideapad-310s-14isk(i7-6500U 8GB/256GB/2GB独显)

### 一．	机型配置
|  硬件  | 型号 |
|  ---- | -----------------|
| 处理器 |	Intel Core i7-6500U |  
| 系统内存 |	8GB 2133 MHz DDR4|
| 核显     |   Intel HD Graphics 520 2048MB|
| 独显      |  AMD Radeon R5 M430
| 显示器     |  14-英寸(1366 x 768) |
| 音频适配器  |ALC236|
| 网卡       | Realtek RTL8168H/8111H |
| 无线网卡    | 使用小米随身Wi-Fi |
| 硬盘       | 三星Nvme (256GB) |

### 二．	正常工作截图
#### 显卡HD520
使用默认核显驱动，注入ID 0x1916000，除显存没有更改为2048MB，其余工作正常。<br>
![image](https://github.com/MosherET/Lenovo-ideapad310s-14isk-Hackintosh/raw/master/Images/1-HD520.png) 
#### 声卡ALC236
使用AppleALC1.3.6 注入ID 3，内置扬声器和耳机都工作正常。<br>
![image](https://github.com/MosherET/Lenovo-ideapad310s-14isk-Hackintosh/raw/master/Images/2-Audio.1.png)<br>
![image](https://github.com/MosherET/Lenovo-ideapad310s-14isk-Hackintosh/raw/master/Images/2-Audio.2.png)<br>
![image](https://github.com/MosherET/Lenovo-ideapad310s-14isk-Hackintosh/raw/master/Images/2-Audio.3.png)<br>
![image](https://github.com/MosherET/Lenovo-ideapad310s-14isk-Hackintosh/raw/master/Images/2-Audio.4.png)<br>
#### 键盘触摸板
使用PS2设备默认驱动，工作正常。<br>
 ![image](https://github.com/MosherET/Lenovo-ideapad310s-14isk-Hackintosh/raw/master/Images/3-chumoban.png)<br>
#### USB
使用USBPorts.kext和USBInjectAll.kext驱动，工作正常。<br>
![image](https://github.com/MosherET/Lenovo-ideapad310s-14isk-Hackintosh/raw/master/Images/4-USB.png)<br>
 
#### 睡眠唤醒正常
#### 原生电源管理正常
![image](https://github.com/MosherET/Lenovo-ideapad310s-14isk-Hackintosh/raw/master/Images/5-battery.1.png)<br>
![image](https://github.com/MosherET/Lenovo-ideapad310s-14isk-Hackintosh/raw/master/Images/5-battery.2.png)<br>
#### 亮度调节正常
![image](https://github.com/MosherET/Lenovo-ideapad310s-14isk-Hackintosh/raw/master/Images/8-light.png)

#### WIFi和蓝牙
WIFI使用小米随身Wi-Fi（MI WLAN Adapter）配合RT2870驱动和Wireless Utility软件工作正常。<br>
![image](https://github.com/MosherET/Lenovo-ideapad310s-14isk-Hackintosh/raw/master/Images/6-WIFI.png)

#### 蓝牙工作正常 
![image](https://github.com/MosherET/Lenovo-ideapad310s-14isk-Hackintosh/raw/master/Images/7-buletoosh.png)
### 三．	尚未解决
目前HD520的显存依然显示1536MB，未更改为2048MB
HDMI未尝试，工作状态未知
其他bug待发现...

### 四．	备注
使用黒果小兵的部落阁分享镜像
【黑果小兵】macOS Mojave 10.14.4 18E226 正式版 with Clover 4903原版镜像

## @mos
### 2019-04-19
	

