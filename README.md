# 说好的免费V2ray


```
vmess://ew0KICAidiI6ICIyIiwNCiAgInBzIjogIjEuMHggSlAtQkdQLUEg5pel5pysIiwNCiAgImFkZCI6ICJqcDAzLnFpYW5nbGllLm9yZyIsDQogICJwb3J0IjogIjgwIiwNCiAgImlkIjogIkY2NkEzNERELTI0QTktODQ3Qi0xMzAyLTcyQzk0RDk3RjgxNyIsDQogICJhaWQiOiAiMCIsDQogICJuZXQiOiAid3MiLA0KICAidHlwZSI6ICJub25lIiwNCiAgImhvc3QiOiAianAwMS1jeGlscy1jb20uYWxpa3VubHVuLmNvbSIsDQogICJwYXRoIjogIiIsDQogICJ0bHMiOiAiIg0KfQ==
```
```
vmess://ew0KICAidiI6ICIyIiwNCiAgInBzIjogIjEwLjB4IFVTLUJhc2ljLUEg576O5Zu9IiwNCiAgImFkZCI6ICJoNHZmdXRjaTEzeWxrZnV4Yncuc3RhdGljLnVzLnFpYW5nbGllLmNmIiwNCiAgInBvcnQiOiAiNDY1IiwNCiAgImlkIjogIkY2NkEzNERELTI0QTktODQ3Qi0xMzAyLTcyQzk0RDk3RjgxNyIsDQogICJhaWQiOiAiMiIsDQogICJuZXQiOiAid3MiLA0KICAidHlwZSI6ICJub25lIiwNCiAgImhvc3QiOiAiIiwNCiAgInBhdGgiOiAiIiwNCiAgInRscyI6ICIiDQp9
```
```
vmess://ew0KICAidiI6ICIyIiwNCiAgInBzIjogIjEuMHggSlAtQkdQLUIg5pel5pysIiwNCiAgImFkZCI6ICJqcDAyLnFpYW5nbGllLm9yZyIsDQogICJwb3J0IjogIjgwIiwNCiAgImlkIjogIkY2NkEzNERELTI0QTktODQ3Qi0xMzAyLTcyQzk0RDk3RjgxNyIsDQogICJhaWQiOiAiMCIsDQogICJuZXQiOiAid3MiLA0KICAidHlwZSI6ICJub25lIiwNCiAgImhvc3QiOiAianAxMC1iamV5b3UtY29tLmFsaWt1bmx1bi5jb20iLA0KICAicGF0aCI6ICIiLA0KICAidGxzIjogIiINCn0=
```
## v2ray和shadowsocks相比，有什么好处？

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
总述
## v2ray安装
[v2ray安装教程](./v2ray-install.md)

快捷复制-V2ray一键安装脚本
```
bash <(curl -s -L https://git.io/v2ray.sh)
```
## vps购买建议

[vps购买建议](./vps.md)

# 墙裂购买
如果你想追求稳定省事，不妨直接购买v2ray服务，在这里强烈推荐[**墙裂**](./qianglie.md)

[直接点我购买](https://xn--noss43i.com/aff.php?aff=627)
