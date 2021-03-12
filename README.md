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
  * [Docker](001.md#docker)
  * [C & C++](001.md#c--c)
  * [Nodejs](001.md#nodejs)
  * [JDK](001.md#jdk)
  * [Golang](001.md#golang)
  * [Python](001.md#python)
  * [Rust](001.md#rust)
  * [VS Code](001.md#vs-code)
  * [Electerm SSH客户端管理](001.md#electerm)
  * [Remmina 远程访问管理](001.md#remmina)
  * [Insomnia API测试](001.md#insomnia)
  * [Typora Markdown撰写](001.md#typora)
  * [Joplin 笔记管理](001.md#joplin)
  * [KeepassXC 密码管理](001.md#keepassxc)
  * [Seafile](001.md#seafile)
  * [坚果云](001.md#%E5%9D%9A%E6%9E%9C%E4%BA%91)
  * [WPS](001.md#wps)
  * [FlameShot 火焰截图](001.md#flameshot-%E7%81%AB%E7%84%B0%E6%88%AA%E5%9B%BE)
  * [GIMP 图像处理](001.md#gimp)
  * [网易云音乐](001.md#%E7%BD%91%E6%98%93%E4%BA%91%E9%9F%B3%E4%B9%90)
  * [Chrome](001.md#chrome)
  * [微信](001.md#%E5%BE%AE%E4%BF%A1)
  * [fqterm BBS客户端](001.md#fqterm)
* [之二](./002.md)
  * [XMind 思维导图](002.md#xmind)
  * [MindMaster 思维导图](002.md#mindmaster)
  * [Sublime Text 3](002.md#sublime-text-3)
  * [Umbrello UML图](002.md#umbrello)
  * [drawio 流程、关系图等绘制](002.md#drawio)
  * [Pencil 软件原型设计](002.md#pencil)
  * [中望 CAD](002.md#%E4%B8%AD%E6%9C%9B-cad)
  * [Krita 绘图工具](002.md#krita-%E7%BB%98%E5%9B%BE%E5%B7%A5%E5%85%B7)
  * [DBeaver 数据库图形客户端](002.md#dbeaver)
  * [有道词典](002.md#%E6%9C%89%E9%81%93%E8%AF%8D%E5%85%B8)
  * [VeraCrypt 文件加密](002.md#veracrypt)
  * [Cryptomator 文件加密](002.md#cryptomator)
  * [腾讯视频客户端](002.md#%E8%85%BE%E8%AE%AF%E8%A7%86%E9%A2%91%E5%AE%A2%E6%88%B7%E7%AB%AF)
  * [QQ 音乐](002.md#qq-%E9%9F%B3%E4%B9%90)
* [之三](./003.md)
  * [铜豌豆 Linux 软件](003.md#%E9%93%9C%E8%B1%8C%E8%B1%86-linux-%E8%BD%AF%E4%BB%B6)
  * [VirtualBox 虚拟机](003.md#virtualbox)
  * [xDroid 安卓模拟器](003.md#xdroid)
  * [GitAhead Git图形客户端](003.md#gitahead)
  * [Double Commander 文件管理器](003.md#double-commander)
  * [福昕 PDF 阅读器](003.md#%E7%A6%8F%E6%98%95-pdf-%E9%98%85%E8%AF%BB%E5%99%A8)
  * [EverNote 第三方客户端](003.md#evernote-%E7%AC%AC%E4%B8%89%E6%96%B9%E5%AE%A2%E6%88%B7%E7%AB%AF)
  * [Meld 文件对比](003.md#meld-%E6%96%87%E4%BB%B6%E5%AF%B9%E6%AF%94)
  * [XnViewMP 看图软件](003.md#xnviewmp-%E7%9C%8B%E5%9B%BE%E8%BD%AF%E4%BB%B6)
  * [digiKam 相册管理](003.md#digikam-%E7%9B%B8%E5%86%8C%E7%AE%A1%E7%90%86)
  * [Kazam 录屏软件](003.md#kazam-%E5%BD%95%E5%B1%8F%E8%BD%AF%E4%BB%B6)
  * [Kdenlive 视频编辑](003.md#kdenlive-%E8%A7%86%E9%A2%91%E7%BC%96%E8%BE%91)



