# 打造 Ubuntu 桌面工作环境
The documents about how to setup my Ubuntu Desktop for daily work...

软件版本以文档撰写时为准，请自行去官方网站获取最新版本信息。

目前来看，主要是**企业微信**还不能很好的在 Linux 环境下使用，利用 Wine 跑起来的企业微信响应十分迟钝，基本算是不可用。这个就只能通过远程使用公司电脑或者安装 Windows 虚拟机解决了。

![Ubuntu2004.png](./images/Ubuntu2004.png)



## 基本系统

**Ubuntu 20.04 LTS**

修改软件仓库为国内镜像：
```bash
sed -i 's/archive\.ubuntu\.com/mirrors\.tuna\.tsinghua\.edu\.cn/g' /etc/apt/sources.list
sed -i 's/security\.ubuntu\.com/mirrors\.tuna\.tsinghua\.edu\.cn/g' /etc/apt/sources.list
```

更新软件到最新：
```bash
sudo apt-get update
sudo apt-get dist-upgrade
```



## 笔记

* [之一](./001.md)
* [之二](./002.md)
* [之三](./003.md)