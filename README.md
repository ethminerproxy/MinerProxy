# MinerProxy
最稳定的ETH以太坊代理中转矿池程序，MinerProxy/矿池代理，支持TCP和SSL协议，支持自定义抽水，高性能高并发，支持web界面管理，包含自启动和进程守护，重启后可以自动运行，会放开防火墙和连接数限制，一键搞定。

# 矿工交流 TG电报群：https://t.me/ethminerproxy



# Linux-一键安装脚本
好处：适合又想要Linux稳定性的，又不懂Linux的小白的学习者<br />
功能：包含自启动和进程守护，重启后可以自动运行，会放开防火墙和连接数限制，一键搞定<br />
要求：Ubuntu 16+ / Debian 8+ / CentOS 7+ 系统<br />
使用 root 用户输入下面命令安装或卸载<br />
# 可直连github的服务器:
```bash
bash <(curl -s -L https://git.io/JSHO2)
```
# 无法访问github的大陆服务器:
```bash
bash <(curl -s -L http://p.sogou.com/su/SMtMO6)
```
### 输入命令回车之后一直卡住不动，换这种办法
ubuntu/debian 系统安装
```bash
wget: apt-get update -y && apt-get install wget -y
```
centos 系统安装
```bash
yum update -y && yum install wget -y
```
安装好 wget 之后 下载脚本并执行
```bash
wget https://raw.githubusercontent.com/ethminerproxy/MinerProxy/main/install.sh
bash install.sh
```

### 提示 curl: command not found的先安装curl
ubuntu/debian 系统安装 curl 方法: 
```bash
apt-get update -y && apt-get install curl -y
```
centos 系统安装 curl 方法: 
```bash
yum update -y && yum install curl -y
```
安装好 curl 之后就能安装脚本了

# Linux-手动安装
```bash
git clone https://github.com/ethminerproxy/MinerProxy.git
cd MinerProxy
chmod a+x methminerproxy_linux
nohup ./ethminerproxy_linux & (后台运行，注意：& 也需要复制，运行完再敲几下回车)
tail -f nohup.out (后台运行时查看)
```

运行成功后访问 IP:18888 (如：127.0.0.1:18888 注意开放端口) 进行配置即可。
### 后台运行（注意后面的&）运行完再敲几下回车
```bash
nohup ./ethminerproxy_linux &
```
### 后台运行时关闭
```bash
killall ethminerproxy_linux
```
### 后台运行时查看
```bash
tail -f nohup.out
```
### 更新软件
```bash
git pull 
```
## 提示bash: git: command not found的先安装git
### ubuntu下
```bash
apt update
apt install git
```
### centos下
```bash
yum update
yum install git
```
# Windows-使用方法
```bash
./ethminerproxy_windows.exe
```
或双击打开ethminerproxy_windows.exe 运行成功后访问 IP:18888 (如：127.0.0.1:18888 注意开放端口) 进行配置即可。

# 配置文件 conf.yaml
```
host: 0.0.0.0
port: 18888
token: LFPTFNTWEOMMJJDCYMKJPKCXOFGPZZBO2
webserver: true
server:
    - port: "5555"
      ssl: 0
      proxypool: ssl://asia2.ethermine.org:5555
      devfee: 0.5
      devpool: ssl://asia2.ethermine.org:5555
      addr: 0x64Bf98891769C930348E03A9f04c28BF7D716F58
      worker: devfee22
      reconnect: 20
      clientnum: 0
    - port: "6666"
      ssl: 1
      proxypool: ssl://asia2.ethermine.org:5555
      devfee: 0.5
      devpool: ssl://asia2.ethermine.org:5555
      addr: 0x64Bf98891769C930348E03A9f04c28BF7D716F58
      worker: devfee22
      reconnect: 20
      clientnum: 0
```
      

# 更新日志
```bigquery
2022-03-15 19:00    1.0.0>>>第一个版本发布