# 前言
v2ray+ws+tls可以说之目前最稳的上网方式，虽然方法稍微复杂，但稳定性较好，不易被X

有任何问题,建议都可以[向我提问](https://github.com/mwz1tn/free-v2ray/issues)
或者给我发邮件[mzbskccn@gmail.com](Mailto://mzbskccn@gmail.com)

个人水平有限，有哪里不对的地方，恳请指正

若本项目对您有所帮助，[欢迎Star](https://github.com/mwz1tn/free-v2ray)

# 目录
- [前言](#前言)
- [说好的免费V2ray](#说好的免费V2ray)
     - [其他上网方式(备用)](#其他上网方式(备用))
     - [直连网站](#直连网站)
     - [浏览器插件](#浏览器插件)
     - [其他节点](#其他节点)
- [墙裂购买](#墙裂购买)
- [v2ray使用教程(服务器端)](#v2ray使用教程)
    - [v2ray和shadowsocks相比，有什么好处？](#v2ray和shadowsocks相比有什么好处？)
    - [vps购买建议](#vps购买建议)
    - [v2ray安装](#v2ray安装)
        - [V2ray一键安装脚本](#快捷复制-V2ray一键安装脚本)
        - [SS一键安装脚本](#顺便给下SS的安装脚本(自动配置ipv6如果可用的话))
- [v2ray客户端使用](#v2ray客户端使用)
    - [windows](#windows)
    - [Mac](#Mac)
    - [Android(安卓)](#Android(安卓))
    - [ios](#ios)
    - [Linux](#Linux)
    - [直接使用v2ray内核](#提示)
    

# 说好的免费V2ray

一般不能用的话从发现到更换需要几天(小概率)，多多见谅

> Netflix/TVB/Hulu/HBO 访问解锁

> 高达 1000Mbps 速率可用

**订阅地址**
> https://freev2ray.netlify.com/

不会用点我[订阅怎么用？](https://www.bing.com/search?q=v2ray+%E8%AE%A2%E9%98%85&PC=U316&FORM=CHROMN)

提示——打开网址全选，去[Base64解码](https://tool.chinaz.com/tools/base64.aspx)就是Vmess链接(提醒一下，是在右边粘贴)

两个还可以用的ss

```
ss://YWVzLTI1Ni1jZmI6amp5RldReERQOUB3d3cueGlhb2h1b2ppYW4uY2Y6NTg5MTY=#US_1
```
```
ss://YWVzLTI1Ni1jZmI6WGVNUG1LejVEZ0B4aWFvaHVvamlhbi5jZjo2MDAz#Us_2
```


## 其他上网方式(备用)

### 直连网站

打开即可使用，优点可以访问所有的站点

[jsproxy](https://jsproxy.cf/)[被Q]

### 浏览器插件

**建议使用Chrome安装插件**，安装方法参考：[Chrome安装扩展教程](https://jingyan.baidu.com/article/a681b0de7ddd313b19434661.html)  

[Google Helper](http://googlehelper.net/)

[skyZIP代理应用程序](https://git.io/fjSQr)(推荐)
### 其他节点
[免费节点 Lncn.org](https://lncn.org/)(备用)

---

# 墙裂购买

如果你没有太高需求就建议你别自己折腾了

不妨直接购买v2ray服务，简单稳定省事，在这里强烈推荐[**墙裂**](./qianglie.md)

[直接点我购买](https://aff.qianglie.org/aff.php?aff=627)

# v2ray使用教程

## v2ray和shadowsocks相比有什么好处？

* 更完善的协议：V2Ray 使用了新的自行研发的 VMess 协议，改正了 Shadowsocks一些已有的缺点，更难被墙检测到；
* 更强大的性能: 网络性能更好，具体数据可以看 V2Ray 官方博客
* 更丰富的功能：以下是部分V2Ray的功能：

    * mKCP:KCP 协议在 V2Ray 上的实现，不必另行安装 kcptun
    * 动态端口：动态改变通信的端口，对抗对长时间大流量端口的限速封锁
    * 路由功能：可以随意设定指定数据包的流向，去广告、反跟踪都可以
    * 传出代理：看名字可能不太好理解，其实差不多可以称之为多重代理。类似于 Tor 的代理
    * 数据包伪装：类似于 Shadowsocks-rss 的混淆，另外对于 mKCP 的数据包也可伪装，伪装常见流量，令识别更困难
    * WebSocket 协议：可以 PaaS 平台搭建V2Ray，通过 WebSocket 代理。也可以通过它使用 CDN 中转，抗封锁效果更好
    * Mux:多路复用，进一步提高科学上网的并发性能

## vps购买建议

[vps购买建议](./vps.md)


## v2ray安装

[v2ray安装教程](./v2ray-install.md)

### 快捷复制-V2ray一键安装脚本
```
bash <(curl -s -L https://raw.githubusercontent.com/mwz1tn/free-v2ray/master/code/v2ray.sh)
```
### 顺便给下SS的安装脚本(自动配置ipv6如果可用的话)
```
wget -N --no-check-certificate https://raw.githubusercontent.com/mwz1tn/free-v2ray/master/code/ss-go.sh && chmod +x ss-go.sh && bash ss-go.sh
```

---
# v2ray客户端使用

- ## Windows

    - V2RayN [V2RayN 使用教程](https://github.com/233boy/v2ray/wiki/V2RayN%E4%BD%BF%E7%94%A8%E6%95%99%E7%A8%8B)
    [下载链接](https://git.io/fjSfU)
    - clash[教程](./qianglie.md)
    [下载链接](https://git.io/fjyhN)
- ## Mac

    - [V2Ray Mac 使用教程之 V2RayX](https://github.com/Cenmrev/V2RayX)
    -  V2rayU等

- ## Android(安卓)

    - v2rayNG[下载地址](https://github.com/2dust/v2rayNG/releases)
    - Kitsunebi[下载地址](https://git.io/fjSfk)
        
        Kitsunebi支持订阅和导入规则，推荐使用下、


- ## iOS
    - 软件
        - ShadowRocket（小火箭）
        - Kitsunebi
        - Pepi

        三款APP已经全部从国区APP Store下架
    - 方案
        - 申请苹果美区账号，自行购买
        - 破解版(不推荐)，低版本不能很好支持协议，高版本需要登录
        - 万能淘宝(推荐)

- ## Linux

    - [Linux 系统下v2ray客户端使用](https://octopuspalm.top/2018/08/18/Linux%20%E7%B3%BB%E7%BB%9F%E4%B8%8Bv2ray%E5%AE%A2%E6%88%B7%E7%AB%AF%E4%BD%BF%E7%94%A8/)

## 提示

**V2Ray 内核可以单独使用**，也可以配置其它程序一起使用。

官网：https://www.v2ray.com/

[下载地址](https://github.com/v2ray/v2ray-core/releases)

### 使用方式

#### Windows 或 macOS

压缩包内的 config.json 是默认的配置文件，无需修改即可使用。配置文件的详细信息可以在官网找到。

* Windows 中的可执行文件为 v2ray.exe 和 wv2ray.exe。双击即可运行。
  * v2ray.exe 是一个命令行程序，启动后可以看到命令行界面。
  * wv2ray.exe 是一个后台程序，没有界面，会在后台自动运行。
* macOS 中的可执行文件为 v2ray。右键单击，然后选择使用 Terminal 打开即可。

#### Linux

压缩包中包含多个配置文件，按需使用。

可执行程序为 v2ray，启动命令：

```bash
v2ray --config=<full path>
```