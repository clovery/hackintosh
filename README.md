# hackintosh

## 硬件信息

* CPU    i9-9900k 酷睿八核 盒装CPU处理器   
* 主板    Asus/华硕 ROG STRIX Z390-I GAMING  
* 内存    海盗船(USCORSAIR)DDR4 3200 32GB     
* 硬盘    Intel 512G  SSD固态硬盘 M.2 760P系列 
* 显卡    无                                       
* 电源    海盗船 (USCORSAIR) SF600 白金版
* 机箱    sunmilo机箱定制:T03 A4      
* 散热器  恩杰 X52 240mm一体式水冷散热器

## CCG

Version: 5.21.0.0

https://mackie100projects.altervista.org/download-clover-configurator/

## CloverBootloader
https://github.com/CloverHackyColor/CloverBootloader

## 配置驱动（Kexts）
启动必备
FakeSMC.kext
Lilu.kext
WhateverGreen.kext
显卡
NoVPAJpeg.kext（独立显卡需要，解决无法预览和打开 JPG 图片）
声卡
AppleALC.kext
有线网卡
IntelMausiEthernet.kext
无线网卡
AirportBrcmFixup.kext
蓝牙 (配合 Kext Utility/KextBeast 安装到系统)
BrcmFirmwareRepo.kext
BrcmPatchRAM2.kext

## 参考资源

* [\[安装实录\] 零基础完美黑苹果安装之华硕篇](https://zhuanlan.zhihu.com/p/55991446)
