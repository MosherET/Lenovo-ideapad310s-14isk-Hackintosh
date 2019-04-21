# Lenovo-ideapad310s-14isk-Hackintosh
## Lenovo-ideapad-310s-14isk(i7-6500U 8GB/256GB/2GB独显)

### 一．	机型配置
|  硬件  | 型号 |
|  ---- | -----------------|
| 处理器 |	Intel Core i7-6500U |  
| 系统内存 |	8GB 2133 MHz DDR4|
| 核显     |   Intel HD Graphics 520 2048MB|
| 独显      |  AMD Radeon R5 M430 2048MB |
| 显示器     |  14-英寸(1366 x 768) |
| 音频适配器  |ALC236|
| 网卡       | Realtek RTL8168H/8111H |
| 无线网卡    | 使用小米随身Wi-Fi |
| 硬盘       | 三星Nvme (256GB) |

### 二．	正常工作截图

#### 显卡HD520
使用默认核显驱动，注入ID 0x1916000，显存更改为2048MB，工作正常。<br>
![image](https://github.com/MosherET/Images/raw/master/Lenovo-ideapad310s-14isk-Hackintosh/1-zonglan.png) 
#### 声卡ALC236
使用AppleALC1.3.6 注入ID 3，内置扬声器和耳机都工作正常。<br>
![image](https://github.com/MosherET/Images/raw/master/Lenovo-ideapad310s-14isk-Hackintosh/audio-1.png)<br>
![image](https://github.com/MosherET/Images/raw/master/Lenovo-ideapad310s-14isk-Hackintosh/audio-2.png)<br>
![image](https://github.com/MosherET/Images/raw/master/Lenovo-ideapad310s-14isk-Hackintosh/audio-3.png)<br>
![image](https://github.com/MosherET/Images/raw/master/Lenovo-ideapad310s-14isk-Hackintosh/audio-4.png)<br>
#### 键盘触摸板
使用PS2设备默认驱动，工作正常。<br>
 ![image](https://github.com/MosherET/Images/raw/master/Lenovo-ideapad310s-14isk-Hackintosh/chumoban.png)<br>
#### USB
使用USBPorts.kext和USBInjectAll.kext驱动，工作正常。<br>
![image](https://github.com/MosherET/Images/raw/master/Lenovo-ideapad310s-14isk-Hackintosh/USB.png)<br>
 
#### 原生电源管理正常
![image](https://github.com/MosherET/Images/raw/master/Lenovo-ideapad310s-14isk-Hackintosh/dianyuan.png)<br>
![image](https://github.com/MosherET/Images/raw/master/Lenovo-ideapad310s-14isk-Hackintosh/dianyuan-1.png)<br>
#### 亮度调节正常
![image](https://github.com/MosherET/Images/raw/master/Lenovo-ideapad310s-14isk-Hackintosh/light.png)

#### 网卡
![image](https://github.com/MosherET/Images/raw/master/Lenovo-ideapad310s-14isk-Hackintosh/realetek.png)

#### WIFi和蓝牙
WIFI使用小米随身Wi-Fi（MI WLAN Adapter）配合RT2870驱动和Wireless Utility软件工作正常。<br>
![image](https://github.com/MosherET/Images/raw/master/Lenovo-ideapad310s-14isk-Hackintosh/WiFi-1.png)
![image](https://github.com/MosherET/Images/raw/master/Lenovo-ideapad310s-14isk-Hackintosh/WiFi-2.png)

#### 蓝牙工作正常 
![image](https://github.com/MosherET/Images/raw/master/Lenovo-ideapad310s-14isk-Hackintosh/Buletooth.png)

#### 内存
![image](https://github.com/MosherET/Images/raw/master/Lenovo-ideapad310s-14isk-Hackintosh/neicun.png)
#### 睡眠唤醒正常
### 三．	尚未解决
HDMI未尝试，工作状态未知 <br>
其他bug待发现... <br>

### 四．	备注
可直接将整个EFI文件夹复制进U盘和安装磁盘的EFI分区，具体操作方法见黑果小兵部落阁 <br>

[镜像与安装教程](https://blog.daliansky.net/macOS-Mojave-10.14.4-18E226-official-version-with-Clover-4903-original-image.html)

## @mos
### 2019-04-20 更新
	

