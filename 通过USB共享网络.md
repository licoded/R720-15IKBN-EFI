> USB无线网卡虽然小巧但在使用windows的时候很多余，甚至会影响win10蓝牙的正常使用。而手机和USB数据线是出门必备，安装一个软件后就可以实现手机通过USB共享网络给黑苹果。

[GitHub链接](https://github.com/jwise/HoRNDIS)
[官网链接](https://www.joshuawise.com/horndis)

> 安装成功后需要重启系统才能正常使用！

### 10.15Catalina安装失败

终端输入命令，亲测有效。

```bash
sudo mount -uw /
```

> 其他解决方案见[issue](https://github.com/jwise/HoRNDIS/issues/102#issuecomment-551255547)