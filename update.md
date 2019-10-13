## 更新日志

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