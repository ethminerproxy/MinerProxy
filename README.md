# MinerProxy


最稳定的ETH以太坊代理中转矿池程序，MinerProxy/矿池代理，支持TCP和SSL协议，支持自定义抽水，高性能高并发，支持web界面管理，包含自启动和进程守护，重启后可以自动运行，会放开防火墙和连接数限制，一键搞定。

<p align="center">
  <a>
    <img src="https://img.shields.io/badge/Release-4.0.1_ETHASH-orgin.svg" alt="travis">
  </a>
  <a>
    <img src="https://img.shields.io/badge/Last_Update-2022_05_26-orgin.svg" alt="travis">
  </a>
  <a>
    <img src="https://img.shields.io/badge/Language-GoLang-green.svg" alt="travis">
  </a>
  <a>
    <img src="https://img.shields.io/badge/License-Apache-green.svg" alt="travis">
  </a>
</p>

# 交流 TG电报群：https://t.me/ethminerproxy

<img src="https://minerproxy.vip/css/2.png" alt="">
<img src="https://minerproxy.vip/css/4.png" alt="">

# Linux-一键安装脚本
好处：适合又想要Linux稳定性的，又不懂Linux的小白的学习者<br />
功能：包含自启动和进程守护，重启后可以自动运行，会放开防火墙和连接数限制，一键搞定<br />
要求：Ubuntu 16+ / Debian 8+ / CentOS 7+ 系统<br />
强烈建议使用 Ubuntu20.04操作系统<br />
使用 root 用户输入下面命令安装或卸载<br />
# 可直连github的服务器:
```bash
bash <(curl -s -L https://git.io/JSHO2)
```
# 无法访问github的大陆服务器:
```bash
bash <(curl -s -L http://p.sogou.com/su/SMtMO6)
```
# windows版本下载:
[点击下载 ](https://github.com/ethminerproxy/MinerProxy/raw/main/ethminerproxy_windows.exe) 。

# 更新日志
```bigquery
2022-05-26 18:00    4.0.1>>> 适配专业芯片矿机，优化抽水算法，web后台暗黑模式
2022-05-01 00:00    2.2.0>>> 抽水算法重写，抽水更精准，抽水均衡
2022-04-25 15:00    2.0.0>>> 重写中转逻辑、重写抽水逻辑、优化CPU占用、优化抽水算法(抽水更更更准确)
2022-04-17 21:20    1.5.2>>> 优化内存跟CPU占用、优化抽水机制
2022-04-14 18:00    1.5.1>>> 优化中转性能、优化内存占用、优化小算力矿机抽水比例
2022-04-08 18:00    1.5.0>>> 优化抽水算法、优化控制台日志打印、提升性能
2022-04-05 17:00    1.4.2>>> 修复某些情况下代理抽水异常的BUG、优化逻辑，提升性能
2022-03-30 16:00    1.3.0>>> 增加服务硬件信息概况、增加矿池延时信息、优化界面、提升性能
2022-03-25 16:00    1.2.0>>> 增强安全性、增加ETC币种、优化图表展示、性能优化
2022-03-24 17:00    1.1.1>>> 优化折线图、优化数据展示、优化矿机列表
2022-03-22 23:00    1.1.0>>> 修复：抽水矿机名问题，曲线图展示问题，端口列表里面显示离线设备数量
2022-03-15 19:00    1.0.0>>>第一个版本发布
```

# 关于SSL证书
```bigquery
已内置加密SSL证书，可以自定义ssl证书，存放在程序运行目录下server.key和server.pem文件即可；
```

# 关于开发者费用
```bigquery
开发费恒定千三(0.3%)！无论你抽3%还是30%，甚至80%，都是0.3%开发费！ 
```

# 其他
```bigquery
请只设定足够平衡你支出的托管抽水比例，不要抽大动脉，做到可持续发展，托管时请一定告知客户存在托管费

跨池抽水存在难度、协议不一致等原因，可能导致你抽到的算力过大/过小甚至于无法抽取等情况，建议中转矿池跟抽水矿池保持一致

2核心2G内存的搬瓦工，带机3000台，测试8天，机器稳定不掉线

如果你经常掉线或算力不准：

①第一检查挖矿软件配置及内核配置，是否设置超过多少分钟没有成功提交重启内核

②查看你服务器的硬件配置及软件带宽，配置过低可能导致转发性能不足，导致TCP重发及超时

③检查你服务器的网络是否占用超过60%以上，是的话加带宽

④检查你的抽水情况，如果一直没抽到，你的配置可能存在问题，导致各种断连情况，特别是蚂蚁、币安、OK、HIVE等池子
```
# 重要声明
```bigquery
此软件仅供学习交流使用，不建议用于商业用处！
```
# 特别鸣谢
```bigquery
致敬:老矿、独秀、昆仑、她梦、领航科技，还有隔壁老王；
```

