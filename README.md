[![](https://img.shields.io/badge/TG群-点击加入-FFFFFF.svg)](https://t.me/joinchat/AAAAAEpRF88NfOK5vBXGBQ)


欢迎来到sirpdboy的源码仓库！
=
Welcome to sirpdboy's  git source of packages
-
### [sirpdboy  固件分为：大全版，迷你版，旁路由版，养老版等几个版本](https://github.com/sirpdboy/openwrt18.06/)

### 使用本固件前，请严格遵守国家互联网使用相关法律规定,不要违反国家法律规定！

[![](https://img.shields.io/badge/-目录:-696969.svg)](#readme) [![](https://img.shields.io/badge/-固件说明-F5F5F5.svg)](#固件说明-) [![](https://img.shields.io/badge/-登陆信息-F5F5F5.svg)](#登陆信息-)  [![](https://img.shields.io/badge/-版本信息-F5F5F5.svg)](#版本信息-) [![](https://img.shields.io/badge/-固件下载-F5F5F5.svg)](#固件下载-) [![](https://img.shields.io/badge/-捐助-F5F5F5.svg)](#捐助-) 

------------------------------------------------------

请 **认真阅读完毕** 本页面，本页面包含注意事项和如何使用。

**本固件只在恩山论坛免费发布，未经许可，严禁私自扩散，严禁在淘某宝上出售本固件！！**

**因精力有限不提供任何技术支持和教程等相关问题解答。不保证插件完全无BUG，特此公告！**

### 恩山链接 ：https://www.right.com.cn/forum/thread-4053752-1-1.html

## 【免责声明】
**1.仅限完全行为能力人使用本固件，使用本固件即视为使用者的自愿行为;**

**2.本人不对任何人因使用本固件所遭受的任何理论或实际的损失承担责任;**

**3.本人不保证固件的普适性，不保证无bug，不保证绝对的安全稳定。**

----------------------------------------------------

***本固件基于lean大佬的源码编译，外加一些额外的软件包，主要使用源码如下：***

### https://github.com/coolsnowwolf/lede

### https://github.com/sirpdboy/sirpdboy-package (带定时关机源码）

### 固件说明 [![](https://img.shields.io/badge/-固件说明-F5F5F5.svg)](#固件说明-) 

1、固件上传之前，都是亲自有测试，不排除测试不全面有问题的可能**

2、本固件本人保证没加入任何后门**

3、强烈建议不保留配置刷入本固件，可以减少很多问题，如果此前是刷的本人固件可以同版本保留配置升级**

4、因为固件是在线编译，”IMG写盘工具“支持不太好，提示错误不影响正常使用，可直接压缩包升级或者用网盘中命令行刷机工具**

5、不管什么问题请先自己学习研究再寻求帮助，群里的人没有义务来帮你以及回复一些无聊与无知的问题，需要帮助的可以去某**

### 补充说明：

--------------------------------------------------------------

##文件下载请看日期文件名内容下载;

如文件名中：20200514表示是编译时间是2020年5月14日;

如文件名中：有IPV6表示支持IPV6的固件;

如文件名中：有EFI表示支持EFI快速引导模式，否则是标准BIOS模式;

如文件名中：有mini表示精简版本、Super表示极致版，Plus表示大全版。

如文件名中：有P表示旁路由版本

如文件名中：有R2S表示R2S机器使用版本

本固件基于lean大佬的源码编译。在此感谢所有无私奉献源码的大佬们！
 
### openwrt 登陆信息 [![](https://img.shields.io/badge/-登陆信息-F5F5F5.svg)](#登陆信息-)

---------------------------------------------------------------------------------------  

**2022年3月20日之前【固件IP】：192.168.1.1  密码： password或者 密码空

**2022年3月20日【统一固件IP】：192.168.8.1  密码无 

---------------------------------------------------------------------------------------

2022-6-1更新：【sirpdboy独家优化】     （IPV6大全版  5.15.41  内核【带DOCKER】 + IPV6精简版 5.15.41内核  + IPV6极致版 5.15.41 内核  ）  【养老版】

在上个版本的基础上优化更新如下：

1.增加常见无线驱动,名称自动区分：OP-2.4G和OP-5G，密码：12345678

2.增加预览首页实时【CPU主频】显示.

3.驱动大全再加上bcm5719驱动（待测试）

4.升级netdata1.33.1汉化版本。

5.更新bypass不能导入和导出节点等问题

6.新打包rootfs文件，PVE使用LCX容器的福音。

7.修复上个版本MWAN3负载没有负载信息问题.

8.修复adguardhome内核更新导致不能进入的问题

9.增加主题 darkmatter和neobird。

10.修复上个版系统日志循环eth1报错等问题.。

11.由于KPR不支持5.15内核，全线下架换成[广告屏蔽大师]。

---------------------------------------------------------------------------------------

2022-5-1更新：【sirpdboy独家优化】     （IPV6大全版  5.15.36  内核【不带DOCKER】 + IPV6精简版 5.15.36内核 【带DOCKER】+ IPV6精简版 5.15.36内核  + IPV6极致版 5.15.36 内核  + R2S IPV6精简版 5.15.36内核 + R4S IPV6精简版 5.15.36内核）  

更新内容如下：【在上个版本的基础上优化更新如下】

1.修复流量统计，标记二台未知设备的名字【总有人不知道二个未知的MAC是什么机器在偷跑流量，其实是LAN 和WAN二个接口】。

2.提高网络管控，升级时间控制为家长控制，可时间控制，协议过滤，端口过滤，黑名单模式等。

3.新加登入管控插件，增加OPENWRT安全性。【所有版本】

4.新加断线检测执行指定任务功能【所有版本】

5.升级多拨带IPV6功能。【除极致版外】

6.升级MWAN3多线负载支持IPV6，此版本配置是默认配置带WAN6负载均衡。【除极致版外】

7.加回open-vm-tools取消qemu-ga。

8.zerotier取消新版防火墙功能返回老版本。

9.增加Tailscale依赖。【TG群内测群友推荐】

10.PASSwall升级最新版本。

11.所有版本集成群主自用版bypass和增加smartdns，修复已知问题。【源码来自OVERWALL】

--------------------------------------------------------------------------------------

### 固件下载地址：[![](https://img.shields.io/badge/-固件下载-F5F5F5.svg)](#固件下载-)
 
##【123云盘下载】链接:https://www.123pan.com/s/dS5A-By4qd 提取码:SeY7

**Telegram聊天群组: https://t.me/joinchat/RV6mxIxZJVDByibQ

**加入固件电报群：https://t.me/joinchat/AAAAAEpRF88NfOK5vBXGBQ 

--------------------------------------------------------------

## 说明 [![](https://img.shields.io/badge/-说明-F5F5F5.svg)](#说明-)

源码来源：https://github.com/sirpdboy/sirpdboy-package

![xm1](doc/登陆界面2.jpg)
![xm2](doc/预览界面.jpg)
![xm3](doc/高级设置.jpg)
![xm3](doc/网络共享.jpg)
![xm3](doc/合并图.jpg)

**感谢LEAN大，感谢Lienol大 等大神分享源码，你可以随意使用其中的源码，但请注明出处。**

# My other project

网络速度测试 ：https://github.com/sirpdboy/NetSpeedTest

定时关机重启 : https://github.com/sirpdboy/luci-app-autotimeset

关机功能插件 : https://github.com/sirpdboy/luci-app-poweroffdevice

opentopd主题 : https://github.com/sirpdboy/luci-theme-opentopd

opentoks 主题: https://github.com/sirpdboy/luci-theme-opentoks [仿KOOLSAHRE主题]

btmob 主题: https://github.com/sirpdboy/luci-theme-btmob

系统高级设置 : https://github.com/sirpdboy/luci-app-advanced

## 捐助 [![](https://img.shields.io/badge/-捐助-F5F5F5.svg)](#捐助-) 

**如果你觉得此项目对你有帮助，请捐助我们，以使项目能持续发展，更加完善。··请作者喝杯咖啡~~~**

**你们的支持就是我的动力！**

------------------------------

## 赞助名单


**j*g                  赞助200元

***ㄎ                  赞助15元

***群                  赞助50元

***看                  赞助8.8元

***洋                  赞助5元

***畅                  赞助50元

***石                  赞助7.77元

***阳                  赞助66.66元

***儒                  赞助10元

***斌                  赞助10元

**C*o                  赞助20元

***洗                  赞助30元

**p*k                  赞助50元

**KK                   赞助600元

**潮                   赞助50元

------------------------------

### 捐助方式

|     <img src="https://img.shields.io/badge/-支付宝-F5F5F5.svg" href="#赞助支持本项目-" height="25" alt="图飞了😂"/>  |  <img src="https://img.shields.io/badge/-微信-F5F5F5.svg" height="25" alt="图飞了😂" href="#赞助支持本项目-"/>  | 
| :-----------------: | :-------------: |
|![xm1](doc/支付宝.png) | ![xm1](doc/微信.png) |

<a href="#readme">
    <img src="https://img.shields.io/badge/-返回顶部-orange.svg" alt="图飞了😂" title="返回顶部" align="right"/>
</a>

## DD刷机教程 ：![点击阅读](doc/【推荐】用dd命令写盘【保姆级图文教程】.pdf)



[![](https://img.shields.io/badge/TG群-点击加入-FFFFFF.svg)](https://t.me/joinchat/AAAAAEpRF88NfOK5vBXGBQ)

