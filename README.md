# hackintosh

## 硬件信息

* CPU    i9-9900k 酷睿八核
* 主板    Asus/华硕 ROG STRIX Z390-I GAMING  
* 内存    海盗船(USCORSAIR)DDR4 3200 32GB
* 硬盘    Intel 512G  SSD固态硬盘 M.2 760P系列 
* 显卡    集显
* 电源    海盗船 (USCORSAIR) SF600 白金版
* 机箱    sunmilo机箱定制:T03 A4
* 散热器  恩杰 X52 240mm一体式水冷散热器

## linux 读取 BIOS 信息

```sh
$ sudo dmidecode | less
```

## Kext

* WhateverGreen.kext
* AppleALC.kext
* IntelMausi.kext
* Lilu.kext
* SMCProcessor.kext
* SMCSuperIO.kext
* USBInjectAll.kext
* VirtualSMC.kext


## Audio

AudioDevice: PciRoot(0x0)/Pci(0x1b,0x0)


## 参考资源

* [\[安装实录\] 零基础完美黑苹果安装之华硕篇](https://zhuanlan.zhihu.com/p/55991446)
* [Dortania's OpenCore Install Guide](https://dortania.github.io/OpenCore-Install-Guide/)
* [macOS 开启 HiDPI，增加4k、2k、1080P、720P等多种分辨率，解决字体小、模糊、睡眠、唤醒黑屏、花屏、无法连接外部显示器、消除出现8个苹果的概率](http://imacos.top/2019/10/08/2319/)
