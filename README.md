# ASRock-Z370m-ITX/ac



## 使用方式

1. 在`Releases`中下载`EFI`
2. 默认使用的是4K主题，需要1080p的可以将主题修改为`Minimalism`
3. 使用`Clover Configuration`随机一个新的序列号，以防和别人重复出现不必要的问题。



## 更新日志

### 2019-07-12

> 强迫症更新了测试版，总体来说变化不大，可以流畅使用。

10.15 db3存在的问题有

1. 夜览功能不能正常开启。需要切换分辨率，重启后又失效。
2. sle不能写入，只能读取。
3. 会多出一些文件夹，并且不能删。强删系统就炸了（开不了机了，我试过😂）



+ Update `Clover` 4980
+ Update `Lilu` v1.3.7
+ Update `WhateeverGreen` v1.3.0
+ Update `AppleALC` v1.3.9
+ Add `BrcmBluetoothInjector.kext` 驱动蓝牙和WIFI
+ Change `FakeSMC` to `VirtualSMC 1.0.6` 这俩作用都是一样的，后面这个更好一些。



### 2019-06-29

> 4K是真的爽🤙

+ Update `Clover` 4972
+ Change  `VirtualSMC` to `FakeSMC`
+ Delete `AptioMemoryFix-64.efi`
+ 修改了4K的Clover主题
+ Clover倒数时间修改为1S



### 2019-06-16

+ Update `Clover` 4961
+ Update `Lilu` v1.3.6
+ Update `WhateeverGreen` v1.2.9
+ Update `AppleALC` v1.3.8
+ Update `CPUFriengd` v1.1.7
+ Change `FakeSMC` to `VirtualSMC`
+ Add `SMCProcessor.kext`
+ Add `SMCSuperIO.kext`



### 2019-05-17

+ 初次提交 



## 关于本机

![关于本机](./pic/关于本机.png)



## 系统偏好设置

![关于本机](./pic/系统偏好设置.png)



## 配置

| 名称      | 详情                           |
| --------- | ------------------------------ |
| 主板      | 华擎Z370m-ITX/ac               |
| 处理器    | 英特尔酷睿 i5-8400             |
| 内存      | 海盗船复仇者LPX DDR4 3000 8G*2 |
| 显卡      | 蓝宝石RX590                    |
| 硬盘1     | 三星960EVO 250G (windows)      |
| 硬盘2     | 三星860EVO 250G (macos)        |
| 硬盘3     | HHD 500G (存储与TimeMachine)   |
| 显示器    | LG 27ul500                     |
| WIFI+蓝牙 | BCM94352Z / DW1560             |



## 不工作

+ 睡眠会立即唤醒
  + 但是拔掉USB就可以正常睡眠。可能是定制的USB有问题吧。但是USB的速度是正常的。
+ iMessage和FaceTime不可用

总的来说，不完美，不过影响不大。



## 工作

除了不工作的，一切正常。



## 跑分

![CPU-G](./pic/CPU.png)



![GPU-G](./pic/GPU.png)



## 显示器

![monitor](./pic/monitor.png)



## 蓝牙

Blutbooth ok! 👌
[10.14驱动方式](https://blog.daliansky.net/Broadcom-BCM94352z-DW1560-drive-new-posture.html)

10.15 db3的驱动方式与上面的不同，新增了一个`BrcmBluetoothInjector.kext`

![bluetooth](./pic/bluetooth.png)



## 音频

id设为1

![audio](./pic/audio.png)



## CPU变频

![audio](./pic/cpu变频.png)



## USB

使用Hackintool创建一个了USBPorts。没有用机箱端口。

![usb](./pic/USBPort.png)

![usb](./pic/USB2.png)

![usb](./pic/USB3.png)



## 视频硬解码

使用核显和独显进行硬解码

![usb](./pic/video.png)

![usb](./pic/test.png)

可以看到4K使用独显硬解成功，CPU使用率极低。



## 🍎总结

我也只是个黑苹果的小白，这些东西都是看论坛和大佬的博客学到的。日常使用没有任何问题，睡眠问题对于我来说影响不大。以后有时间再看看，使黑苹果更完美。



[远景论坛](<http://bbs.pcbeta.com/forum-559-1.html>)

[黑果小兵](<https://blog.daliansky.net/>)

[tonymacx86](<https://www.tonymacx86.com/>)
