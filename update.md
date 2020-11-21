## 更新日志

### 2020-11-21

> 升级到 11.0.1 全新版本

+   Update `OpenCore` v0.6.3

升级到最新版本，正常功能与之前保持一致，均可正常使用

### 2020-10-16

> 升级到 10.15.7 正式版

+   Update `OpenCore` v0.6.2
+   Update `Lilu` v1.4.8
+   Update `WhateverGreen` v1.4.3
+   Update `AppleALC` v1.5.3

### 2020-07-05

>   迁移到OC引导，版本为0.5.9

迁移后无任何问题，与之前保持一致，所有功能均可正常使用。

迁移时，只需将自己原先的序列号等信息替换到新的`config.plist`即可。

在下图中对应位置替换即可。

![序列号](https://lepicgo.oss-cn-beijing.aliyuncs.com/img/opencore.jpg)

### 2020-05-30

>   升级到 10.15.5 正式版

+   Update `Lilu` v1.4.4
+   Update `WhateverGreen` v1.3.9
+   Update `AppleALC` v1.4.9

### 2020-04-25

+   Delete EmuVariableUefi-64.efi。添加后`iMessage`可用，却引入了启动倒数失效的问题。删除后`iMessage`仍可用，也无启动等问题
+   Update`Clover`5114
+   Update `Lilu` v1.4.3
+   Update `WhateverGreen` v1.3.8
+   Update `AppleALC` v1.4.8
+   显示器支持音箱时，可使用[MonitorControl](https://github.com/the0neyouseek/MonitorControl)来控制显示器的亮度和声音

### 2020-03-27

> 升级到10.15.4正式版

+ 删除`BrcmPatchRAM2.kext`，替换为`BrcmPatchRAM3.kext`。修复蓝牙只显示却搜索不出任何设备并连接不上的问题

### 2020-03-07

> 升级到10.15.4(19E242d)测试版（新增了HDR功能）

+ 修复iMessage，FaceTime和HandOff功能
  + 修复方法可查看这篇[文章](https://younglele.cn/fix-iMessage-and-FaceTime-for-hackintosh/)
+ Update `Clover` 5104
+ Update `AppleALC` v1.4.6
+ Add EmuVariableUefi-64.efi 用于修复iMessage和FaceTime

### 2020-01-29

> 升级到10.15.3(19D76)版本

+ Update `Lilu` v1.4.1
+ Update `WhateverGreen` v1.3.6
+ Update `AppleALC` v1.4.5

### 2019-12-15

>  升级到10.15.2(19C57)版本

+ Update `Lilu` v1.4.0
+ Update `WhateverGreen` v1.3.5
+ Update `AppleALC` v1.4.4

### 2019-11-10

>  升级到10.15.1(19B88)版本

+ Update `Clover` 5098
+ Update `Lilu` v1.3.9
+ Update `WhateverGreen` v1.3.4
+ Update `AppleALC` v1.4.3

### 2019-10-13

> 升级到10.15(19A582a) beta版本，比正式版版本号高。从10.14.6直接升级上来，很稳定。

+ 新增`BrcmBluetoothInjector.kext`驱动蓝牙
+ 精简`kext`放入`backup`文件夹中

### 2019-08-31

> 升级到10.14.6 (18G95)版本

- Update `Clover` 5058

### 2019-07-23

> 放弃测试版，已升级10.14最后一个正式版10.14.6

- Update `Clover` 5018
- Update `Lilu` v1.3.8
- Update `WhateverGreen` v1.3.1
- Update `AppleALC` v1.4.0
- Update `CPUFriend` v1.1.9
- Update `VirtualSMC` v1.0.7
- Update `AirportBrcmFixup` v2.0.3
- Change `SMBIOS` iMac19.1
- USB端口重新定制（去除了主板上靠近蓝牙的两个USB，添加了机箱端口）
  - [使用Hackintool定制自己的USB](https://younglele.cn/post/use-hackintool-custom-made-usb3.0/)



### 2019-07-12

> 强迫症更新了测试版，总体来说变化不大，可以流畅使用。

10.15 db3存在的问题有

1. 夜览功能不能正常开启。需要切换分辨率，重启后又失效。
2. sle不能写入，只能读取。
3. 会多出一些文件夹，并且不能删。强删系统就炸了（开不了机了，我试过😂）



- Update `Clover` 4980
- Update `Lilu` v1.3.7
- Update `WhateverGreen` v1.3.0
- Update `AppleALC` v1.3.9
- Add `BrcmBluetoothInjector.kext` 驱动蓝牙和WIFI
- Change `FakeSMC` to `VirtualSMC 1.0.6` 这俩作用都是一样的，后面这个更好一些。



### 2019-06-29

> 4K是真的爽🤙

- Update `Clover` 4972
- Change  `VirtualSMC` to `FakeSMC`
- Delete `AptioMemoryFix-64.efi`
- 修改了4K的Clover主题
- Clover倒数时间修改为1S



### 2019-06-16

- Update `Clover` 4961
- Update `Lilu` v1.3.6
- Update `WhateverGreen` v1.2.9
- Update `AppleALC` v1.3.8
- Update `CPUFriengd` v1.1.7
- Change `FakeSMC` to `VirtualSMC`
- Add `SMCProcessor.kext`
- Add `SMCSuperIO.kext`



### 2019-05-17

- 初次提交 