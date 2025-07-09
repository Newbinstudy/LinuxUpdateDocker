# LinuxUpdateDocker
Docker 安装与换源脚本，感谢大佬开源，参考自 https://github.com/SuperManito/LinuxMirrors ，用于个人学习和研究。

## 使用方法

### 方法一：
一键运行
```
bash <(curl -sSL https://raw.githubusercontent.com/Newbinstudy/LinuxUpdateDocker/main/docker.sh)
```
只更换Docker镜像加速器
```
bash <(curl -sSL https://raw.githubusercontent.com/Newbinstudy/LinuxUpdateDocker/main/docker.sh)  --only-registry
```

### 方法二：
离线下载脚本
```
curl -O https://raw.githubusercontent.com/Newbinstudy/LinuxUpdateDocker/main/docker.sh 
```
运行脚本：
```
chmod +x docker.sh
```
```
./docker.sh
```
只更换Docker镜像加速器
```
./docker.sh --only-registry
```

## 命令选项（高级用法）
```
bash <(curl -sSL https://raw.githubusercontent.com/Newbinstudy/LinuxUpdateDocker/main/docker.sh)  --help
```
或
```
./docker.sh --help

命令选项(名称/含义/值)：

  --source                 指定 Docker CE 源地址(域名或IP)      地址
  --source-registry        指定镜像仓库地址(域名或IP)           地址
  --branch                 指定 Docker CE 源仓库(路径)          仓库名
  --codename               指定 Debian 系操作系统的版本代号     代号名称
  --designated-version     指定 Docker CE 安装版本              版本号
  --protocol               指定 Docker CE 源的 WEB 协议         http 或 https
  --install-latest         是否安装最新版本的 Docker Engine     true 或 false
  --close-firewall         是否关闭防火墙                       true 或 false
  --clean-screen           是否在运行前清除屏幕上的所有内容     true 或 false
  --only-registry          仅更换镜像仓库模式                   无
  --ignore-backup-tips     忽略覆盖备份提示                     无
  --pure-mode              纯净模式，精简打印内容               无
```

## 适配的操作系统及版本
| 操作系统 | 适配版本 | 
| :-------- | :----- |
| Debian | 8 ~ 13 |
| Ubuntu | 14 ~ 25 |
| Kali Linux | all |
| Linux Mint | 19 ~ 22 / LMDE 6|
| Deepin（深度） | all |
| Armbian | all |
| Proxmox VE | all |
| Raspberry Pi OS | all |
| Red Hat Enterprise Linux | 7 ~ 10 |
| Gentoo | all |
| Manjaro | all |
| Arch Linux | all |
| openKylin（开放麒麟） | all |
| Fedora | 30 ~ 42 |
| CentOS | 7 ~ 8 / Stream 8 ~ 10 |
| Rocky Linux | 8 ~ 10 |
| AlmaLinux	| 8 ~ 10 |
| openEuler（开源欧拉） | 21 ~ 25 |
| OpenCloudOS（鸥栖）	| 8.6 ~ 9 / Stream 23 |
| Anolis OS（龙蜥）	| 8 / 23 |
| openSUSE | Leap 15 / Tumbleweed |
| Alpine Linux	| v3 / edge |
| NixOS	| 19 ~ 25 |
