# MinerProxy


最稳定的ETH以太坊代理中转矿池程序，MinerProxy/矿池代理，支持TCP和SSL协议，支持自定义抽水，高性能高并发，支持web界面管理，包含自启动和进程守护，重启后可以自动运行，会放开防火墙和连接数限制，一键搞定。

<p align="center">
  <a>
    <img src="https://img.shields.io/badge/Release-1.5.2_ETHASH-orgin.svg" alt="travis">
  </a>
  <a>
    <img src="https://img.shields.io/badge/Last_Update-2022_04_17-orgin.svg" alt="travis">
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
