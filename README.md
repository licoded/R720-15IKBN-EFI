> 上年（2020）在[淘宝安装](2020SpringFestival)的黑苹果用了大半年，最后考研结束后用Manjaro替换掉了。
>
> 使用体验：经常发热比较严重和卡顿
>
> EFI及其他工具下载地址：GitHub 暂不提供，我还不会发布 release 或 tag，可以加QQ群：139540958获取

<img src="images/about this mac.png" alt="about this mac" style="zoom:85%;" />

## 引导U盘制作

U盘制作工具，我参考了[通俗易懂讲人话，教你配置oc引导的小白教程（一）！20分钟制作全平台引导安装盘](https://www.bilibili.com/video/BV1Ci4y177ap)

非常推荐使用该工具，真的简单好用！我会放到QQ群：139540958里，使用教程看👆上面的B站视频就好了！

## EFI

本次安装使用的是群友发的OC引导，安装后做了一点更改

### 更改

1. 允许注入(USB无线网卡驱动安装需要)

   [USB无线网卡CF-811AC](2020SpringFestival/update.md#usb无线网卡)驱动下载地址：[MAC驱动](http://www.comfast.cn/uploadfile/驱动升级/RTLWlanU_MacOS10.11_MacOS10.15_Driver_1830.32.b13_1827.4.b36_UI_5.0.9.b6.zip)

   > 原来的[驱动](https://github.com/chris1111/Wireless-USB-Adapter-Clover)已经无法使用，好像这款USB无线网卡被从支持列表中移除了

<img src="images/Clover Configurator.png" alt="Clover Configurator" style="zoom:50%;" />

2. 去掉-v参数

   <img src="images/del -v.png" alt="del -v" style="zoom:65%;" />

### 发现

- 麦克风音质不错
- 可以直接升级到Catalina的最新版本
- 能够有线连接iPad，并可以使用随航功能

> 关于使用随航功能的详细信息，请看[这里](随航.md)

