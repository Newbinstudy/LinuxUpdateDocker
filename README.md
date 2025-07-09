# LinuxUpdateDocker
Docker 安装与换源脚本，感谢大佬开源，参考自 https://github.com/SuperManito/LinuxMirrors ，用于个人学习和研究。

## 使用方法
使用建议：速度上推荐`中科大`、`字节(火山引擎)`，地域兼容性上推荐`阿里云`、`腾讯云`，软件源种类上推荐`南京大学`、`中科院`，境外、海外或复杂网络环境下不建议使用`清华(TUNA)` 等容易阻断的学校镜像站。

### 方法一：
一键运行
```
bash <(curl -sSL https://raw.githubusercontent.com/Newbinstudy/LinuxUpdateDocker/main/docker.sh )
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
