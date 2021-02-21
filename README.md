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
  * [FortiClient VPN 客户端](001.md#forticlient-vpn-%E5%AE%A2%E6%88%B7%E7%AB%AF)
  * [EasyConnect VPN 客户端](001.md#easyconnect-vpn-%E5%AE%A2%E6%88%B7%E7%AB%AF)
  * Docker
  * C & C++
  * Nodejs
  * JDK
  * Golang
  * Python
  * Rust
  * VS Code
  * Electerm
  * Remmina
  * Insomnia
  * Typora
  * Joplin
  * KeepassXC
  * Seafile
  * 坚果云
  * WPS
  * FlameShot 火焰截图
  * GIMP
  * 网易云音乐
  * Chrome
  * 微信
  * fqterm
* [之二](./002.md)
  * XMind
  * MindMaster
  * Sublime Text 3
  * Umbrello
  * drawio
  * Pencil
  * 中望 CAD
  * Krita 绘图工具
  * DBeaver
  * 有道词典
  * VeraCrypt
  * Cryptomator
  * 腾讯视频客户端
  * QQ 音乐
* [之三](./003.md)
  * 铜豌豆 Linux 软件
  * VirtualBox
  * xDroid
  * GitAhead